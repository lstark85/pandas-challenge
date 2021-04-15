# pandas-challenge
PyCitySchools

Well done! Having spent years analyzing financial records for big banks, you've finally scratched your idealistic itch and joined the education sector. In your latest role, you've become the Chief Data Scientist for your city's school district. In this capacity, you'll be helping the  school board and mayor make strategic decisions regarding future school budgets and priorities.

As a first task, you've been asked to analyze the district-wide standardized test results. You'll be given access to every student's math and reading scores, as well as various information on the schools they attend. Your responsibility is to aggregate the data to and showcase obvious trends in school performance.

Your final report should include each of the following:

### District Summary

* Create a high level snapshot (in table form) of the district's key metrics, including:
  * Total Schools
  * Total Students
  * Total Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math (The percentage of students that passed math.)
  * % Passing Reading (The percentage of students that passed reading.)
  * % Overall Passing (The percentage of students that passed math **and** reading.)
  
  District Summary
  Total Schools	Total Students	Total Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
0	15	39,170	$24,649,428.00	78.985	81.878	74.980853	85.805463	65.172326

### School Summary

* Create an overview table that summarizes key metrics about each school, including:
  * School Name
  * School Type
  * Total Students
  * Total School Budget
  * Per Student Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math (The percentage of students that passed math.)
  * % Passing Reading (The percentage of students that passed reading.)
  * % Overall Passing (The percentage of students that passed math **and** reading.)
  
  School Summary
  
School Type	Total Students	Total School Budget	Per Student Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Over Passing
Bailey High School	District	4,976	$3,124,928.00	$628.00	77.048432	81.033963	66.680064	81.933280	54.642283
Cabrera High School	Charter	1,858	$1,081,356.00	$582.00	83.061895	83.975780	94.133477	97.039828	91.334769
Figueroa High School	District	2,949	$1,884,411.00	$639.00	76.711767	81.158020	65.988471	80.739234	53.204476
Ford High School	District	2,739	$1,763,916.00	$644.00	77.102592	80.746258	68.309602	79.299014	54.289887
Griffin High School	Charter	1,468	$917,500.00	$625.00	83.351499	83.816757	93.392371	97.138965	90.599455
Hernandez High School	District	4,635	$3,022,020.00	$652.00	77.289752	80.934412	66.752967	80.862999	53.527508
Holden High School	Charter	427	$248,087.00	$581.00	83.803279	83.814988	92.505855	96.252927	89.227166
Huang High School	District	2,917	$1,910,635.00	$655.00	76.629414	81.182722	65.683922	81.316421	53.513884
Johnson High School	District	4,761	$3,094,650.00	$650.00	77.072464	80.966394	66.057551	81.222432	53.539172
Pena High School	Charter	962	$585,858.00	$609.00	83.839917	84.044699	94.594595	95.945946	90.540541
Rodriguez High School	District	3,999	$2,547,363.00	$637.00	76.842711	80.744686	66.366592	80.220055	52.988247
Shelton High School	Charter	1,761	$1,056,600.00	$600.00	83.359455	83.725724	93.867121	95.854628	89.892107
Thomas High School	Charter	1,635	$1,043,130.00	$638.00	83.418349	83.848930	93.272171	97.308869	90.948012
Wilson High School	Charter	2,283	$1,319,574.00	$578.00	83.274201	83.989488	93.867718	96.539641	90.582567
Wright High School	Charter	1,800	$1,049,400.00	$583.00	83.682222	83.955000	93.333333	96.611111	90.333333

### Top Performing Schools (By % Overall Passing)

* Create a table that highlights the top 5 performing schools based on % Overall Passing. Include:
  * School Name
  * School Type
  * Total Students
  * Total School Budget
  * Per Student Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math (The percentage of students that passed math.)
  * % Passing Reading (The percentage of students that passed reading.)
  * % Overall Passing (The percentage of students that passed math **and** reading.)

Top Performing Schools
	School Type	Total Students	Total School Budget	Per Student Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Over Passing
Cabrera High School	Charter	1,858	$1,081,356.00	$582.00	83.061895	83.975780	94.133477	97.039828	91.334769
Thomas High School	Charter	1,635	$1,043,130.00	$638.00	83.418349	83.848930	93.272171	97.308869	90.948012
Griffin High School	Charter	1,468	$917,500.00	$625.00	83.351499	83.816757	93.392371	97.138965	90.599455
Wilson High School	Charter	2,283	$1,319,574.00	$578.00	83.274201	83.989488	93.867718	96.539641	90.582567
Pena High School	Charter	962	$585,858.00	$609.00	83.839917	84.044699	94.594595	95.945946	90.540541

### Bottom Performing Schools (By % Overall Passing)

* Create a table that highlights the bottom 5 performing schools based on % Overall Passing. Include all of the same metrics as above.

Bottom Performing Schools
	School Type	Total Students	Total School Budget	Per Student Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Over Passing
Rodriguez High School	District	3,999	$2,547,363.00	$637.00	76.842711	80.744686	66.366592	80.220055	52.988247
Figueroa High School	District	2,949	$1,884,411.00	$639.00	76.711767	81.158020	65.988471	80.739234	53.204476
Huang High School	District	2,917	$1,910,635.00	$655.00	76.629414	81.182722	65.683922	81.316421	53.513884
Hernandez High School	District	4,635	$3,022,020.00	$652.00	77.289752	80.934412	66.752967	80.862999	53.527508
Johnson High School	District	4,761	$3,094,650.00	$650.00	77.072464	80.966394	66.057551	81.222432	53.539172

### Math Scores by Grade\*\*

* Create a table that lists the average Math Score for students of each grade level (9th, 10th, 11th, 12th) at each school.

Math Scores by Grade

9th	10th	11th	12th
Bailey High School	77.084	76.997	77.516	76.492
Cabrera High School	83.095	83.155	82.766	83.277
Figueroa High School	76.403	76.540	76.884	77.151
Ford High School	77.361	77.672	76.918	76.180
Griffin High School	82.044	84.229	83.842	83.356
Hernandez High School	77.438	77.337	77.136	77.187
Holden High School	83.787	83.430	85.000	82.855
Huang High School	77.027	75.909	76.447	77.226
Johnson High School	77.188	76.691	77.492	76.863
Pena High School	83.625	83.372	84.328	84.122
Rodriguez High School	76.860	76.612	76.396	77.691
Shelton High School	83.421	82.917	83.383	83.779
Thomas High School	83.590	83.088	83.499	83.497
Wilson High School	83.086	83.724	83.195	83.036
Wright High School	83.265	84.010	83.837	83.645

### Reading Scores by Grade

* Create a table that lists the average Reading Score for students of each grade level (9th, 10th, 11th, 12th) at each school.

Reading Scores by Grade
	9th	10th	11th	12th
Bailey High School	81.303	80.907	80.946	80.912
Cabrera High School	83.676	84.253	83.788	84.288
Figueroa High School	81.199	81.409	80.640	81.385
Ford High School	80.633	81.263	80.404	80.662
Griffin High School	83.369	83.707	84.288	84.014
Hernandez High School	80.867	80.660	81.396	80.857
Holden High School	83.677	83.325	83.816	84.699
Huang High School	81.290	81.512	81.417	80.306
Johnson High School	81.261	80.773	80.616	81.228
Pena High School	83.807	83.612	84.336	84.591
Rodriguez High School	80.993	80.630	80.865	80.376
Shelton High School	84.123	83.442	84.374	82.782
Thomas High School	83.729	84.254	83.586	83.831
Wilson High School	83.940	84.021	83.765	84.318
Wright High School	83.833	83.813	84.156	84.073

### Scores by School Spending

* Create a table that breaks down school performances based on average Spending Ranges (Per Student). Use 4 reasonable bins to group school spending. Include in the table each of the following:
  * Average Math Score
  * Average Reading Score
  * % Passing Math (The percentage of students that passed math.)
  * % Passing Reading (The percentage of students that passed reading.)
  * % Overall Passing (The percentage of students that passed math **and** reading.)

Scores by School Spending
	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Over Passing
Spending Ranges					
<$585	$83.46	$83.93	83.455399	96.610877	90.369459
$585-615	$83.60	$83.89	83.599686	95.900287	90.216324
$615-645	$79.08	$81.89	79.079225	86.106569	66.112060
$645-675	$77.00	$81.03	76.997210	81.133951	53.526855

### Scores by School Size

* Repeat the above breakdown, but this time group schools based on a reasonable approximation of school size (Small, Medium, Large).

Scores by School Size
	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Over Passing
Size Ranges					
Small (<1000)	83.821598	83.929844	93.550225	96.099436	89.883854
Medium (1000-2000)	83.374684	83.864438	93.599695	96.790680	90.621535
Large (2000-5000)	77.746417	81.344493	69.963361	82.766634	58.286003

### Scores by School Type

* Repeat the above breakdown, but this time group schools based on school type (Charter vs. District).
Scores by School Type

	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Over Passing
School Type					
Charter	83.473852	83.896421	93.620830	96.586489	90.432244
District	76.956733	80.966636	66.548453	80.799062	53.672208

As final considerations:

Based on the data provided, we can see that the top scoring schools happen to be charter schools and the bottom scoring schools are district schools.
Another observation is that with the top and bottom performing schools, their budget is also different. The top performing schools have a lower budget than the bottom performing schools.

