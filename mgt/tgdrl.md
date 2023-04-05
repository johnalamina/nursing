


[Geron](https://nbviewer.org/github/ageron/handson-ml2/blob/master/index.ipynb)
1. ML Landscape
2. ML End-to-end
3. Classification
4. Training models
5. SVM
6. Decision Trees
7. Ensemble learning and random forests
8. Dimensionality reduction
9. Unsupervised Learning
Part 2
10. Neural Newroks
11. NN Training
12. Custom models
13. Loading data
14. CNN
15. RNN
16. NLP
17. GAN
18. Reinforcement
19. Training at scale

https://github.com/ageron/handson-ml2

## Notebooks[¶](https://nbviewer.org/github/ageron/handson-ml2/blob/master/index.ipynb#Notebooks)

1.  [The Machine Learning landscape](https://nbviewer.org/github/ageron/handson-ml2/blob/master/01_the_machine_learning_landscape.ipynb)
2.  [End-to-end Machine Learning project](https://nbviewer.org/github/ageron/handson-ml2/blob/master/02_end_to_end_machine_learning_project.ipynb)
3.  [Classification](https://nbviewer.org/github/ageron/handson-ml2/blob/master/03_classification.ipynb)
4.  [Training Models](https://nbviewer.org/github/ageron/handson-ml2/blob/master/04_training_linear_models.ipynb)
5.  [Support Vector Machines](https://nbviewer.org/github/ageron/handson-ml2/blob/master/05_support_vector_machines.ipynb)
6.  [Decision Trees](https://nbviewer.org/github/ageron/handson-ml2/blob/master/06_decision_trees.ipynb)
7.  [Ensemble Learning and Random Forests](https://nbviewer.org/github/ageron/handson-ml2/blob/master/07_ensemble_learning_and_random_forests.ipynb)
8.  [Dimensionality Reduction](https://nbviewer.org/github/ageron/handson-ml2/blob/master/08_dimensionality_reduction.ipynb)
9.  [Unsupervised Learning Techniques](https://nbviewer.org/github/ageron/handson-ml2/blob/master/09_unsupervised_learning.ipynb)
10.  [Artificial Neural Nets with Keras](https://nbviewer.org/github/ageron/handson-ml2/blob/master/10_neural_nets_with_keras.ipynb)
11.  [Training Deep Neural Networks](https://nbviewer.org/github/ageron/handson-ml2/blob/master/11_training_deep_neural_networks.ipynb)
12.  [Custom Models and Training with TensorFlow](https://nbviewer.org/github/ageron/handson-ml2/blob/master/12_custom_models_and_training_with_tensorflow.ipynb)
13.  [Loading and Preprocessing Data](https://nbviewer.org/github/ageron/handson-ml2/blob/master/13_loading_and_preprocessing_data.ipynb)
14.  [Deep Computer Vision Using Convolutional Neural Networks](https://nbviewer.org/github/ageron/handson-ml2/blob/master/14_deep_computer_vision_with_cnns.ipynb)
15.  [Processing Sequences Using RNNs and CNNs](https://nbviewer.org/github/ageron/handson-ml2/blob/master/15_processing_sequences_using_rnns_and_cnns.ipynb)
16.  [Natural Language Processing with RNNs and Attention](https://nbviewer.org/github/ageron/handson-ml2/blob/master/16_nlp_with_rnns_and_attention.ipynb)
17.  [Representation Learning and Generative Learning Using Autencoders and GANs](https://nbviewer.org/github/ageron/handson-ml2/blob/master/17_autoencoders_and_gans.ipynb)
18.  [Reinforcement Learning](https://nbviewer.org/github/ageron/handson-ml2/blob/master/18_reinforcement_learning.ipynb)
19.  [Training and Deploying TensorFlow Models at Scale](https://nbviewer.org/github/ageron/handson-ml2/blob/master/19_training_and_deploying_at_scale.ipynb)

## [Scientific Python tutorials](https://nbviewer.org/github/ageron/handson-ml2/blob/master/index.ipynb#Scientific-Python-tutorials)

-   [NumPy](https://nbviewer.org/github/ageron/handson-ml2/blob/master/tools_numpy.ipynb)
-   [Matplotlib](https://nbviewer.org/github/ageron/handson-ml2/blob/master/tools_matplotlib.ipynb)
-   [Pandas](https://nbviewer.org/github/ageron/handson-ml2/blob/master/tools_pandas.ipynb)

## [Math Tutorials](https://nbviewer.org/github/ageron/handson-ml2/blob/master/index.ipynb#Math-Tutorials)

-   [Linear Algebra](https://nbviewer.org/github/ageron/handson-ml2/blob/master/math_linear_algebra.ipynb)
-   [Differential Calculus](https://nbviewer.org/github/ageron/handson-ml2/blob/master/math_differential_calculus.ipynb)

## [Extra Material](https://nbviewer.org/github/ageron/handson-ml2/blob/master/index.ipynb#Extra-Material)

-   [Auto-differentiation](https://nbviewer.org/github/ageron/handson-ml2/blob/master/extra_autodiff.ipynb)

## .[Misc](https://nbviewer.org/github/ageron/handson-ml2/blob/master/index.ipynb#Misc.)

-   [Equations](https://nbviewer.org/github/ageron/handson-ml2/blob/master/book_equations.pdf) (list of equations in the book)

## [Prerequisites](https://nbviewer.org/github/ageron/handson-ml2/blob/master/index.ipynb#Prerequisites)

### To [understand](https://nbviewer.org/github/ageron/handson-ml2/blob/master/index.ipynb#To-understand)

-   **Python** – you don't need to be an expert python programmer, but you do need to know the basics. If you don't, the official [Python tutorial](https://docs.python.org/3/tutorial/) is a good place to start.
-   **Scientific Python** – We will be using a few popular python libraries, in particular NumPy, matplotlib and pandas. If you are not familiar with these libraries, you should probably start by going through the tutorials in the Tools section (especially NumPy).
-   **Math** – We will also use some notions of Linear Algebra, Calculus, Statistics and Probability theory. You should be able to follow along if you learned these in the past as it won't be very advanced, but if you don't know about these topics or you need a refresher then go through the appropriate introduction in the Math section.

## Reinforcement Learning Notes

Reinforcement learning fills the gap between supervised learning, where the algorithm is trained on the correct answers given in the target data, and unsupervised learning, where the algorithm can only exploit similarities in the data to cluster it.  The middle ground is where information is provided about whether or not the answer is correct, but not how to improve it.  The reinforcement learner has to try out different strategies and see which works best.  ‘Trying out’ different strategies is just another way of describing search which is a fundamental part of the reinforcement learning process: the algorithm searches over a state space of possible inputs and outputs in order to try to maximise a reward.

Reinforcement learning is usually described in terms of the interaction between some agent and its environment.  The agent is the thing that is learning, and the environment has another task, which is to provide information about how good a strategy is, through some reward function. 

The importance of reinforcement learning for psychological learning theory comes from the concept of trial-and-error learning, which has been around for a long time, and is also known as the Law of effect. 

Reinforcement learning maps states or situations or actions in order to maximise some numerical reward.  That is, the algorithm knows about the current input (the state), and the possible things it can do (the actions), and its aim is to maximise the rewards.

In reinforcement learning, the algorithms get feedback in the form of reward about how well it is doing. In contrast to supervised learning, where the algorithm is ‘taught’ the correct answer, the reward function evaluates  the current solution, but does not suggest how to improve it.  To further make things complex, the reward may be delayed until several steps into the future.  In order to accommodate such a scenario the concept of immediate and total expected reward are employed.

Once the algorithm has decided on the reward, it needs to choose the action that should be performed in the current state.  This is known as the policy.  This is done based on some combination of exploration and exploitation (remember, reinforcement learning is basically a search method), which in this case means deciding whether to take the action that gave the highest reward last time we were in this state, or trying out a different action in the hope of finding something even better.

### Example: Getting lost

You arrive in a foreign city exhausted after many hours of flying, catch the first train into town and stagger into a backpacker’s hotel without noticing much of your surroundings.  When you wake up it is dark and you are starving, so you set off for a wander around town looking for somewhere to eat.  Unfortunately, it is 3 a.m. and, even more unfortunately, you soon realise that you are completely lost.  To make matters worse, you discover that you can’t remember the name of the backpacker’s, or much else about it except that it is in one of the old squares.  Of course, that doesn’t help much because this part of the city pretty much consists of old squares.  There are only two things in your favour: you are fairly sure that you’ll recognise the building, and you’ve studied reinforcement learning and decided to apply it.

You are sure that you’ve only walked through the old part of the city, so you don’t need to worry about any street that takes you out of the old part.  So at the next bus stop you come to, you have a proper look at the map, and note down the map of the old town squares, which turns out to look like figure 13.3.

![](https://lh4.googleusercontent.com/A-nB_cy59-AGl2_CpEp4mU4iDF0NgngOzoMm-zAq--K0VIbXYrSrO5LFZipGE45VrYVrG2OkCpNyOSG0fMk9SfLT6qmxRbXOZeglEPHlddj44tnr4Df8dHECXe_FILMBPolfdlXi77tsx79wlV-94A)

Figure 13.3: Getting lost town

As you finish drawing the map you notice a 24-hour shop and buy as many bags of potato chips as you can fit into your pockets.  As a reinforcement learner you decide to reward yourself when you take actions that lead to the backpacker’s rather than stuff your face immediately (delayed reward).  After thinking about a reward structure you decide that the only one that will work is to eat until you can eat no more when you actually get to the backpacker’s, and not to reward  yourself until then.  Inspired by the idea, you decide the backpacker is almost definitely in square labelled F on the map, because its name seems vaguely familiar.  You decide to work out a reward structure so that you can follow a reinforcement learning algorithm to get to the backpacker’s.  The first thing you work out is that staying still means that you are sleeping on your feet, which is bad.  So you assign yourself a reward of -5 for that (while negative reinforcement can be viewed as punishment, it doesn’t necessarily correspond clearly, but you might want to imagine it as pinching yourself so you stay awake).  Of course, once you reach state F you are in the backpacker’s and will therefore stay there.  This is known as an absorbing state, and is the end of the problem, when you get the reward of eating all the chips you bought.  Now moving between two squares could be good, because it might take you closer to F. But without looking at the map, you won’t know that, so you decide to  just apply a reward when you actually reach F, and leave everything else as neutral.  Where there is no direct road between two squares (so that no action takes you from one to the other) there is no reward because it  is not a viable action.  This results in the reward matrix R shown and also in Figure 11.4:

![](https://lh5.googleusercontent.com/4sk-Hrf3EfYIi6TOlUFGP53z1kor-jlYg0zRjYIE3mPMQ1ztrHNrWQ6oVomECzWTiKhfK9wCKN--yWMc7a47CnXa1-BXjIJsn8AVyAYk3x9zEWzaD1yPIQJ6Z1iner5sKBkoT-pCzpsEPwKeVuZivg)

  

![](https://lh6.googleusercontent.com/dcBtp5WsZYmZH_Jqs7uKrYlQbrNKqzTpS3Hp5gFFuCLYYQ8DV5cCUfzfpB_qlhY3uqE2Gsk3zREbecZf0dmX75j_smZMgdbeNV5NyPRZdWM61iImILaXkzL-fhN9LGJ6ePNJTnQyGInqyv4SZ6CJ0w)

Of course, as a reinforcement learner you don’t actually know the reward matrix.  That’s pretty much what you are trying to discover, but it doesn’t make for a very good example. 

## State action and spaces

The set of all states that are posible for the learner to experience is known as the **state space**.  There is a corresponding **action space** that contains all of the possible actions.  If we can reduce the size of the state space and action space, then it is almost always a good idea, providing that it does not oversimplify the problem.  In the example, there are only six states, but if one wonders through them repeatedly it will take a long time and this generally is the case.

Computing the size of the state space (and corresponding action space) is relatively simple.  For example, suppose that there are 5 inputs, each an integer between 0 and 100.  The size of the state space is then $100^5$, which is incredibly large, so the curse of dimensionality is kicking in here. However, if we decide we can quantize the data so that instead of 100 numbers there are only two for each input (for example by assigning every number less than 50 to class 1, and every number 50 and above to class 2), then the size of the state space is more manageable $2^5 = 32$.  Choosing the state space and action space carefully is therefore a crucial part of making a successful reinforcement learner.  You want them to be as small as possible without losing accuracy in the results.  Reducing the input from 100 to 2, has certainly thrown away a lot of information that may have made the quality of the answer better, so there is a trade off between the two.

## The reward function

The basic idea is that the learner will choose the action that gets the maximum expected reward.  The reward function takes the current state and the chosen action and produces a numerical reward based on them.  So in if w are in state A, and choose the action of doing nothing, so that we remain in state A, we get a reward of -5.  Note that the reward can be positive or negative.

## Discounting
The solution to this problem is known as discounting, and means that we take into account how certain we can be about things that happen in the future: there is lots of uncertainty in the learning anyway, so we should discount our predictions o rewards in the future according to how much chance there is that they are wrong.  The rewards that we expect to get very soon are probably going to be the more accurate predictions than those  a long time in the future, because lots o other things might change. So we add an additional parameter $0\le\gamma\le 1$, and then discount future rewards by multiplying them by $\gamma^t$, where $t$ is the number of timesteps in the future this reward is from,  as $\gamma$ is less than 1, so $\gamma^2$ is smaller.  Again as $\gamma^k \to 0$ as $k \to \infty$ (i.e. $\gamma$ gets smaller and smaller as k gets larger and larger) .  So that we can ignore most of the future predictions.  This means that our prediction of the total future reward is: $$R_4 = r_{t+1}+\gamma r_{t+2}+\gamma r_{t+2}+\gamma^2 r_{t+2}+\dots+\gamma^{k-1}r_k\quad\quad (11.1)$$
Obviously, the closer $\gamma$ is to zero, the less distance we look into the future, while with $\gamma=1$ there is no discounting, as in the episodic case above (in fact discounting is sometimes used for episodic learning as well, since the eventual reward could be a very long way off, and we need to deal with that uncertainty in learning somehow).  We can apply discounting to the example of learning to walk.  When you fall over you give yourself a reward of -1, and otherwise there are no rewards.  The -1 reward is discounted into the future, so that a reward k steps into the future has Edward $-\gamma^k$. The learner will therefore try to make k as large as possible, resulting in the proper walking.

The point of the reward function is that it gives us a way to choose what to do next - our predictions of the reward let us exploit our current knowledge and try to maximise the reward we get.  Alternatively, we can carry on exploring and trying out new actions in the hope that we find ways to get even larger rewards.  The methods of exploration and exploitation that we carry out are methods of action selection that we perform.

## Action selection

At each stage of the reinforcement learning process, the algorithm looks at the actions that can be performed in the current state and computes the value of each action, that is, the average reward that is expected for carrying out the average reward that has been received each time in the past.  This is known as Qs,t(a), where s is the state, a is the action and t is the number of times that the action has been taken before the current state.  This will eventually converge to the true prediction of the reward for that action.  Based on the current average reward predictions, there are three methods of choosing actions that are worth thinking about for reinforcement learning. We’ve seen the first and third of them before

1.  Greedy: pick the action that has the highest value of Qs,t(a), so always choose to exploit your current knowledge
    
2.  $\varepsilon$-greedy:  this is similar to the greedy algorithm, but with some small probability $\varepsilon$ we pick some other action at random.  So nearly every time we take the greedy option, but occasionally, we try out an alternative in the hope of finding a better action.  This throws some exploration into the mix. \epsilon-greedy selection finds better solutions over time than the pure greedy algorithm, since it can explore and find better solutions.
    
3.  Softmax: One refinement of \epsilon-greedy is to think about which of the alternative action to select the exploration happens.  The \epsilon-greedy algorithm chooses the alternatives with uniform probability.  Another possibility is to use the softmax function to make the selection
    

![chart](https://lh4.googleusercontent.com/J7r4SusX4Aq0sm893m5ztZURUIyFVEFH_MJMoVeUHXq--YvuvsMb0Vb2M5qE-H8qhdLB4wNROcK95Cv46W1VbP0RD7vhHAyujKyBWKenvc4rvi8jwoeXrmPmojpQ17FmLJ2J_d9aVrBe21qRcnlWBA) - - - (13.2)

Here, there is a new parameter \tau, which is known as the temperature because of the link to simulated annealing.  When \tau is large, all actions have similar probabilities, when \tau is small, the selection probabilities matter more.  In softmax selection, the current best (greedy) action will be chosen most of the time, but the others will be chosen proportional to their estimated reward, which is updated whenever they are used.

## Policy

## Markov Decision Processes

### Markov Decision Property

The importance of this can be seen from the following two equations

### Probabilities in Markov Decision processes

## Values (Q-learning)
...
The Q(s,a) version looks very similar, except that we have to include the action information.  In both cases we are using the difference between the current and previous estimates, which is why these methods have the name of temporal difference (TD) methods.  Suppose that we know rather more about where we had been.  In that case, we could have updated more states when we got to the backpacker’s, which would have been rather more efficient.  The trouble is that we don’t know if those states were useful or not - it might have been chance that we visited them.  The answer to this is similar to discounting: we introduce another parameter 0 <= \lambda <= 1 that we apply to reduce the amount that being in that particular state matters.  The way this works is known as an eligibility trace, where an eligible state is one that you have visited recently, and it is computed by setting:

![chart](https://lh5.googleusercontent.com/6DBrHfkvkwMWZSLhIKEAyNI0RYrSeeUvw06JFpU4Z1obpbNd3lPODM2cJvBhr3NxKshh7waVqrIF6CcKAFSVfQ4fBLm_7ESNF6XDvWFfWl1trUt_fvefJOu-7ccVVVL6mp8Ln7x7A51RtoJ63GUQhA) - - - ([13.9](http://chart.apis.google.com/chart?cht=tx&chl=e_t(s%27%2Ca%27)%3D%5Cbegin%7Bcases%7D%0A1%20%26%26%26%20if%20s%27%3Ds%2C%20a%27%20%3D%20s%5C%5C%0A%5Cgamma%5Clambda%20e_%7Bt-1%7D(s%27%2Ca%27)%20%26%26%26%20otherwise%0A%5Cend%7Bcases%7D))

If \lambda=0 then you only use the current state, which was the algorithm we had above.  For \lambda=1 you retain all the knowledge of where you have been.  It can be shown  that the TD(0) algorithm (i.e., the TD(\lambda) algorithm with V\pi for the current policy \pi.  There are some provisos on the values of the parameter \mu, which are usually satisfied by incrementally reducing the size of \mu as learning progresses.  The TD(0) algorithm for Q values is also known as the Q-learning algorithm

### Q-Learning Algorithm

-   Initialisation
	-   Set Q(s,a) to small random values for all s and a
-   Repeat
	-   Initialise s
	-   Repeat:
		-   Select action a using \epsilon-greedy or another policy
		-   Take action a and receive reward r
		-   Sample new state s’
		-   Update ![chart](https://lh4.googleusercontent.com/UggFhhcf7Rr0AIcSoYy5SpWdZYkbfXPoLn1BR_g1Ya5bYKyPlVri42dWsf6rTs_b5ZOBKR4Lz-nkoN2UfCxAa2h-I3g16c1dL1Wm-ingNjNxZudHztQ2vUMws2wi1nT8utF-VS9p9OOLsrNed9WRpQ)
		-   Set s ← s’
	-   For each step of the current episode
-   Until there are no more episodes.

Note that we can do exactly the same thing V(s) values instead of Q(s,a) values.  There is one this algorithm that is slightly odd, which is in the computation of Q(s’,a’).  We do not use the policy to find the value of a’, but instead choose the one that gives the highest value.  This is known as an off-policy decision.  Modifying the algorithm to work on-policy is very easy.  It gets an interesting name based on the fact that it uses the set of values (st, at, rt+1, st+1,at+1), which reads ‘sarsa’.

### The Sarsa algorithm

-   Initialisation
-   Set Q(s,a) to small random values for all s and a
-   Repeat
	-   Initialise s
	-   Choose action a using the current policy
	-   Repeat
		-   Take action a and receive reward r
		-   Sample new state s’
		-   Choose action a’ using the current policy
		-   Update ![chart](https://lh4.googleusercontent.com/GpsgJDtHg17jrWhbb1Q8o6hJoGRbRR_P7YrsT22K3JIgPhN4m32reOwZgCPSjucnxYGPTFL4m1IahdQm8_sIgwsYStxFFKW0ehkcxJ2xG0sFMB2LEPzznw87s_K6lQDzSW-M3ouRcdlSUKQT8MYs2A)
		-   s ← s’, a ← a’
	-   For each step of the current episode
-   Until there are no more episodes

The two algorithms are very similar. They are both bootstrap methods, because they start from poor estimates of the correct answers and iteratively updates them as the algorithm progresses.   The algorithms work on-line, with the values of Q being updated as soon as rt+1 and st+1 are known.  In both cases, we are updating based only on the next state and reward.  We could delay our updating for longer, until we knew of rt+n and st+n, and then use a TD(\lambda) algorithm.  The only difficulty with this is that st+n, and then use a TD(\lambda) algorithm.  The only difficulty with this is that there are many different actions that could be taken between st and st+n. 

Once the details of the reward and transition matrices have been sorted out, the implementation of the algorithms doesn’t hold many surprises.  For example, the central part of the sarsa algorithm using the epsilon-greedy policy can be written in this form.

### Back on Holiday - example

Using the example of finding the way back to the backpacker’s by using \epsilon-greedy policy.  The specification of the problem is to set up in the reward matrix R and  transition matrix t, so the first thing to do is work out how to describe those, neither of which is very difficult since they were given. NumPy has a useful inf value, so -inf can be used as rewards for impossible actions.

It is then just a question of running the algorithm for parameter choices of \lambda, \mu, \epsilon, and the number of iteration.  A run with \lambda=0.4, \mu = 0.7, \epsilon = 0.1, and 1,000 iteration (with either sarsa or Q-learning), produced the following Q matrix:

![[Pasted image 20230226173806.png]]

Some of the 0s can becomes -infs eventually.  The question is how to interpret and use this matrix, and the answer is to simply apply the policy at each point, choosing the maximum available Q value for the current state most of the time until you reach the goal.  So from A, the policy wil direct you to move B(Q=16) then on to C (Q = 40) and so to F.  From D you can go either C or E (Q=40) and from either of those, directly to F.

## Sarsa Vs Q-learning.

# Grokking DRL ([Morales](https:/github.com/mimoralea/girl))

## Contents
1. Introduction
	1. What is DRL
	2. The past, present and future of DRL
	3. The suitability of DRL
	4. Setting clear two-way expectations
2. Mathematical foundation of  RL
	1. Components of reinforcement learning
	2. MDPs: The engine of the environment
3. Balancing immediate and long-term goals
	1. The objective of decision-making agent
	2. Planning optimal sequences of actions
4. Balancing the gathering and use of information
	1. The challenge of interpreting evaluative feedaback
	2. Strategic exploration
5. Evaluating agents' behaviours
	1. Learning to estimate the value of policies
	2. Learning to estimate from multiple steps
6. Improving agent's behaviours
	1. The anatomy of reinforcement learning agents
	2. Learning to improve policies of behaviour
	3. Decoupling behaviour from learning
7. Achieving goals more effectively and efficiently
	1. Learning to improve policies using robust agents
	2. Agents that interact, learn and plan
8. Introduction to value-based deep reinforcement learning
	1. The kind of feedback deep reinforcement learning agents use
	2. Introduction to function approximation or reinforcement learning
	3. NFQ: The first attempt at value-based deep reinforcement learning
9. more stable value-based methods
	1. DQN:Making reinforcement learning more like supervised learning
	2. Double DQN: Mitigating the overestimation of action value functions
10. Sample-efficient value-based methods 
	1. Duelling DDQN: A reinforcement-learning-aware neural network  architecture. 
	2. PER: Prioritizing the of meaningful experiences
11. Policy-gradient and actor-critic methods
	1. Reinforce: Outcome-based policy learning
	2. VPG: Learning a value function
	3. A3C: Parallel policy updates 
	4. GAE: Robust advantage estimation
	5. A2C: Synchronous policy updates
12. Advanced actor-critic methods
	1. DDPG: Approximating a deterministic policy
	2. TD3: State-of-the-art improvements over DDPG
	3. SAC: Maximising the expected return and entropy
	4. PPO Restricting optimisation steps
13. Toward artificial general intelligence
	1. What was covered and what notably wasn't
	2. More advanced concepts towards AGI
	3. What happens next


Summary of concepts
1.  Reinforcement Learning (RL): RL is a type of machine learning where an agent learns how to make decisions based on feedback from an environment. The agent receives a reward signal for each action it takes, and its goal is to maximize the total reward it receives over time.
    
2.  Deep Learning: Deep learning refers to a family of machine learning techniques that use artificial neural networks to model and solve complex problems. In deep reinforcement learning, deep neural networks are used to approximate the optimal policy of an RL agent.
    
3.  Q-Learning: Q-learning is a popular RL algorithm that uses a function called the Q-function to approximate the optimal policy of an agent. The Q-function represents the expected total reward an agent will receive if it takes a particular action in a particular state.
    
4.  Policy Gradient Methods: Policy gradient methods are a family of RL algorithms that directly optimize the policy of an agent. These methods use gradient descent to update the parameters of a policy neural network in order to increase the expected total reward.
    
5.  Exploration-Exploitation Tradeoff: The exploration-exploitation tradeoff is a fundamental problem in RL where an agent must balance the desire to exploit actions that are known to be good with the need to explore new actions that may lead to better long-term rewards. RL algorithms use various strategies, such as epsilon-greedy exploration and Thompson sampling, to balance this tradeoff.

6.  Markov Decision Processes (MDPs): MDPs provide a mathematical framework for formalizing the RL problem. An MDP consists of a set of states, actions, transition probabilities, and reward functions, and it assumes that the future state and reward only depend on the current state and action.
    
7.  Value-Based Methods: Value-based methods are a family of RL algorithms that use a value function to approximate the optimal policy of an agent. The value function represents the expected total reward an agent will receive starting from a particular state.
    
8.  Actor-Critic Methods: Actor-critic methods are a family of RL algorithms that combine the advantages of policy gradient methods and value-based methods. In these methods, an actor neural network learns to select actions, and a critic neural network learns to estimate the value function.
    
9.  Experience Replay: Experience replay is a technique used in deep RL to store and reuse transitions from the agent's interaction with the environment. By sampling transitions from a replay buffer, the agent can learn from past experiences and break correlations between consecutive transitions.
    
10.  Deep Q-Networks (DQNs): DQNs are a popular value-based RL algorithm that uses a deep neural network to approximate the Q-function. DQNs were one of the first successful applications of deep learning in RL and have been used in a wide range of applications, from playing Atari games to controlling robots.

Deep reinforcement learning (DRL) is a subfield of artificial intelligence that combines deep learning and reinforcement learning to enable agents to learn from experience to perform complex tasks. While DRL has shown remarkable successes in a variety of applications, it is not yet clear how it will contribute to the development of artificial general intelligence (AGI).

AGI refers to a hypothetical form of AI that can perform any intellectual task that a human can. It requires a level of flexibility and adaptability that current AI systems do not possess. While DRL has made significant strides in addressing complex tasks, it is still limited by the narrowness of the tasks for which it is designed. DRL systems are highly optimized for specific tasks, and their ability to generalize to new tasks or environments is limited.

To contribute toward AGI, DRL will need to become more flexible, adaptable, and generalizable. This may involve developing new algorithms that can learn from a broader range of experiences, including unsupervised learning and self-supervised learning. It may also involve developing systems that can learn from fewer examples and transfer knowledge more efficiently between tasks and domains.

In summary, while DRL has made impressive strides in addressing complex tasks, it is still a long way from contributing toward AGI. More research and development will be needed to make DRL systems more flexible, adaptable, and generalizable to approach the level of human intelligence.

Here are summaries of three academic papers that attempt to utilize deep reinforcement learning to achieve artificial general intelligence:

1.  "Playing Atari with Deep Reinforcement Learning" by Mnih et al. (2013): This paper introduced the Deep Q-Network (DQN), a deep reinforcement learning algorithm that uses a neural network to approximate the Q-function. The authors demonstrated that DQN can learn to play 49 Atari games with superhuman performance, showing that deep reinforcement learning can enable agents to learn from raw sensory input and achieve human-level performance on a range of tasks.
    
2.  "Mastering the game of Go with deep neural networks and tree search" by Silver et al. (2016): This paper introduced AlphaGo, a system that combines deep neural networks and Monte Carlo tree search to play the game of Go. The authors demonstrated that AlphaGo could defeat the world champion in a series of matches, showing that deep reinforcement learning can enable agents to learn from experience and make strategic decisions in complex games.
    
3.  "OpenAI Five" by OpenAI (2019): This paper describes OpenAI Five, a team of five agents that use deep reinforcement learning to play the game Dota 2. The agents learn to coordinate with each other and make strategic decisions in real-time, showing that deep reinforcement learning can enable agents to collaborate and communicate with each other to achieve complex goals.

These papers demonstrate that deep reinforcement learning can enable agents to learn from experience and achieve human-level performance on a range of complex tasks, including playing games and collaborating with other agents. However, it is still an open question whether deep reinforcement learning can enable agents to achieve true artificial general intelligence. More research is needed to develop more flexible and adaptable deep reinforcement learning algorithms that can approach the level of human intelligence.

## Chapter 1 What is DRL
1. Machine learning approach to artificial intelligence
2. Involves creating computer programs that learn through trial, error and feedback that is 
	1. Simultaneous
	2. Sequential
	3. Evaluative
	4. Sampled and
	5. Leveraged by non linear function approximation
### Ingredients of DRL
1. Deep learning.  This could involve the following
	1. Perceptron
	2. Machine learning
	3. Expert systems
	4. NLP
	5. Computer vision
	6. Logic
	7. Robotics
	8. Search
	9. Planning
2. Ai
	1. Supervised
	2. Unsupervised
	3. Reinforcement learning 
3. Intelligence-related problems can be solved by deep learning
4. Trial and error learning 
5. Evaluative feedback 
6. Sampled feedback
7. Nonlinear function approximation

### Timeline
- 1990s.TD-Gammon: by Gerald Tesaur et al.  Learned to play backgammon by learning to evaluate table positions on its own through RL. Architecture:
	1. Handcrafted features, not deep learning
	2. Non deep neural network 
	3. Output of the network was predicted probability of winning, given the current game state
- 2004, Andrew Ng et al. Autonomous helicopters fly stunts from human experts using *Inverse reinforcement learning*.
- 2004, Nate Kohl, and Peter Stone - *Policy Gradient Methods*. Fastest forward moving Robocup agent with only 3 hours training.
- 2013,2015, Mnih et al. Deep Q networks (DQN) Learned to play Atari games from raw pixels using CNN and single set of hyperparameters. Won human professionals 22 of 49 games. Atari DQN architecture:
	1. Last four frames as inputs needed to infer velocities
	2. Features learned through (CNN)
	3. Features fed through Feed forward network
	4. Output layer return estimated  expected value for each action (up, down fire, etc.)
- 2014, Silver et al.: Deterministic Policy Gradient (DPG)
- 2015, Lillicrap et al: Deep Deterministic Policy Gradients (DDPG)
- 2016, Schulman et al: Trust Policy Optimisation (TRPO), Generalised Advantage Estimation (GAE).
- 2016, Sergey Levine et al:  Guided Policy Search (GPS)
- 2016, Silver et al: 
	1. AlphaGo. 
	2. double deep-Q networks (DDQN), 
	3. prioritised experience replay (PER), 
	4. proximal policy optimisation (PPO), 
	5. Actor-critic with experience replay (ACER), 
	6. Asynchrounous advantage actor-critic (A3C), 
	7. advantage actor-critic (A2C), 
	8. actor-critic using Kronecker-factored trust region (ACKTR), 
	9. Rainbow Unicorn etc.
- 2019, Oriol Vinyals.  Alpha Star agent wins star gract II professional players
- 2019, Jakub Pachocki et al:  Dota-2 playing bots called Fire become first AI to beat world champions in an e-sports game.


## Chapters Summary
- 3-7 -> Tabular RL can be exhaustively sampled, and practically no need for function approximation using neural networks.
- 3 -> Sequtntial aspect of RL and temporal credit assignment problem.
- 4 -> Evaluative feedback and exploration vs exploitation
- 5 -> Estimate the result of fixed behaviour
- 6 -> Learning to improve behaviour
- 7 -> Efficient Tabular RL techniques
- 8-12 -> value- and policy based to actor critic methods
- 8-10 -> Value based DRL
- 11 -> Policy based DRL and actor-critic
- 12 -> Deterministic policy gradient  (DPG), soft actor-critic (SAC) and proximal policy optimisation (PPO) methods
Main reward algorithms covered
1. Derivative free
2. Policy based
3. Actor critic
4. value based
5. model-based

Introduction to DRL Summary

DRL is challenging because agents must learn from feedback that is simultaneously sequential, evaluative and sampled.  Learning from seequential  feedback forces the agent to learn how to balance the gatering and the utilisation of information.  Learning from sampled feedback forces the agent to generalise from old to new experiences.

Main areas of AI associated with DRL include
1. Artificial intelligence - Programs having human like or superceding human abilities
2. Machine Learning - The most popular approach to AI.  Can be divided into three areas
	1. Supervised learning
	2. reinforcement learning
	3. unsupervised  machine learning

DRL is the use of multiple layers of powerful function approximators known as neural networks (deep learning) to solve complex sequential decision-making problems under uncertainty.  

The main challenges of applying DRL is associated with sampling complexity, exploration strategies and safe algorithms.

Tweetable handles
1. #gdrl_ch01_tf01: Write a post analysing how supervised, unsupervised and reinforcement learning differ and work together.  How they can be used together to solve a problem.
2. #gdrl_ch01_tf02: Write a list of resources, blog post, YouTube videos, books or any other medium and share with the rest of us also studying decision-making.
3. #gdrl_ch01_tf03: Part of the text in this chapter has information that could be better explained through graphics, tables, and other forms.  For instance, I talked about the different. Tabularise the following value-based, policy-based, actor-critic, model-based, gradient free learning agents.
4. #gdrl_ch01_tf04: General

### RL Blog

- Program so far - Tic Tac Toe game
- GPT-3 Alexa skill
- Bible geneologies project
- Podcast summariser 
- Reinforcement learning from human feedback. 

As a researcher in Artificial Intelligence, I am quite humbled by the advancements made in machine learning.  Machine learning is a data-driven approach to artificial intelligence where smart algorithms are able to make business intelligent inferences based on a large data fed into it. 

In this blog post, I am sharing some of the areas of machine learning that is currently  of interest to me.  In particular, I want to discuss how the three areas of Machine learning, namely supervised, unsupervised and reinforcement learning can work together to achieve specific goals.

## GDRL_CH2 Concepts
### DRL Components Cycle
1. Agent
2. Action
3. Environment
4. Reward
### Agent strategy (decision cycle)
- interact 
- Observe
- Evaluate 
- Improve 
- Action 
#### Environment modelling 
1. State space
2. Observation space
3. Action space
4. Transition function
5. Reward function
6. Model : set of transition and reward functions

### Agent environment cycle
The ability to interact with the environment is represented using MDPs, which in turn needs be following inputs
1. States 
2. Observations
3. Actions 
4. Transition function
5. Reward function

## TGRL

### MDP Samples
1. Hot/cold: Guess a randomly selected number using hints.
	1. Observations: 0-3. 0 means no guess, 1 means guess is lower, 2 means gues is target, 3 means guess is higher
	2. Sample observation 2
	3. Action space: -2000.0 to 2000.0
	4. Sample Action: -909
	5. Reward Function: squared percentage of the way the agent has guessed toward the target.
2. Cart pole:  Balance a pole in a cart
	1. Observations: Four-element vector with ranges: from [-4.8, -inf, -4.2,-Inf] to [4.8, Inf, 4.2, Inf].  First element is the cart position, second element is the cart velocity, third is the pole angle and fourth is the velocity at tip.
	2. Sample observation: [-0.16, -161, 0.27, 2.44]
	3. Action space: Int range 0-1. 0 means  push cart to left, 1 means push cart to right.
	4. Sample action: 0
	5. Reward: The reward is 1 for every step taken incliding the termination step.
2. Cart pole:  Balance a pole in a cart
	1. Observations: Four-element vector with ranges: from [-4.8, -inf, -4.2,-Inf] to [4.8, Inf, 4.2, Inf].  First element is the cart position, second element is the cart velocity, third is the pole angle and fourth is the velocity at tip.
	2. Sample observation: [-0.16, -161, 0.27, 2.44]
	3. Action space: Int range 0-1. 0 means  push cart to left, 1 means push cart to right.
	4. Sample action: 0
	5. Reward: The reward is 1 for every step taken incliding the termination step.
3. Lunar lander:  Navigate a lander to its landing pad
	1. Observations: An eight-element vector with ranges from [-inf, -inf, -inf, -inf, -inf, -inf, 0, 0] to [inf, inf, inf, inf, inf, inf, 1, 1].  First element is the x position, the secon, the y position, the third is the x velocity, the fourth is the y veleocity, firth is the vehicle's angle, sixth is the angular velocity, and the last two values are booleans indicating legs contact with the ground.
	2. Sample observation: [0.36, 0.23, -0.63, 0.10, -97.0,-1.73, 1.0, 0.0]
	3. Action space: Int range 0-3.  No-op (do nothing), fire left engine, fire main engine, fire right engine.
	4. Sample action: 2
	5. Reward: Reward for landing is 200.  There's a reward for moving from top to the landing pad, for crashing or coming to rest, for each leg touching the ground and for firing the engines.
4. Pong:  Bounce the ball past the opponent, and avoid letting the ball pass you.
	1. Observations: A tensor of shape [210, 160, 3]. Values ranging from 0-255. Represents the game screen image.  First element is the cart position, second element is the cart velocity, third is the pole angle and fourth is the velocity at tip.
	2. Sample observation: [[ [246,217,64], [55,184,230]...., [28,104,249] ],..., [ [2,219,64], [122,84,23]...., [228,29,1] ] ]
	3. Action space: Int range 0-5. Action 0 is no-op, 1 is fire, 2 is up, 3 is right, 4 is left, 5 is down. notice how some action do not affect the game in anyway.  In reality the paddle can move up or down or not move.
	4. Sample action: 3
	5. Reward: The reward is 1 when the ball goes beyond the opponent, and a -1 when your agent's paddle misses the ball.
5. Humanoid:  The robot must run as fast as possible and not fall.
	1. Observations: A 44 element (or more, depending on the implementation) vector. Values ranging from -Inf to Inf. Represents the positions and velocities of the robot's joints.
	2. Sample observation: [0.6, 0.08, 0.9, 0.0, 0.0, 0.0, 0.0, 0.0, 0.045, 0.47 ..., 0.32, 0.0, -0.22,..., 0].
	3. Action space: A 17-element vector. Values ranging from -Inf to Inf.  Represents the forces to apply to the robot's joints.
	4. Sample action: [-0.9, -0.06, 0.6, 0.6,0.6, -0.06, -0.4, -0.9, 0.5, -0.2, 0.4, -0.8, -0.1, 0.8, -0.03].  
	5. Reward: The reward is calculated based on forward motion with a small penaltiy to envourage a natural gait.

### Time step, experience tuple, episodic and continuing tasks, return and value function
Interactions  between the and environment go on fo several cycles.  Each cycle is called a _time step_.  A time step is a unit of time, which can be a millisecond, a second, 1.2363 seconds, a minute, a day or any other period of time. 

At each time step, the agent, observes the environment, takes, action, and receives a new observation and reward.  Notice that, even though rewards can be negative values, they are still called rewards in the RL world.  the set of observation (or state), the action, the reward, and the new observation or state is called the _experience tuple_.

The task the agent is trying to solve may or may not have a natural ending.  Tasks that have a natural ending, such as a game, are called *episodic tasks*.  Tasks that don't, such as learning forward motion, are called _continuing tasks_.  The sequence of time steps from beggining to the end of an episodic task is called and *episode*.  Agents may take several time steps and episodes to learn to solve a task.  The sum of rewards collected in a single episode is called a *return*.

Every experience tuple has an opportunity for learning and improving performance.  The agent may have one or more components to aid learning.  The agent may be designed to learning mappings from observations to new observations and/or rewards called models.  the agent may be designed to learn mappings from observations (and possibly actions) to reward-to-go estimates (a slice of the return) called a *value function*.

- Chap2 - Understanding MDPs - the engine of the environment
- Chap3 - agents with no interactions (full MDP access)
- Chap4 - Agent interactions with no MDP in single-state environments (bandits)
- Chap5 - Learning to estimate returns in multi-state environments with no MDPs.
- Chap 6 & 7 - Optimising behaviour, using the full reinforcement learning problem.
- Note chap 5,6&7 comprise classical RL with no function approximation i.e shallow RL.

## GDRL_CH8 Concepts
### Objectives
1. Training RL agents with non-linear function approximators
2. Deep reinforcement agents that when trained from scratch with minimal adjustements to hyperparameters, can solve different kind of problems.
3. Advantages and disadvantages of using value-based methods when solving RL problems.


