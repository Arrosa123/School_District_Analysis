# School_District_Analysis
## Project Overview
Maria is the chief data scientist for a city school district. The school board believes that there is evidence of academic dishonesty withing their local school district. They believe that some of the test scores have been altered. The school board wants to uphold state-testing standards and have asked for help. Maria has asked me for help and given me the following tasks.
1. Replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact.
2. Recreate the district and school summary DataFrames.
3. Recalculate the school performance based on the spending per student.
4. Recalculate the school performance based on the size of the school.
5. Recalculate the school performance based on the type of school.
6. Write up a report to describe how these changes affected the overall analysis
## Results
### How is the district summary affected?
The average math score decreased by 0.1 points while the average reading score stayed the same.
The percentage of students passing math decreased by 1% as did the percentage of students passing reading. The overall passing percentage also decreased by 1%

Figure 1: District summary before data cleanup
![District summary before data cleanup](https://user-images.githubusercontent.com/96403349/151609516-fdc747cc-b075-45ac-9567-8784c75bb100.png)
Figure 2: District summary after data cleanup
![District summary after data cleanup](https://user-images.githubusercontent.com/96403349/151609594-94583a02-658d-447f-9dd9-306fa302f601.png)
### How is the school summary affected?
The only change in data is with Thomas High School. The overall math and reading passing numbers decreased.

Figure 3: School summary before clean data
![School summary before clean data](https://user-images.githubusercontent.com/96403349/151610467-8eee0b16-ef1c-45d7-86fa-15317f676ad1.png)

 Figure 4: School summary after clean data
![School summary after clean data](https://user-images.githubusercontent.com/96403349/151610543-d44a8aa6-e89d-4cde-9c5b-67749b1d799f.png)
### How does removing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other schools?
Thomas High School moved from 2nd place overall with a passing % of ~92% down to last place with a passing % of ~68%.
## How does removing the ninth grade scores affect the following?
- Math and Reading Scores by Grade
Thomas High School's 9th grade class has no math or reading score data to count. Everything else was unaffected.
 
 Figure 5: Math scores by grade

![Math scores](https://user-images.githubusercontent.com/96403349/151611627-e9425a03-bc88-413f-9b8c-0c321420fc36.png)
 
 Figure 6: Redaing scores by grade

![Reading Scores](https://user-images.githubusercontent.com/96403349/151611686-8696310f-4b3c-40d0-bb06-cfe8e73e1cd6.png)
- Scores by School Spending  
The $630-644 bin saw a decrease in the passing percentages since Thomas High School was in that spending range.The average math and reading scores for that range remained the same.

Figure 7: Scores by school spending before data cleanup

![Scores by school spending before data cleanup](https://user-images.githubusercontent.com/96403349/151621357-4ffa97c5-3588-494e-8fa8-688181eccdbe.png)

Figure 8: Scores by school spending after data cleanup

![Scores by school spending after data cleanup](https://user-images.githubusercontent.com/96403349/151621434-33b503ed-c20b-4086-a0ef-ccd6234d1a90.png)

- Scores by School Size
The Medium (1000-2000) bin saw a decrease in the passing percentages since Thomas High School was in that school size. The average math and reading scores for that range remained the same.

Figure 9: Scores by school size before data cleanup

![Scores by school size before data cleanup](https://user-images.githubusercontent.com/96403349/151621918-da7389cf-fc4f-4ab2-9d91-6c628949ae39.png)

Figure 10: Scores by school size after claen data 

![Scores by school size after data cleanup](https://user-images.githubusercontent.com/96403349/151622016-0081bacf-4ad7-4528-bad1-5329a8468f2f.png)

- Scores by School Type
The Charter schools saw a decrease in the passing percentages since Thomas High School was in that school type. Though, interestingly the average math and reading scores for that range remained the same.

Figure 11: Scores by school type before clean data

![Scores by school type before clean data](https://user-images.githubusercontent.com/96403349/151622445-962f5e65-bdb2-444d-a8be-5b7f056b2943.png)

Figure 12: Scores by school type after clean data

![Scores by school type after clean data](https://user-images.githubusercontent.com/96403349/151622544-6fca25f5-a3df-43cb-ace5-70fd1d0a9236.png)

## Summary
Removing 9th grade math and reading scores from Thomas High School negatively impacted its ranking among other schools and also change to NaN's had an insigificant impact to the overall school analysis. It will be good if the school board continue with the budgeting process based on the updated data.
