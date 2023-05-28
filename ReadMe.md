# ProsperLoanData
## by Mohamed Al-Ghaly<br>In this project we applied Univariate/Bivariate/Multivariate Analysis to analyze the data.<br>
### The aim of the project is to use Statistical Analysis techniques to ensure that loans are made on proper terms to clients who can and will pay them back.


## Dataset

> This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.<br>I have included a guide dat set which contain a definition for each column in the data set.<br>I also have chosen only 13 variables to explore both qualitative and quanitative ones and I have cleaned the data, removed missing values and so on.



## Summary of Findings

> From the exploration I have found that<br>
<ul><li>Most of the loans has interest rate between 6 and 20 percent.</li>
<li>There is lots of loans with rate .32 except that most of rates are among 6 and 26.</li>
<li> Most of the loans have a return rate between .06 and .13 with some loans with .2 and above return rate.</li><li>Most loans haveing a duration of 36 months(Three years) and some loans of 5 years and a small fraction of loans with one year period.</li><li>The loan amount is right skewed as most loans have smaller amount</li><li>most loans have monthly payment below 500 with some loans with higher payments</li>
<li> most of the loans have only 1 investor and the others almost have from 2-100 investors and there are so much fewer loans with greater number of investors.</li><li>As we can see The prosper variable is almost normally distributed with peak at C category and smallest count at AA category but as we see the A Prospercount didn't follow the normal distribution and our data set has so much loans with A prosper.
The employment variable in the other hand is almost baised toward the employed category but there is small loans for not employed bborrower which make no sense and as we can see the part time, retired bars are pretty short.
As we all expect the borrower is more likely to be a home owner as this plays the role of guaranteed pay back for the bank.
As we see most of the loans are current loans but there are some loans that are either completed, charged of.</li><li> (loan amount, payment), (rate, return) each of these pairs are strongly positively related, and (loan amount, investors), (payment, investors) are weakly positively related and the other pairs are weakly negatively related.</li><li>It is obvious that the prosper is coerrelated with the rate as we move from lower prosper category to a heigher one A --> B --> C --> D --> E --> HR the interest rate seems to increase which is not surprising, The same correlation is noted also between the prosper and the return variable.</li>
<li>It is obvious and makes sense that the borrower who is NOT a home owner pays more interest rate than the home owner as being homeless raises the risk of not paying back so the bank must make it up, the coerrelation between the home owner and the return is not that strong as they are not related.</li>
<li>The not employed borrower pays more interest rate and that gives the bank more return but the other employment categories is not strongly related with the rate or the return variables.</li>
<li>As we can obviously see the longer term loans seems to get heigher benefit or return to the bank but it is not clearly coerrelated to th interest rate.</li><li>most home owners are employed which make sense.</li><li> mostly the duration has nothing to do with the prosper except that all the HR prospers have a three-year loans.
and It seems that the duration is not coerrelated to the status.</li>
<li>the coerrelation between rate and return is its strongest in 3 years loans.</li>
<li>As we see the higher loans have mostly low rates and average return. </li>
<li>Long term loans have higher return.</li>
</ul>



## Key Insights for Presentation

> For the presentation, I focus on just the influence of the four variables 
both qualitative and quanitative on the variables of interest annual interest rate and the return and leave out most of the intermediate derivations.<br>The variables are: <ol><li>Loan Amount</li><li>Home Owner</li><li>Duration</li><li>Status</li></ol><br> I start by introducing the rate and return variables.
Afterwards, I introduced the numeric variable, then I introduced each of the categorical variables one by one. To start, 
I used histograms to show the distribution of the main variables, then I used scatter plots to show
the coerrelation between them and the numeric variable, then I used both box plot and violin plots to
show the coerrelation between the interest variables and the categorical variables and then I used 
encoding techniques to show the coerrelation between the two numeric variables of interest and the categorical variable status.
