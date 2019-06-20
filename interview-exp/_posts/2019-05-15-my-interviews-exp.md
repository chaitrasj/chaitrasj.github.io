---
layout: post
title: My Interview Experiences at IITs/IISc
comments: true

author: author1
noindex: true
---


### IIT Delhi MTech Interview Experience - Computer Technology (EET)

_15 May 2019_  
_Gate score_ - 762, _AIR_- 388, _Category_ - General  
There was no written test here. First there was document verification and then they asked us to wait outside a room for interviews. There was 1 professor per candidate to take interview. Since this course is offered by Electrical department, so candidates were from both CS and Electrical/Electronics background. So each prof was asking questions on different subjects, like Sumit sir was asking CS related ques of Algorithms, Prathosh sir was asking on Mathematics, and other profs were there for Embedded system and other electronics subjects. And there were TA's who were very helpful, I had told them that I had prepared Linear ALgebra and Probability, so they gave my form to Prathosh sir.  
_Well this was one of my most memorable interviews :)_

**Interviewer**: From where have you done B.Tech, Veermata Jijabai..  
**Me**: Yes Sir VJTI, Mumbai

**Interviewer**: Mumbai, but your name and surname looks like South Indian names  
**Me**:Yes Sir, actually Im Kannada and I have been born and brought up in Mumbai
_(And to my surprise, he was also a Kannadiga, and he was happy seeing a candidate speaking same native language, he asked how we came to Mumbai, where my father works, and where is our native place in Karnataka. Then he asked if my mother tongue is also Kannada. Then the entire interview went in my mother tongue :)_

**Interviewer** : Why didn't you attend the interviews yesterday?  
**Me**: _(The interviews were scheduled for 2 days, 14th for first pref branch, and 15th for 2nd pref. Since I had applied only for EET, it was my 1st pref so my interview was scheduled on 14th)_
Sir I had another written test at IITB IEOR so I couldn't come yesterday.

**Interviewer** : So if you get selected there are you willing to join here, if we too give the offer?  
**Me**: Yes Sir, I will definitely consider, because interviews are 1 day game and unpredictable, so I had applied at all places.

**Interviewer** : Ok, let's start which subjects have you prepared?  
**Me**: Sir, Maths, Probability and Linear Algebra

**Interviewer**: He smiled and said so you knew I ask questions on Maths that's why you came to me.  
**Me**: Yes Sir

**Interviewer**: He drew a graph on a paper and asked if it was a CDF  
**Me**: Yes Sir, it looks like a  CDF.

**Interviewer**: Look properly  
**Me**: No Sir, CDF graph are always non decreasing, and here the graph is decreasing at this point, so it cannot be CDF.

**Interviewer**: What is the expected value of a Gaussian distribution?  
**Me**: I showed by integration

**Interviewer**: Ok. Let $$X$$ be a Gaussian Random variable, with mean 3 and variance 4. If Y is another Gaussian RV such that $$Y=aX+b$$, what is mean and variance of $$Y$$?   
**Me**: I started it wrong, I thought $$Z=(X-\mu)/\sigma$$, here $$Z$$ has 0 mean and unit variance. So was trying to map this with $$Y$$. But with a hint I understood we have to apply Linearity of expectation, $$E(Y) = E(aX+b) = aE(X)+b$$

**Interviewer**: Then why were you doing it in complicated way?  
**Me**: Yeah, it didn't strike, and I was getting a little bit nervous. _(Actually he was very friendly, and I didn't wanted to let him down, so I had become nervous)_

**Interviewer**: In previous ques, will $$Y$$ be a Normal Random variable?  
**Me**: Yes Sir, $$Y$$ is a linear combination of $$X$$, so it will just be shifted and shrunk because of a and b, rest it will be Gaussian distribution only.

**Interviewer**: If I give another Random variable $$Z$$ which is a Quadratic equation of $$X$$, will it still be Gaussian?  
**Me**: I wrote $$Z=aX^2+bX+c$$, um no Sir, $$Z$$ is a non linear function of $$X$$, so it won't be Gaussian.

**Interviewer**: What will happen because of non linearity?  
**Me**: I didn't knew this reason, I said sir it's shape will change

**Interviewer**: Ok, anyhow yes it won't be Gaussian. Do you know what is Conditional Probability?  
**Me**: Yes Sir, and then I explained on paper taking $$X$$ and $$Y$$ as 2 RV's.

**Interviewer**: What is $$E(X|Y)$$  
**Me**: I wrote the formula for Conditional expectation

**Interviewer**: This will be a function of what?  
**Me**: I didn't get this

**Interviewer**: Generally for a RV $$X$$ what is the expected value function of?  
**Me**: It's a constant sir

**Interviewer**: So here what it will be a function of?  
**Me**: Yes sir, it will be a function of $$Y$$, based on which $$Y$$ has occured it's value changes

**Interviewer**: What will be Expected value of this function of $$Y$$? $$E(E(X|Y))$$?  
**Me**: _(I had a little bit idea about this as on 14th, my friend was also asked the same question)_ Sir it will be $$E(X)$$

**Interviewer**:  Are you sure? Can you prove it?  
**Me**: Maybe Sir, I will try.
_(He helped a lot during the proof, and it involved marginal pdf, joint pdf knowledge everything, and yes it's true, $$E(E(X|Y))=E(X)$$, I have added below how I did it )_

**Interviewer**:  Good. Should I ask about Linear Algebra  
**Me**: Yes Sir, you can ask.

**Interviewer**: He gave a matrix, and asked to find the rank, without doing any calculation  
**Me**: It was easy I explained it.

_(While I was solving, I heard his conversation with Sumit sir, he was like if the cndidate is really willing to join and work, then we should take. So here it was like that, they were looking towards the attitude of the candidate and willingness to work)_

**Interviewer**: If we offer you a seat, will you join?   
**Me**: Yes Sir, I will join

_(Then after the interview, outside the classroom we spoke for another 5 mins, I told that I'm interested to work in applied ML areas, he said he teaches Deep learning and EET is a very good branch, many people do research work here, and if a student wants to take a job, they get get good package, then he asked where I'm staying, and some more talk about IIT D hostel campus, and finally he said me see you in class :))_

_**Results**_: Got Selected, and I was expecting that.

_**Suggestions**_:  
The TA's are very helpful, and it's not the case in all IIT's, so make use of the opportunity. Be clear on which areas you want to be questioned and choose the panel accordingly.
Professors will give lot of hints, keep trying, don't give up on any question easily.
And usually IITD interview clashes with other interviews, so like I did, try to adjust and somehow given an attempt for the interview.

![Dark Mode](/assets/img/IMG-20190518-WA0004.jpg){:data-width="1440" data-height="836"}
*Proof for E(E(X|Y))=E(X)*
{:.figure}

Thank you for reading, and if you liked my post, don’t forget to share among your friends for whom this might be helpful. Cheers!
