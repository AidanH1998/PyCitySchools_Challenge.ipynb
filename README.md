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

So how do we do that we just nullify the 9th graders scores, so that they aren't affecting the overall score for Math and Reading.

![Schools Overall Math Scores Based on Grade Remove 9th](https://user-images.githubusercontent.com/100543143/159195083-fabeaa18-32c8-45e9-8236-967c7aba8819.png)

![Schools Overall Reading Scores Based on Grade Remove 9th](https://user-images.githubusercontent.com/100543143/159195084-a61b853f-9038-47ae-8867-9c8ef2e6ac29.png)



What we should expect is Thomas High School to still maintain the top spots for all of the high schools
