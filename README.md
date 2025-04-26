# cs6601-assignment-2---cross-isolation-p0-solved
**TO GET THIS SOLUTION VISIT:** [CS6601 Assignment 2 – Cross Isolation P0 Solved](https://www.ankitcodinghub.com/product/cs6601-assignment-2-cross-isolation-p0-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;125234&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS6601 Assignment 2 - Cross Isolation P0 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (3 votes)    </div>
    </div>
This assignment will cover some of the concepts discussed in the Adversarial Search lectures. You will be implementing game playing agents for a variant of the game Isolation.

Table of Contents

Get repository

Setup

Jupyter

Jupyter Tips

FAQ

IDE

Get repository

Pull this repository to your local machine:

git clone https://github.gatech.edu/6601Spr24/a2_YourGTGithubUsername

Setup

For this assignment, we highly recommend you to create a new environment just for this one assignment.

conda create -n ai_env_a2 python=3.9

Activate the environment: conda activate ai_env_a2

In case you used a different environment name, to get a list of all environments you have on your machine, you can run conda env list.

Install correct package versions that will be used for visualising the game board.

cd assignment_2 pip install -r requirements.txt

Jupyter

python -m ipykernel install –user –name ai_env_a2 –display-name “Python 3.9 (AI-A2)”

Further instructions are provided in the notebook.ipynb. Run:

jupyter notebook

Once started you can access http://localhost:8888 in your browser.

Jupyter Tips

1. My Jupyter notebook does not seem to be starting up or my kernel is not starting correctly.

Ans: This probably has to do with activating virtual environments. If you followed the setup instructions exactly, then you should activate your conda environment using conda activate &lt;environment_name&gt; from the Anaconda Prompt and start Jupyter Notebook from there.

2. I was running cell xxx when I opened up my notebook again and something or the other seems to have broken.

Ans: This is one thing that is very different between IDEs like PyCharm and Jupyter Notebook. In Jupyter, every time you open a notebook, you should run all the cells that a cell depends on before running that cell. This goes for cells that are out of order too (if cell 5 depends on values set in cell 4 and 6, you need to run 4 and 6 before 5). Using the “Run All” command and its variants (found in the “Cell” dropdown menu above) should help you when you’re in a situation like this.

3. The value of a variable in one of my cells is not what I expected it to be? What could have happened?

FAQ

1. What depth does the server call my search algorithms with?

Ans: The server will not pass a depth value to your CustomPlayer; whatever you set as the default parameter value will be used on Gradescope.

Modifying this default value is extremely important in changing the performance of your agent.

2. How does Gradescope set up and run each game?

Ans: Gradescope will run 20 games in order to determine the win ratio. Your player (CustomPlayer) will be Q1 for 10 of those games and Q2 for 10 of those games. Each player has 1 second to make each move and the first two moves (i.e. each player’s starting location) will be randomized.

3. Can we use multithreading of multiprocessing?

Ans: Sorry, we will not allow multithreading or multiprocessing on this Assignment. It isn’t necessary to successfully complete the Assignment.

4. I have a question about the isolation API or the workings of the framework. Where should I learn more?

IDE

In case you are willing to use IDE (e.g. Pycharm) to implement your assignment in .py file. Please run:

bash python helpers/notebook2script.py submission

You will get autogenerated submission/submission.py file where you can write your code. However, make sure you have gone through the instructions in the notebook.ipynb at least once.

CS6601 Assignment 2 Cross Isolation
