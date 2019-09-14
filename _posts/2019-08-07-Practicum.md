DSSA 5302 Data Practicum:  
=====
This is the final project for my Master's degree.  

Here is the github repo with code: [github.com/chillington/DSSA_Practicum](https://github.com/chillington/DSSA_Practicum)

Here is the summary:

Educators at colleges and universities have a number of reasons to be concerned with student retention and graduation rates.  It is important for public perception of the institution, as well as for the student on an individual level.  With all of the data available to education professional, there should be more technology-assisted tools available to identify students who are at-risk of ending their college careers prematurely.

Previous research has found success in using artificial neural networks to predict different types of academic performance, including graduation and retention, with some success.  Many of those studies, however, focused on pre-admission background data as input variables.  Here, I primarily used student performance – grades earned – in their first year at Stockton University.  My goal was to create a neural network model that would identify students who would leave the university before completing their degree.

I identified students who were invited to attend new student orientation during the summer of 2015 as my target sample.  I had their names and ID numbers available (one of my job functions is to assist students with registration at orientation), and was able to obtain course records, transfer credits, and different status indicators from the Degree Works curriculum planning database, with some help from Stockton Information Technology Services.  After much cleaning and rearranging of the data in R, I had a complete sample of 1,295 students.

My input variables were highest and lowest grades earned in each of the students’ first two semesters – fall 2015 and spring 2016 (four variables), as well as total number of courses withdrawn in the first year, and the number of transfer credits, for six variables in all.  My output variables were three binary classifications – whether or not a student: graduated on time in four years, was still continuing at Stockton, or had left the university before completing their degree.

Unfortunately, my model was mostly unsuccessful in identifying the students who “left early” in a test data set from my sample, though it did reasonable well at predicting if they would graduate.  If nothing else, this study provides a possible framework and starting point for future research in this area.

The full report will be made available soon.

Data may be available upon request.
