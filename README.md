# comp551-miniproject-2-optimization-and-text-classification-solved
**TO GET THIS SOLUTION VISIT:** [COMP551 MiniProject 2-Optimization and Text Classification Solved](https://www.ankitcodinghub.com/product/comp551-miniproject-2-optimization-and-text-classification-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96426&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP551 MiniProject 2-Optimization and Text Classification Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
<ul>
<li>&nbsp;
Background

The goal of this project is twofold. First, we want you to gain some insight into the optimization process of gradient based methods. In particular, this section will ask you to implement different variations of gradient descent and analyze their impact on the convergence speed. In the second part of the assignment, you will be experimenting with text data. The section encourages you to explore text-specific preprocessing techniques, and to reapply concepts such as cross-validation that are central to machine learning. In both sections, you will be performing binary classification with Logistic Regression.

Part 1 : Optimization

In this section you will be using the diabetes dataset, which you can find in the assignment folder. For this part, you do not need to perform any data cleaning or preprocessing, i.e. you can use the dataset as-is. For this section, we encourage you to leverage the Logistic Regression notebook, which you can find here. For each bullet point, make sure to include clear and concise plots to go with your discussion.
</li>
</ul>
<ol>
<li>You should first start by running the logistic regression code using the given implementation. This will serve as a baseline for the following steps. Find a learning rate and a number of training iterations such that the model has fully converged to a solution. Make sure to provide empirical evidence supporting your decision (e.g. training and validation accuracy as a function of number of training iterations).</li>
<li>Implement mini-batch stochastic gradient descent. Then, using growing minibatch sizes (e.g. 8, 16, 32, …) com- pare the convergence speed and the quality of the final solution to the fully batched baseline. What configuration works the best among the ones you tried ?</li>
<li>Add momentum to the gradient descent implementation. Trying multiple values for the momentum coefficient, how does it compare to regular gradient descent ? Specifically, analyze the impact of momentum on the conver- gence speed and the quality of the final solution.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
4. repeat the previous step for a) the smallest batch size and b) largest batch size you tried in 2). In which setting (small mini-batch, large mini-batch, fully batched) is it the most / least effective ?

Part 2 : Text Classification

In this part, you will be using the fake news dataset. The goal is to detect which articles are generated by a computer, and which ones are written by humans. The dataset has already been split into training, validation, and test. No preprocessing has been applied. A good place to start is the sklearn text data tutorial. For this part, we recommend using the sklearn’s Logistic Regression package as your base model.

Get a basic version working. This includes building a preprocessing pipeline to map raw text to features on which you can train a model. You can go above and beyond, for example, to see if you can achieve more than 80% on the test set.

Deliverables

You must submit two separate files to MyCourses (using the exact filenames and file types outlined below):

<ol>
<li>code.zip: Your entire code, which should consist of a jupyter notebook file (.ipynb), and additional python files (.py); the notebook should contain the main body of your code, where we can see and easily reproduce the plots in your report.</li>
<li>writeup.pdf: Your (max three pages) project write-up as a pdf (details below).</li>
</ol>
Project write-up

Your team must submit a project write-up that is a maximum of three pages (single-spaced, 11pt font or larger; minimum 1 inch margins, an extra page for references/bibliographical content can be used). We highly recommend that students use LaTeX to complete their write-ups. You have some flexibility in how you report your results, but you must adhere to the structure discussed in the first assignment. As before you can also have a statement of the breakdown of the workload across the team members.

Evaluation

The mini-project is out of 10 points, and the evaluation breakdown is as follows: • Completeness (2 points)

– Did you submit all the materials?

– Did you run all the required experiments?

– Did you follow the guidelines for the project write-up?

• Correctness (4 points)

– Are your models used/implemented correctly?

– Are you visualizations informative and visually appealing?

– Are your reported accuracy close to (our internal) reference solutions? – Are you observing the expected trends?

• Writing quality (2.5 points)

<ul>
<li>– &nbsp;Is your report clear and free of grammatical errors and typos?</li>
<li>– &nbsp;Did you go beyond the bare minimum requirements for the write-up (e.g., by including a discussion of related work in the introduction)?</li>
<li>– &nbsp;Do you effectively present numerical results (e.g., via tables or figures)? • Originality / creativity (1.5 points)
– Did you go beyond the bare minimum requirements for the experiments?
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
– within the context of producing the required results did you propose a creative idea?

– Note: Simply adding in a random new experiment will not guarantee a high grade on this section! You should be thoughtful and organized in your report in explaining why you performed an additional experiment and how it helped in evaluating your hypothesis.

Final Remarks

You are expected to display initiative, creativity, scientific rigour, critical thinking, and good communication skills. You don’t need to restrict yourself to the requirements listed above – feel free to go beyond, and explore further.

You can discuss methods and technical issues with members of other teams, but you cannot share any code or data with other teams.

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
