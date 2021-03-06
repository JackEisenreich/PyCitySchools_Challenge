# PyCitySchools_Challenge
**Overview of the school district analysis:**

The purpose of this analysis was first to change all of Thomas High School’s 9th grade scores to NAs, and then rerunning the analysis that we ran in the module for Thomas High School with just grades 10-12 to see if this altered the overall analysis. This was done because the 9th grade at Thomas High School was suspected of dishonesty.

**Results:**
* The new fixed average math, reading, and overall scores by district all went down slightly
![New District Analysis](https://user-images.githubusercontent.com/95661553/150731713-124c4e7a-2f43-41cf-891e-57b55fe9c233.png)
![Old District Analysis](https://user-images.githubusercontent.com/95661553/150731725-001dded4-5e03-4953-b253-81a9c073e643.png)

* The new school summary for math, reading, and overall scores all went down as well
* By replacing the 9th grade scores with NaNs, Thomas High School’s scores for reading, math, and overall all went down, but the school remained one of the top schools in terms of overall grades.
* Replacing the ninth grade scores did the following:
  * The math and reading scores by grade for the ninth grade at Thomas High School registered as “NaN” because the by grade analysis was done on a school basis. However, if this was done on a total grade basis with all schools, the overall % passing would decrease
  * The % Passing in the $630-644 range slightly decreased but remained very similar
  * By school size only the medium was affected. The average math actually increased, the average reading decrease and the overall % passing decreased as well. Again the scores remained largely similar though
  * By type, the district schools were unaffected, but in the charter schools, the overall passing % decreased slightly

**Summary**
In all, by changing the ninth grade grades at Thomas High School, the overall passing % for the ninth grade in the district decreased, percent passing in the $630-644 school spending bin decreased, the medium school size in the district percent passing decreased, and the charter school percent passing decreased. 


