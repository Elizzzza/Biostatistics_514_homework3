# Biostat 514/517 Homework 3
#### Instructor: Ken Rice

- Please read the class site for details on appropriate answering of questions. Discussion of the 
questions with other students, TAs, the instructor, or on the class discussion board is permitted, 
but you should write up your own answers in your own words. 
- Upload your answers to the class site – see under course navigation for “Assignments”. 
- Raw code should not appear in your solutions, but include your code (e.g. your .R script file) as 
an appendix. As well as making your work reproducible, this helps the grader see exactly what 
you have done – and help with any problems. 

### Q1 – 1D summaries 

Medical costs per patient for heart disease are typically very skewed. While most patients’ procedures 
incur some modest cost (e.g. taking a generic statin, or being told to eat better) a very small proportion 
of the sickest patients have extremely expensive procedures, e.g. heart transplants. Write an 
explanation of how a successful new form of treatment for heart disease may raise the median cost per 
patient but lower the mean. 

### Q2 – Kaplan Meier  
For the n=9 example in slides (2.116-2.119) give the exact fractional values of the survival function (the 
red line on slide 2.119) at each event time. Note: main aim of this exercise is to reinforce how the 
‘redistribution’ argument works, but it will require doing some arithmetic, e.g. at the first step on 2.116 
you need to calculate (1/9)/7=1/63. If you need help with the arithmetic, or just want to check your 
work, Wolfram Alpha may be helpful.  

### Q3 – 2D summaries 
a. For the monthly salary variable in the salary dataset seen in HW2, give a table (or tables) giving 
sample size, and sample mean, median, interquartile range and variance for  

i. Each sex separately (i.e. Male and Female) 
ii. Each rank separately (i.e. Assistant, Associate and Full Professors) 
iii. Each combination of sex and rank 

*Note: to do this in R, first work out how to obtain the relevant subset of the data, then 
calculate the numeric summaries.* 

b. For each part i/ii/iii, provide a graphical summary that illustrates the same comparisons as in 
part a). Using part a) to help you, write a brief description (i.e. full sentences and paragraphs) of 
what each plot shows. 

c. In i) you should see a notable difference in salary between men and women. Using the other 
parts of the question to help you, give one explanation of why that difference may be present. 
Importantly, your explanation should be consistent with the other patterns seen in parts ii) and 
iii). Note: more than one explanation consistent with the data is possible. 

### Q4 – 2D summaries

Do Vittinghoff et al, Problem 2.5. Note that, to avoid transcriptional errors, the data is available on the 
course site. Also, for part (4), you should give at least one advantage and at least one disadvantage. As 
before, if you haven’t already downloaded this book, recall it is available with your UWNetID login on 
Springer Link. 
 
 
### Q5 – 2D summaries 
The course site contains a file of survival data from a long-term randomized trial. The variables are; 
- ***id***: Participant ID 
- ***time***: time (in years) to death, or censoring 
- ***event***: indicator variable for death; 1 indicates death, 0 indicates censoring. You should assume that for censored observations, survival after censoring is similar to survival for those who were not censored. (See slide 2.120 for why this matters) 
- ***treatment***: 1=new drug, 2=control drug 

Plot Kaplan-Meier survival curves that summarize survival in the two treatment groups. Based on what 
you see in the plot, describe how the two treatment groups compare, writing in minimally-technical 
language but capturing the main features of the plot. 

### Q6 – Looking ahead 
In preparation for next week’s lectures (Oct 25th-29th) read slides 2.175 until the end of Chapter 2. 
