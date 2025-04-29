# mast90104-lab-7-solved
**TO GET THIS SOLUTION VISIT:** [MAST90104 Lab 7 Solved](https://www.ankitcodinghub.com/product/mast90104-a-first-course-in-statistical-learning-solved-6/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;112917&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;MAST90104 Lab 7 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
1 Practical questions

1. The data teengamb from the faraway package contains data from a survey in Britain to study teenage gambling. The variables are

• sex: 0=male, 1=female

• status: Socioeconomic status score based on parents’ occupation income in pounds per week

• verbal: verbal score in words out of 12 correctly defined

• gamble: expenditure on gambling in pounds per year We can import the data by

data(teengamb)

We are interested in predicting gamble using the other variables. Implement the following variable selection methods to determine the “best” model

(a) Backward elimination

(b) Forward selection

(c) Stepwise selection

Comment on the AIC of the final model chosen by the 3 methods.

2. Load and examine the dataset trees using

data(trees) ?trees pairs(trees)

We will model the volume of a black cherry tree as a function of its girth and height.

(a) By calculating R(γ1|γ2) and SSRes from the data y and design matrix X, use an F test to determine if including the variable Height significantly improves the model fitted using only Girth (and an intercept).

Repeat the test using the lm and anova commands, to see if you get the same numbers.

(b) Add variables Girth squared and Girth squared times Height to the model, then use stepwise selection to simplify the model. (You can use step for this step.) Comment on the form of your final model.

(c) Use diagnostic plots to check the fit of your final model.

(d) What transformation might be indicated from the plot of residuals versus fitted values? Transform all variables with this transformation. What might the appropriate model be? Fit it and comment on the resulting residuals.

3. In a manufacturing plant, filters are used to remove pollutants. We are interested in comparing the lifespan of 5 different types of filters. Six filters of each type are tested, and the time to failure in hours is given in the dataset (on the website) filters (in csv format).

(a) Use the read.csv function to read the data. Then convert the type component into a factor.

(b) Using only the matrix command, construct a y vector and a full rank X for this linear model, corresponding to cont.treatment

(c) Fit the models and compare with the lm output.

(d) Calculate s2 using the residuals

2 Workshop questions

1. Show that R2 is the square of the correlation coefficient between the data and the fitted values. [Hint: write the response as fit + residual. Express the correlation coefficient as that of a random vector which chooses randomly from the data (both y and corresponding row of X) and has values of response and fit. Use rules for covariance and the correlation between fitted values and residuals.] 2. Show that the adjusted R2 satisfies:

2 − estimate of σ2using the model

adjusted R = 1 estimate of σ2assuming equal means

3. Suppose each row of a dataset has a response variable and two factors, which have 2 and 3 possible levels respectively. The dataset has 2 rows for each possible combination of factor levels. We model this with a less than full rank model with one parameter for the overall mean, and one parameter for each level of each factor, assuming that the overall mean is adjusted additively by each factor. Write down the linear model in both equation and matrix form. 4. Let

.

(a) Show that r(A) = 2.

(b) Construct two different full rank matrices which generate the same column space as A.

5. It is known that toxic material was dumped into a river that flows into a large salt-water commercial fishing area. We are interested in the amount of toxic material (in parts per million) found in oysters harvested at three different locations in this area. A study is conducted and the following data obtained:

Site 1 Site 2 Site 3

15 19 22

26 15 26

(a) Write down the linear model in matrix form.

(b) Write down the normal equations.

(c) Reparameterize the model to a full rank model.

(d) Find a solution for the normal equations.

6. In the one-way classification model, show that any linear combination of ¯y1 −y¯·,…,y¯k −y¯· can be written as a linear combination of ¯y1,…,y¯k. Does the converse hold?
