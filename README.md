# ai3000---cs5500-reinforcement-learning-assignment-5-solved
**TO GET THIS SOLUTION VISIT:** [AI3000 – CS5500 : Reinforcement Learning Assignment № 5 Solved](https://www.ankitcodinghub.com/product/ai3000-cs5500-reinforcement-learning-assignment-%e2%84%96-5-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;110723&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;AI3000 - CS5500 : Reinforcement Learning Assignment № 5 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Note : Answer any two of the following three problems

The problem involves coding DDPG algorithm and testing in MountainCarContinuous-v0 and LunarLanderContinuous-v2 environments. Assignment 3 had descriptions of similar environments where the action space was discrete. On the contrary, the above environments have continuous action spaces and hence these are continuous control problems. Recall that DDPG algorithm is mainly used for solving continuous control problems.

(a) Develop a small code snippet to load the corresponding Gym environment(s) and print out the respective state and action space. Develop a random agent to understand the reward function of the environment. Record your observations. (3 Points)

(b) Implement the DDPG algorithm to solve the tasks envisioned by the two environments.

Provide corresponding learning graphs in your Jupyter notebooks. (12 Points)

(c) The standard DDPG implementation involves using Ornstein Ulhenbeck (OU) noise for exploration. For this sub question study the implication of using Gaussian noise for exploration and report (with reasons) if solving the task takes similar number of episodes. (5 Points)

Problem 2 : Bandit Algorithms

Consider a multi-arm bandit problem consisting of K arms. Every time an arm is pulled, the agent receives a reward such that where a ∈ {1,2,··· ,K} is the arm that was pulled at time t.

(a) Develop a bandit environment where the reward distribution of each bandit is normally distributed around a given mean (µ) and unit variance. One can use choose appropriate mean reward values for each bandit. The mean reward values for each arm could be well spaced out so that the best arm can be distinctly identified. (2 Points)

(b) Implement greedy, -greedy, -greedy with decay and UCB algorithm to solve the above bandit problem in N rounds. For the -greedy algorithm, consider and .

(Recall that is the greedy strategy) (8 Points)

Assignment № 5 Page 1 (c) For the case of K = 10 and number of rounds N = 1000, plot the average reward obtained using each of the above strategies (in same graph). The x-axis of the plot is the number of rounds (1 to 1000) and y-axis is the average reward obtained in that round. The average reward is computed by running a bandit algorithm multiple times (say 100 times).

(2 Points)

[For example, let’s say we run a bandit algorithm three times. This means that, each time, the agent gets 1000 rounds to pull any of the 10 arms. Corresponding to each time, the agent gets a reward at each round. The average reward is the average values of the reward obtained in each round over multiple times.The bandit environment should be reset every time. ]

(d) Plot a histogram consisting of average number of times each of the 10 arms is pulled for each of the algorithm in sub-question (b) (2 Points)

(e) Plot the average regret as a function of time for each algorithm (2 Points)

(f) From the above plots, reason out which of the above bandit algorithm is better (2 Points)

(g) Repeat the above analysis for the scenario when the mean rewards of the second best arm and the best arm are close (2 Points)

Problem 3 : Monte Carlo Tree Search

(a) Develop a Tic-Tac-Toe agent using the MCTS algorithm. The number of Monte Carlo simulations allowed for each board configuration must be configurable (12 Points)

(b) Test the efficacy of the MCTS agent by soliciting move recommendations for the following board configurations (3 Points)

• A suitable board configuration in which the MCTS agent is one move away from win

• A suitable board configuration in which the MCTS agent is one move away from loss

• The board configuration where the opponent has made the first move and has occupied the centre square

(c) Record the number of wins, loss and draws by letting the MCTS agent play 1000 games against random and safe agents of Assignment 2 (3 Points)

(d) Record of the number of wins, loss and draws by letting the MCTS agent play 1000 games against itself (2 Points)

ALLTHEBEST

Assignment № 5 Page 2
