# School_District_Analysis_v2

## Overview

The purpose of this project is to provide a high-level overview of the school district's key academic metrics. This includes Top 5 and bottom 5 performing schools, based on the overall passing rate, the average math and reading scores received by students in each grade level at each school, as well as school performance based on budget per student, size, and school type.

After discovering evidence of academic dishonesty at one of the schools, this current project will be used to understand what changes will be made to the original analysis when taking away the inconclusive data.

## Results

### District Summary
*  Math scores, and all of the passing percentages dropped. 
*  Average reading score, however, remained the same.

Original

![image](https://user-images.githubusercontent.com/102189324/167324992-84e3b885-b156-42e7-bdd3-f88afa0b43b9.png)

Updated

![image](https://user-images.githubusercontent.com/102189324/167325032-a6286480-35d4-4959-9584-d8210f667b81.png)

### School Summary

* Only Thomas High School's scores and percentages were altered. 
* Only altered by a few hundreths of a point or percentage.

### Thomas High School

* The school still performed very well despite losing some high scores from the 9th grade class. t
* They now fell behind a few schools in the percentage of students who passed reading. 
* They were still the 2nd highest school in terms of percentage of students who passed both math and reading.

Original

![image](https://user-images.githubusercontent.com/102189324/167325973-35b17522-5cb5-41fc-ba11-53f551425827.png)

Updated

![image](https://user-images.githubusercontent.com/102189324/167325999-f1b25d8a-f148-4f68-a5dc-bef4969aa5e9.png)

### Scores by Grade/Spending/Size/Type

* Scores by grade data frames have a significant difference than the original analysis. 
* Thomas High School's 9th grade scores are completely wiped out due to the academic dishonesty. 
* By replacing those scores with "NaN", the dataframes are now missing those data points.

![image](https://user-images.githubusercontent.com/102189324/167324112-e43f836b-cbe9-4b30-a781-aa9922a1f4c9.png)

Afer formatting some of the different data frames that showcase the scores by spending, size, and school type there isn't much difference in the data. As evidence below.

This is the orginial formatted analysis based on school type.
![image](https://user-images.githubusercontent.com/102189324/167324234-61d12bf7-89b0-45e3-b47d-11a04bf17986.png)

This is our updated formatted analysis based on school type.
![image](https://user-images.githubusercontent.com/102189324/167324304-e7aaf826-5fc3-4f34-9345-c5a77c1d3ba2.png)

However, when we look at the unformatted analyses, we can see a slight difference with data points.

Original

![image](https://user-images.githubusercontent.com/102189324/167324417-220f0ddf-dfa4-49c9-967f-f0ee0dfbb5a4.png)

Updated

![image](https://user-images.githubusercontent.com/102189324/167324453-ec75c350-ad1e-4297-886f-6dc60c5a2d17.png)

* We can see that the Charter Schools data points all changed within a very small margin. 
* This margin was typically within 1/100th of a point or percentage point of the original. 
* We see this as well with the average scores and percentile of passing for medium sized schools 
* Also see this as well with schools with a spending range of $631 and $645.

## Summary

There were a few changes to the school district analysis. After the changes were made to the grades from Thomas High School's 9th grade class, we can see that the rankings of the schools was impacted slightly in the percentage of students who passed math as well as the percentage of those who passed reading.

We can also see that the data for schools who spend between $631 and $645 changed as well. Average scores as well as percentage of those who passed was changed.

It can also be noticed that the data for Medium sized schools was altered as well. Scores and percentages were different after the changes.

Finally, the data for Charter schools was different as well. After the changes we can see minimal changes to the data but the numbers are slightly different than before.
