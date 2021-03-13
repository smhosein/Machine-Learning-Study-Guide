# Machine-Learning-Study-Guide

### General Interview Process:

1. Phone Interview — This usually would take either two forms: a complete software engineering interview or a mix of software engineering and a few ML questions
2. Onsite Interview:
* Software Engineering and/or ML Coding Interview
* ML Theory Questions — I have seen this interview split into two parts: ML theory and ML coding
* ML System Design
* Company Specific — I put this here because most companies tend to have one of the above interviews repeated or something specific based on the job (e.g. Facebook has a System Design interview, note this is not an ML System Design interview)
* Hiring Manager (behavioral) — I failed an interview for a company by being unprepared for this round. I aced the technical interviews and was confident I would get an offer. However, when I did not, the feedback was that I did not do well on the behavioral interview. After that feedback, I spent a lot of time preparing for these questions.

### Software Engineering and/or ML Coding Interview
*For the SWE coding, the plan would be*:
1. [Leetcode](https://leetcode.com/): This should not be a strange inclusion as it is ubiquitous for SWE interviews and for good reason! I would recommend following the below steps in order as they build on each other:
* https://leetcode.com/explore/learn/ — this is good to refresh your memory on data structures and algorithms
* https://seanprashad.com/leetcode-patterns/ — this is a great resource containing many patterns that you would face in a coding interview
* https://leetcode.com/problemset/top-interview-questions/ — you should be aware of the popular questions that tend to come up in an interview
N.B: While answering these coding questions, you should create a spreadsheet of difficult questions and the algorithm (not the code) that is used. Then go back to the spreadsheet later on and try to solve the questions a second time. This will help you understand your weaknesses. Once you complete the three links above, you should answer at least one leetcode question every day (preferably medium and sometimes hard). When it is closer to your interview date, I recommend buying leetcode premium and doing the company questions.
2. [Elements of Programming Interviews](https://elementsofprogramminginterviews.com/sample/): Many people recommend [Cracking the Coding Interview](https://www.crackingthecodinginterview.com/) but, I would recommend you buy [Elements of Programming Interviews (EPI)](https://elementsofprogramminginterviews.com/sample/). I make this recommendation because you can choose between Java, C++ or Python as your programming language and can use their coding [judge system](https://github.com/adnanaziz/EPIJudge) to test your code. This book was hard for me to get through at first and I could not solve most of the questions. However, as I continued, I started writing python code efficiently and changed how I think about solving problems.
*For ML Coding, the plan would be*:
1. [ML Coding Algorithms](https://www.mle-interviews.com/ml-coding): I would recommend this site because getting proper ML coding resources became an issue for me when studying for interviews. Most websites are lacking in two ways: the code is far too complex than what is required in an interview or does not contain time/space complexity. This website solves both problems.
2. [Github ML Algorithms](https://github.com/rushter/MLAlgorithms): This resource contains almost all of the possible ML algorithms you will probably encounter in an interview. The code is written in a very modular way, making it is easy to understand the code.
3. [Machine Learning Mastery](https://machinelearningmastery.com/category/algorithms-from-scratch/): A popular website containing the most popular ML algorithms that the author builds from scratch. It is optional because there are parts of the code that may not be relevant in an interview (e.g. data ingestion). If you have extra time, you can browse the code.


### ML Theory
*Books*:
1. [Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/): This book is an excellent book that covers most of the topics above (other than some specialized topics). It is an easy read with engaging diagrams and code to help you understand each topic.
2. [The 100 Page ML Book](http://themlbook.com/): This is another great book that covers most of the topics above. It goes into more mathematical detail than the Hands-On ML book but, the author does an excellent job of being concise while still being an easy read. Also, it is free :)

*(OR) Video Courses*:
1. [Udacity’s Machine Learning Course](https://www.udacity.com/course/machine-learning--ud262): An easy but comprehensive course on ML. The instructors give you an overview of most of all the foundational topics and some of the misc topics. It is an excellent refresher if you are looking for somewhere to start.
2. [Coursera’s Machine Learning Course](https://www.coursera.org/learn/machine-learning): This has to be the most popular course on the internet for machine learning and for good reason! It goes into more of the mathematical foundations of many of the traditional ML algorithms while still being accessible to anyone. Note, if you want a summary of the course rather than watching all the videos you can check out [these notes](http://www.holehouse.org/mlclass/).
3. [Coursera’s Deep Learning Specialization](https://www.coursera.org/specializations/deep-learning): These courses cover most of the neural network architectures above and go into sufficient detail for an interview. I highly recommend this as it has almost all the information you need for succeeding in questions on Neural Networks and deep learning. Again, if you would like a summary of the course you can read [these notes](https://github.com/mbadry1/DeepLearning.ai-Summary).

Once you are finished with the above resources, you probably need questions to practice. Here is a collection of question and answer docs:
https://github.com/andrewekhalel/MLQuestions
https://github.com/IndyNYU/Machine-Learning-Interview/blob/master/Algorithms %26 Theory
https://www.mle-interviews.com/ml-questions


### ML System Design
An ML system design question is (almost) a given for any MLE onsite interview. Since there are no courses or books on this as of this writing, we should use blogs:
1. [ML System Design Template For MLE Interviews](https://www.mle-interviews.com/ml-design-template): A general framework that can be used for most ML System Design interview questions. There are specific questions and answers that most companies will ask.
2. [Architecting a Machine Learning Pipeline](https://towardsdatascience.com/architecting-a-machine-learning-pipeline-a847f094d1c7): A blog for understanding the engineering side for ML System Design
3. [Machine Learning System Design Draft PDF](https://github.com/chiphuyen/machine-learning-systems-design): A good overview of themes that you should include in your response to ML System Design
4. [Machine Learning System Design Blog](https://becominghuman.ai/machine-learning-system-design-f2f4018f2f8): A great resource of links to many company blogs which explain how they build their ML systems.

If you would like to get ML interview questions, ML code and ML system design to ace your ML interview, please visit [mle-interviews.com](mle-interviews.com) 
