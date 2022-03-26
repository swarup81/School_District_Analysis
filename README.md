# School_District_Analysis
 performing school district analysis with python and pandas using jupyter notebook.
# Overview of the school district analysis:
The project analyses school and student data files to evaluate the overall performance of schools.
## purpose:
This project aims to analyze Thoma's high school math and reading grades as there is evidence of academic dishonesty. Replacing math and reading scores with NaNs will do a comparative study between initial analysis and updated analysis to see how it will impact the overall performance.
# Results:
How is the district summary affected?
*  A comparative study between initial and updated analysis shows that the average reading score remained the same. Still, the average math score, percentage of passing math, passing reading, and overall passing percentage decreased by  0.1%, 0.2%, 0.3%,  and 0.1%, respectively. 

      initial analysis
<img width="761" alt="Screen Shot 2022-03-25 at 1 35 09 PM" src="https://user-images.githubusercontent.com/100738688/160219156-8a93e866-93ea-41ce-a704-6bf73e6b2b0b.png">

updated analysis
<img width="1132" alt="Screen Shot 2022-03-25 at 1 27 10 PM" src="https://user-images.githubusercontent.com/100738688/160219175-0f57bb11-03ea-458e-98e6-92f8010c57bf.png">

         
How is the school summary affected?
* Initial analysis shows that the updated school summary analysis showed that Thomas high school students' math and reading passing percentages were 93.27% and 97.30%, which dropped to 66.91% and 69.66%, respectively.There was a slight difference in the average math and reading scores.

initial analysis
<img width="1297" alt="Screen Shot 2022-03-25 at 1 57 54 PM" src="https://user-images.githubusercontent.com/100738688/160219380-f51e7cc0-6d60-4773-98fc-5d0f61c63e3a.png">

updated analysis
<img width="1294" alt="Screen Shot 2022-03-25 at 2 05 28 PM" src="https://user-images.githubusercontent.com/100738688/160219390-49f9a7ec-db63-4967-a080-117bdd5a8f1f.png">


How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools?
* By replacing  9th-graders math and reading scores, Thomas high school performance ranking dropped from the 2nd highest overall passing percentage, 90.94%, to the 8th lowest overall passing percentage, 65.07%.

How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade
* After replacing 9th graders' scores, the data has been excluded from that column for that specific school and grade, and the data becomes NaN or null.

<img width="498" alt="Screen Shot 2022-03-25 at 3 42 10 PM" src="https://user-images.githubusercontent.com/100738688/160219496-33c5cf44-e65c-4138-9175-3e550848cde9.png">


Scores by school spending
* School spending does not change as we have nullified 9th graders from the statistics.

Scores by school size
* The data has not altered; it remains the same.

Scores by school type
* Scores by school type data do not change; it remains the same.

initial analysis
<img width="735" alt="Screen Shot 2022-03-25 at 9 45 23 PM" src="https://user-images.githubusercontent.com/100738688/160219967-bbb1087c-e28c-4d93-aa8a-3aa084fe3f52.png">

updated analysis
<img width="735" alt="Screen Shot 2022-03-25 at 9 43 05 PM" src="https://user-images.githubusercontent.com/100738688/160220003-c494e1b3-f170-4bea-88fe-8adebb5eb0a7.png">




# summary:

The major four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs are:

The average reading score remains the same.

The average math score has decreased by 0.1%.

The passing percentage of math and reading has decreased by 0.2% and 0.3%, respectively.

The overall passing percentage has decreased by 0.1%.






