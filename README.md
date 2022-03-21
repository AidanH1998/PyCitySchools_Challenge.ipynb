# PyCitySchools_Challenge.ipynb

## Overview of School District ##

The main goal of the analyst is to see the dependent variables that lead to the success of schools and their student good scores. The variables will be the number of Students in the school, the amount of money the school recieves and the difference of Charter and District. For this Analyst we are focused on Thomas High School and following their passing rate and what is dependable on it.

  * The district summary.
  * The school summary.
  * The top 5 and bottom 5 schools based on success rate
  * The average math score for each grade in each school.
  * The average reading score for each grade in each school.
  * The scores by school spending per student.
  * The amount of the school size.
  * The type of school it is.



## Result ##

### Before Removing Freshmen ###

Thomas Hiogh School is ranking the second in the high schools average passing rates. That is including all the grade from 9th to 12th.

![Before removing 9th grade](https://user-images.githubusercontent.com/100543143/159194322-6c11d96c-ec72-41b4-8927-8a3828b7a7ce.png)

Thomas High School is considered second best.

![Top 5 schools Based on passes](https://user-images.githubusercontent.com/100543143/159194461-272888cc-5119-4c91-a7a9-278f06d42d3d.png)

Thomas high School is also spending more for their student than the first highest school. So considering that Thomas High School is the second best school, and one of the schools with the highest money spent per student, the money should be the successs of school.

![Overall Summary of Each School](https://user-images.githubusercontent.com/100543143/159194674-e8277875-c2e4-444b-bf48-05531eb1b629.png)



### Removing Freshmen ###

What happens when we remove the freshmen, so taking out the students that are coming into the school and in the 9th grade. 

![Student Data 9th Grade Math and Reading NaN](https://user-images.githubusercontent.com/100543143/159194912-402f6765-77d6-4dcb-8de0-d8da3a201073.png)

So how do we do that, we just nullify the 9th graders scores, so that they aren't affecting the overall score for Math and Reading.

![Schools Overall Math Scores Based on Grade Remove 9th](https://user-images.githubusercontent.com/100543143/159195083-fabeaa18-32c8-45e9-8236-967c7aba8819.png)

![Schools Overall Reading Scores Based on Grade Remove 9th](https://user-images.githubusercontent.com/100543143/159195084-a61b853f-9038-47ae-8867-9c8ef2e6ac29.png)

What we should expect is Thomas High School to still maintain the top spots for all of the high schools, but we found out that the score for Thomas High School Dropped significantly.

![School Summary After removing Freshmen](https://user-images.githubusercontent.com/100543143/159195259-8e1e3696-7d62-4600-830a-0bf2384df006.png)

Thomas High School has dropped to 8th place in Overall Passings. The School was second with their 9th graders included in the Overall Score, but the other grades couldn't catch up with their classmates. This shows that Thomas High School is not as successful as they claim to be because their up grades are not passing as well as the lower students.



### Money Distribution ###

The money distribution changed based on removing 9th grades from Thomas High School's, the distribution used to be from, Less than $584 to $644 was the range of school that used the money and that resulted in passing grade and anything over that results in lower overall scores. However, after removing 9th grades in Thomas High Schools Overall Score, the spending range per student successs rate reducted to Less than $584 to $629, that $15 drop shows that there could be a difference between spending $629 and $630.

![Range of Money spend based on Scores Without 9th](https://user-images.githubusercontent.com/100543143/159196063-b7f5bb75-7fde-4ed3-a3c4-d33ea7894a1a.png)



### Size of School ###

The Size of the does matter because out of the 8 school that are considered large schools, with a student population of 2000-5000, 1 of the schools are only passing will a difference of about 30%-40%. 

![Size of Schools](https://user-images.githubusercontent.com/100543143/159196407-8b4d12c5-f36d-4912-8b90-050974c7b8f6.png)

With the connection of school size and money distribution the schools that are failing with a large population are also the ones that are paying about the middle and higher dollars per student. The large high school that has a 90% Overall Score only spend about the minimum based on the chart.

To extend the point smaller schools have a higer success rate with schools having less than 1000 students because 2/2 small schools Overall Passing score was above 89%.



## Summary ##

* Thomas High School dropped their Overall Passing Score because the freshmen were bring up the score for the whole school.
* The distribution of money on students is much better when schools spend a little less compare to spending $1 to $45 more.
* The Size of the school matters because with smaller school they are going to have better teacher ratio compared to a larger school.
* the correlation between spending money on students and school size is proportional because having a high rate of spending per student and having a large school means that student's Overall Score is around 60%. When the school is Small the school is most likely to spend, in the range of, less for their student, but This results in Higher Overall Scores.
