## NI Concepts

### Contents
1. Channels and Tasks
2. Timing and triggering
3. Reading and writing data
4. Signal routing
5. Counters
6. Terminals
7. Coercion
8. Callibration
9. Control
10. NI-DAQmx simulated devices
11. Distributed applications
12. Functions, VIs, Properties and attributes
13. External Reference sources for generating  votlage
14. Custom scales

### Outline

1. Channels and Tasks
	1. Concepts
		1. Virtual Channel
		2. Physical Channels
		3. Tasks
	2. Types of Channels
		1. Analog Input channels
		2. Analog output channels
		3. Counter input/output channels
		4. Digital input/output channels
		5. Power channels
	3. Task Concepts
		1. Physical channel ranges
		2. Physical channel lists
		3. Port width: the number of lines in a port
		4. channel name generation from ranges

- Note app = DAQ Assistant, programmatically in your DE such as labView or LabWindows CVI

### Channels and Tasks
#### Tasks
- A task is a collectin of one or more virtual channels with timing triggering and other properties.  Conceptually, a task represents a measurement or generation you want to perform.
- Call channels in a task must be of the same I/O type, such as analog input or counter output. However,
- A task can include channels of different measurement types, such as analog input temperature and anlog input voltage types.
- To create a task follow the following steps
	1. Create or load a task using app
	2. Configure channel, timing and triggering as properties as necessary
	3. Optionally, peform various task state transitions to prepare the task to perform the specified operation
	4. Read or write samples.
	5. Clear task
- Example: Create an NI-DAQmx task to measure temperature in the range 50°C to 200°C using a J-type thermocouple that is wired to channel 0 on an M Series device configured as Device 1. Sample the temperature 10 times per second, and acquire 10,000 samples. Use LabVIEW or LabWindows/CVI to write your application.
	1. Call the AI Temp TC instance of the DAQmx Create Virtual Channel VI in LabVIEW (DAQmxCreateAIThrmcplChan function in LabWindows/CVI). 
	2. Specify Dev1/ai0 as the physical channel for the device connected to the thermocouple signal. 
	3. Specify myThermocoupleChannel as the name to assign to your virtual channel. 
	4. Select the appropriate values for the thermocouple type and range inputs. NIDAQmx applies these attributes to the virtual channel.
	5. Call the Sample Clock instance of DAQmx Timing VI in LabVIEW (or DAQmxCfgSampClkTiming function in LabWindows/CVI), specifying a rate of 10 Hz and a sample mode of finite. 
	6. Call the DAQmx Start Task VI (DAQmxStartTask in LabWindows/CVI). 
	7. Call the Analog 1D DBL 1Chan NSamp instance of DAQmx Read VI (DAQmxReadAnalogF64 in LabWindows/CVI), specifying number of samples per channel as 10,000.
	8. Call the DAQmx Stop Task VI (DAQmxStopTask function in LabWindows/CVI) after the desired number of samples have been acquired. 
	9. Call the DAQmx Clear Task VI (DAQmxClearTask function in LabWindows/CVI).
- Auto/starting/aborting tasks
	- Analog output  task
	- start task function
	- Aborting
		- Is task done
		- Wait until done
- Task types
	- Finite measurement tasks
	- Continuous measurement task
	- Multiple-sample, hardware-timed... 
- Task completion
	- If the measurement or generation is finite, the task is done when you acquire or generate the final sample or when you call the Stop Task function/VI
	- If the measurement or generation is continuous (including on-demand timing), or if retriggering is enabled, the task is not done until you call the Stop Task function/VI. In addition, 
	- the task is done if a fatal error is generated while performing the measurement or generation, or you abort the measurement or generation. 
	- Check for errors and warnings to verify the task completed successfully.
- Task State model
![[Pasted image 20230531114416.png]]
1. Unverified state
2. Verified state
3. Reserved State
4. Commited State
5. Running State
- State Transitions
	1. Running to Committed state
	2. Committed to verified state
- Explicit State events
	1. Verify
	2. Reserve
	3. Commit
	4. Start