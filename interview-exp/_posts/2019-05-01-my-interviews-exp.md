---
layout: post
title: My Interview Experiences at IITs/IISc
comments: true

author: author1
noindex: true
---


### IIT Madras MS Interview Experience - CSE

<style>
body {
        background-image: url("/assets/img/whatsap_background.png");
}

</style>

_1 May 2019_  
_Gate score_ - 762, _AIR_- 388, _Category_ - General  

IIT Madras conducted Written test [link for written test questions](https://chaitrasj.github.io/interview-exp/2019-04-30-my-interviews-exp), 53 candidates were shortlisted for interviews after the test. Interviews began with the document verification. After document verification, candidates were sent for interview. There were 3 panels to take interview and each had around 4–5 profs. Since it was my first interview, I didn’t wanted to go early, and my interview finally began post lunch at around 3.30 pm.
The panel had 4 professors, and 1 person named John was remotely connected through Audio. He too was asking questions.

**Interviewer**: _(Reads out my entire profile)_ You have a gap of 1.5 years why did you take this gap? What have you been doing?  
**Me**: I had worked in an IT Company, Wipro Technologies, as a Software Developer. Also my father was at IIT Bombay in Gate office so I was not allowed to give Gate else he had to change his dept, and since he had only 1 year for retirement I thought of taking work experience during that time.

**Interviewer**: _(They didn’t knew about such rules, and were amazed)_ So you have applied at which other IIT’s?  
**Me**:Except IIT Roorkee, I have applied at all others, because IIT Roorkee accepts only B.Tech is CSE.

**Interviewer** :  _(They didn’t knew this also and were surprised and smiling among themselves that some IIT’s have such rules)_ So you did B.Tech in Extc then why Gate in CSE?  
**Me**: Sir, during my job, my work was on programming and I liked coding and logically solving problems. So I thought I can do well in CSE, hence I took this switch.

**Interviewer** : Good. So you know programming well? You will be able to answer programming questions?  
**Me**: Yes Sir, I did programming in Java.

**Interviewer**: Good. So if you get IIT Bombay or other IIT will you still choose IIT Madras?  
**Me**: _(The panel seemed to be quite chilled and by this time my nervousness had gone)_. Yes I will definitely consider IIT Madras if I am given a chance.

**Interviewer**: Okay let’s start, which subject you have prepared for interview? _(He gave a paper in which all subjects were listed, we had to choose 1 among them to be interviewed on)_  
**Me**: Probability Theory, sir _(I had prepared Probability and Linear Algebra, so i chose Probability theory)_

**Interviewer**: Do you know what is a Bernoulli distribution?  
**Me**: Yes, in this distribution, the random variable takes values 1 with probability p and 0 with probability (1-p)

**Interviewer**: What is a Random variable?  
**Me**: It’s like for each of the probabilistic event, we are mapping the event on a real line with a number, and random variables denotes that number.

**Interviewer**: Is this distribution discrete or continuous?  
**Me**: Discrete as it takes only 2 values

**Interviewer**: What is it’s expected value?  
**Me**: _(I didn’t remember the value, but I knew how to derive it, so I asked if I can use the board)_ derived it.

**Interviewer**: Which continuous Random variable do you know?  
**Me**: Sir, Uniform, Normal distribution

**Interviewer**: Define Normal distribution on board and draw the graph for that  
**Me**: Wrote the definition and drew the PDF, they asked what the axes denotes and I answered

**Interviewer**: What does Y axis denote  
**Me**: It is the probability function, PDF

**Interviewer**: Does the points on Y axis shows probability for a point on X axis?  
**Me**: No Sir, like the area under the PDF function curve gives the probability values for a certain range on X axis.

**Interviewer**: Which other forms are there to represent a Random variable  
**Me**: _(Since PMF and PDF was done, I said CDF)_

**Interviewer**: Draw the CDF for Normal distribution  
**Me**: _(I had not tried this before, but I knew how to do, started with y as 0 when x is -infinity, y as 1 when x is +infinity and when x is 0, y is 1/2, and then fitted as a sigmoid curve and I got it right)_

**Interviewer from remote Audio**: What will be the maximum value on Y axis for normal distribution  
**Me**: Sir, the entire are under curve must be 1, so maybe Y also has max of 1

**Interviewer**: Are you sure?  
**Me**: I was struggling here as I didn’t knew what it could be, and I still felt it’s max 1

**Interviewer**: Do you know what is Variance?  
**Me**: Yes Sir, it denotes the variations in x values wrt the mean value. So we sum up the square of the difference between X and Mean values. Wrote the definition on board.

**Interviewer**:  Why we do we take square?  
**Me**: Sir, if we don’t take square then for symmetric graph, positive values will be cancelled by negatives in addition and we get 0 variance which is not right. So we square them.

**Interviewer**:  Okay, so what happens to Normal distribution if variance approaches to 0  
**Me**: Sir, if we reduce variance, then graph shrinks on X axis, so here the graph will shrink and become parallel to Y axis maybe.

**Interviewer**: Do you want to change your previous answer?  
**Me**: Um, no Sir, I am not getting.
_(The answer was Y will reach a max value when X = Mean, so if we put X= mean in PDF, we get Y, but I realized this later after interview)_

**Interviewer**: So we will ask a programming question now. Do you know about Structures in C? Which book did you refer for C?   
**Me**: Yes Sir, I know Structures, I had read from Let Us C.

**Interviewer**: Write a function which will take input as an array, and n is length of array, and it must return the max value in that array and index at which that max element is present. These 2 elements function must return.  
**Me**: Sir, after 1 pass of Bubble sort we will get max element at first position

**Interviewer**: They were laughing, why Bubble sort entire?  
**Me**: No sir, not entire, just 1 pass. _(I quickly wrote the code and explained the logic before they could trap me somewhere else)_

**Interviewer**:  You have returned the output using an array. Can you do it using Structures?  
**Me**: Yes Sir, then I defined structure and used it to as return type.

**Interviewer**: Can we modify it to return a pointer to structure  
**Me**: Yes Sir, we can but sir we may face Dangling pointer issue if the structure is defined inside function, because it will be a local variable, and we are passing pointer to that. _(He didn’t seem to be convinced with what I said. So he just said me to edit my code and now use Pointer, and I did that.)_

**Interviewer**:  Okay, we are done Chaitra  
**Me**: Thank you Sir, Thank you John

_**Results**_: Got Selected!! I was travelling back after another interview, when I got this news, and yes I was on cloud nine. So just relax and pat yourself that you got a chance to be interviewed in India’s top college, and give your best :)

_**Important links**_ : [Preparing for MS-PhD Interviews](http://www.cse.iitm.ac.in/pages.php?pages=NzM%3D)

_**Suggestions**_:  
Professors at IIT M were very chilled and they do this so that the student is calm. Prepare 1–2 subject thoroughly for all the interview and stick to them. If you want to explore Data science/ AI/ ML/ DL areas during Masters, study Probability and Linear Algebra, and give interviews on them. For probability I feel I could answer ques only because of this [MIT prof’s lectures](https://www.youtube.com/playlist?list=PLUl4u3cNGP60hI9ATjSFgLZpbNJ7myAg6)

Just be confident with what you say, think properly and give answers, if you don’t remember any specific values, go and derive things on board, and they will give you hints too, show them how you are thinking and approaching the problem that’s what they are looking for. And if you want to get interviewed early, get your document verification done soon.


Thanks for reading guys, and if you liked my post, don’t forget to Upvote it and share among your friends for whom this may be helpful. Cheers!
