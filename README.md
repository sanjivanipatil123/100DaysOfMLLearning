# Football Data Test Task
 "Raw Data Information
Blue columns in the raw data are the ones that will be used to derive the yellow columns from manipulated data

Task that needs to be performed in the raw data
Convert all the blue columns into the columns that can be used
Convert each column into last 5, 15 and 38 matches
Last 5 matches of home team and last 5 matches of away team
Perform 3rd point to 15 and 38 as well
Every blue column in the raw data needs to be converted into this manner
For example-
Total number of matches won by home team in last 5,15 and 38 matches
Do same for away as well
Home team and away team should be that particular football team
For row 2 in Raw Data home team is Aston Villa and away team is Bolton
So it should be like total number of matches won by Aston Villa in last 5 matches (home and away both)
Total number of matches won by Bolton in last 5 matches (home and away both) and so on
For example-
FTHG_L5 (for Arsenal)
AA2 (from Manipulated Data Sheet)  =  G372 + H370 + H366 + G349 + G332   (From Raw Data Sheet)
ManipulatedData!AA2 =  4 + 3 + 3 + 1 + 3 = 14



About Data
1. HomeTeam - Home team playing the match
2. AwayTeam - Away team playing the match
3. FTHG - Full-Time Home Goals (goals scored by the home team at the end of the match)
4. FTAG - Full-Time Away Goals (goals scored by the away team at the end of the match)
5. FTR - Full-Time Result (H = Home win, D = Draw, A = Away win)
6. HTHG - Half-Time Home Goals (goals scored by the home team by halftime)
7. HTAG - Half-Time Away Goals (goals scored by the away team by halftime)
8. HTR - Half-Time Result (H = Home win, D = Draw, A = Away win)
9. Referee - Name of the referee officiating the match
10. HS - Home Shots (total number of shots by the home team)
11. AS - Away Shots (total number of shots by the away team)
12. HST - Home Shots on Target (shots on target by the home team)
13. AST - Away Shots on Target (shots on target by the away team)
14. HF - Home Fouls (fouls committed by the home team)
15. AF - Away Fouls (fouls committed by the away team)
16. HC - Home Corners (corners won by the home team)
17. AC - Away Corners (corners won by the away team)
18. HY - Home Yellow Cards (yellow cards received by the home team)
19. AY - Away Yellow Cards (yellow cards received by the away team)
20. HR - Home Red Cards (red cards received by the home team)
21. AR - Away Red Cards (red cards received by the away team)
30. HS_L38 - Home Shots in the last 38 matches
31. AS_L5 - Away Shots in the last 5 matches
32. AS_L15 - Away Shots in the last 15 matches
33. AS_L38 - Away Shots in the last 38 matches
34. HST_L5 - Home Shots on Target in the last 5 matches
35. HST_L15 - Home Shots on Target in the last 15 matches
36. HST_L38 - Home Shots on Target in the last 38 matches
37. AST_L5 - Away Shots on Target in the last 5 matches
38. AST_L15 - Away Shots on Target in the last 15 matches
39. AST_L38 - Away Shots on Target in the last 38 matches

Fouls statistics:

40. HF_L5 - Home Fouls in the last 5 matches
41. HF_L15 - Home Fouls in the last 15 matches
42. HF_L38 - Home Fouls in the last 38 matches
43. AF_L5 - Away Fouls in the last 5 matches
44. AF_L15 - Away Fouls in the last 15 matches
45. AF_L38 - Away Fouls in the last 38 matches

Corners statistics:

46. HC_L5 - Home Corners in the last 5 matches
47. HC_L15 - Home Corners in the last 15 matches
48. HC_L38 - Home Corners in the last 38 matches
49. AC_L5 - Away Corners in the last 5 matches
50. AC_L15 - Away Corners in the last 15 matches
51. AC_L38 - Away Corners in the last 38 matches

Cards statistics:

52. HY_L5 - Home Yellow Cards in the last 5 matches
53. HY_L15 - Home Yellow Cards in the last 15 matches
54. HY_L38 - Home Yellow Cards in the last 38 matches
55. AY_L5 - Away Yellow Cards in the last 5 matches
56. AY_L15 - Away Yellow Cards in the last 15 matches
57. AY_L38 - Away Yellow Cards in the last 38 matches
58. HR_L5 - Home Red Cards in the last 5 matches
59. HR_L15 - Home Red Cards in the last 15 matches
60. HR_L38 - Home Red Cards in the last 38 matches
61. AR_L5 - Away Red Cards in the last 5 matches
62. AR_L15 - Away Red Cards in the last 15 matches
63. AR_L38 - Away Red Cards in the last 38 matches

Win/Loss/Draw records over the last 5, 15, and 38 matches:

64. HW_L5 - Home Wins in the last 5 matches
65. HW_L15 - Home Wins in the last 15 matches
66. HW_L38 - Home Wins in the last 38 matches
67. HL_L5 - Home Losses in the last 5 matches
68. HL_L15 - Home Losses in the last 15 matches
69. HL_L38 - Home Losses in the last 38 matches
70. HD_L5 - Home Draws in the last 5 matches
71. HD_L15 - Home Draws in the last 15 matches
72. HD_L38 - Home Draws in the last 38 matches
73. AW_L5 - Away Wins in the last 5 matches
74. AW_L15 - Away Wins in the last 15 matches
75. AW_L38 - Away Wins in the last 38 matches
76. AL_L5 - Away Losses in the last 5 matches
77. AL_L15 - Away Losses in the last 15 matches
78. AL_L38 - Away Losses in the last 38 matches
79. AD_L5 - Away Draws in the last 5 matches
80. AD_L15 - Away Draws in the last 15 matches
81. AD_L38 - Away Draws in the last 38 matches"
