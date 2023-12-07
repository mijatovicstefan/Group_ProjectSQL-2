# Mist 4610 Group Project 2

## Team Members:
1. Manuel Sanchez | @manueldsanchez
2. Stefan Mijatovic | @mijatovicstefan
3. Jake Lane | @jakeklane
4. Jackson Lundmark | jlundmark9

## Description of dataset:
The dataset that we have chosen shows the attendance rate by school district in Connecticut for the years 2019-2022. We obtained the dataset from the website https://catalog.data.gov/dataset. As well as the attendance rate per district, there is a breakdown of subcategories such as All Students, Students Experiencing Homelessness, Students With Disabilities, Free/Reduced Price Meal Eligible, English Learners, All other races, Black or African American, Hispanic/Latino of any race, White, Students Without High Needs, and Students With High Needs. Not all of the school districts contain every category as they aren’t applicable to that district. It is taken in a four year span as stated before, but broken up into individual school years such as 2019-2020, 2020-2021, and 2021-2022. In summation, the dataset has various dimensions that allow for a deeper look into the attendance for the school districts in Connecticut.

## Question 1:
Question: For the 2021-2022 school year, model the five school districts with the lowest overall attendance rates. Include only school districts that have “Free Meal Eligible” and “Reduced Price Meal Eligible” programs. Compare these two groups to all students of each of these school districts. 

Importance:

The question is crucial for revealing the impact of Free Meal Eligible and Reduced Price Meal Eligible programs on attendance rates during the 2021-2022 school year. By focusing on the districts with the lowest overall attendance rates, the analysis aims to uncover whether these meal assistance programs are effective in the worst possible attendance situations. The comparison of attendance rates between students benefiting from these programs and the wider student population within the same districts offers a way to see if students of specific programs have a higher attendance rate than all students. This could prove to be an incentive for more schools to implement these programs.

![Screenshot 2023-12-06 193914](https://github.com/ManuelDSanchez/Group_ProjectSQL-2/assets/148248019/b4a50558-5212-45b5-bd91-869166d6d882)

Our graph centers on the attendance rates in Connecticut school districts with the lowest overall attendance rates for the 2021-2022 school year, for all students, “Free Meal Eligible” and “Reduced Price Meal Eligible” programs. Comparing it to All students and Reduced Price Meal Eligible rates, Free Meal Eligible rates were lower for all of these districts. This indicates that in extreme cases of bad attendance, Free Meal Eligible students attend school less than all students and Reduced Price Meal Eligible students. 

## Question 2:
Question: Provide the attendance rate for all students, homeless students, and students with disabilities for the three most populated districts in the 2021-2022 school year. For these three districts, model their attendance rates for all school years since 2019.

Importance:

This question is important because it enables us to compare attendance rates for students with different backgrounds. School officials can answer questions such as, “Do factors such as homelessness affect attendance rates?” They can then decide if it is necessary to implement programs to increase attendance rates for these groups. The second part of the question allows us to see how COVID has affected attendance rates, if they decreased during the pandemic, and if there ever was a “return to normalcy.” We can also use the second part of the question to determine if groups of students such as students with disabilities were disproportionately affected by COVID.

![Screenshot 2023-12-06 193933](https://github.com/ManuelDSanchez/Group_ProjectSQL-2/assets/148248019/f3ac195e-df7e-41f5-a270-fac74f1fa6cd)


The graph shows that homeless students and students with disabilities generally have lower attendance rates compared to the entire student body. We can see that attendance rates began to decrease in 2020, when the COVID pandemic first began. We can also see that the homeless population was affected disproportionately compared to the student body. Student officials can use this information to ensure homeless students have more support during events such as this, as it was found they are affected more. It was also shown that more effective methods might be available for maintaining attendance rates, even through pandemics. 

## Manipulations applied to the data set for analysis

We did not manipulate any of the data, yet for the Lowest Overall Attendence Rate School Districts graph, we only included School Districts that included all three student groups: 
	
  All Students, Free Meal Eligible, Reduced Price Meal Eligible
 
The five school districts with the lowest overall attendance rates initially did not have all these three groups therefore comparison between districts was much harder to comprehend. To counteract this, we only included the five school districts with all three student groups for clarity and consistency.

## Tableau packaged workbook:
The packaged workbook containing the visualizations shown above is attached to this repository.

