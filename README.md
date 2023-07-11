# python-project
DATA ANALYSIS OF IPL MATCHES

 ![image](https://github.com/Savitha2512/python-project/assets/137802187/f917f596-ab90-4921-a1c9-5bbf4965d59f)

Introduction: Indian Premier League (better known as IPL) is a short format (T-20) Mens Cricket tournament that is hosted in India. It is currently presided over by the Board of Cricket Control of India (BCCI). The Tournament comprises of 8 teams who complete with each other in a league format, which is followed by a knockout Stage. Some of the Teams who Played previously are no more in action (For e.g. Deccan Chargers, Kochi Tuskers, Gujrat Lions, Pune Warriors etc). Two teams have been banned for two seasons, but have been a part of the tournament for the rest. Lets check upon our analysis furthur. Just a note, the data available over her is from 2008-2019, and all the data findings have been as per the data.
LIBRARIES
import matplotlib.pyplot as plt
import seaborn as sns
%matplotlib inline
import plotly.express as px
import plotly.graph_objects as go
Reading the Input File
linkcode
data=pd.read_csv("IPL_2020.csv")
file2.head()

Most wins in IPL

 ![image](https://github.com/Savitha2512/python-project/assets/137802187/09fa41b6-27f1-4c6e-848a-273caa8883c0)

From the graph it is evident that “chennai super kings” and “Mumbai Indians” have the most wins.Through python we can hover over the data and can clearly understand about the wins of every particular team.
 
DATA HISTOGRAM
 
 ![image](https://github.com/Savitha2512/python-project/assets/137802187/5e159fc0-d2b1-47ee-b460-510d7a0ecd60)

![image](https://github.com/Savitha2512/python-project/assets/137802187/330523ab-3623-4ad4-bbc0-4c6ae871d63d)


This shows the histogram of each and every column of the ipl 2020. From this we can get the exact data of each and every particular column.
TOP VENUES

![image](https://github.com/Savitha2512/python-project/assets/137802187/3f13ed49-1045-4d87-ae8a-92b8b3ac7100)

![image](https://github.com/Savitha2512/python-project/assets/137802187/fc9f9324-ffd5-4f2a-adae-6983178a145c)


The total venues is clearly visible in the picture but the second picture depicts the top 10 venues. In python, we can clearly get the picture of the venues which is frequently used.
 
 
TOP 5 UMPIRES
The two pictures clearly explains the umpires who are constantly performing, henceforth they are likely to get hired for the rest of the match

 ![image](https://github.com/Savitha2512/python-project/assets/137802187/53135675-e794-41a8-b8a7-fb18907b6c7d)

 
The second picture depicts the second umpire who are constantly showing good performance.


![image](https://github.com/Savitha2512/python-project/assets/137802187/02c0d28a-a658-465e-90e0-594236f6b3c1)

Creating a list of the Top 10 Wicket Takers in a match of IPL

 ![image](https://github.com/Savitha2512/python-project/assets/137802187/bc5799e9-376a-438b-be25-8c7bdf626379)

 ![image](https://github.com/Savitha2512/python-project/assets/137802187/be801087-b652-4eff-9bec-5fa16f11e489)

This graph shows the correlation between wicket and runs per wicket

 ![image](https://github.com/Savitha2512/python-project/assets/137802187/e4a796c6-545f-4dae-bef5-75b15735f630)

 ![image](https://github.com/Savitha2512/python-project/assets/137802187/9d6c9855-5ef5-483c-9f0e-9631d8ef0f95)

The Scatter Plot depicts there are many existing outliers. Players having very low ball counts have shown very high values of economy rate, as well as extremely low values- The counts of which are low, but there are examples in the dataset. These are the potential outliers, which we need to ignore in our analysis. Hence we have chosen the bowlers who have bowled a particular number of balls,and thus we are able to identify the best choice among the entire list.

CONCLUSION

We have now come to the point where we summarize out findings. We shall be providing them in the below points:
The Tournament has shown a slight favourism towards the winning Teams. What I mean to say is Stadiums like Chinnaswamy, Eden Gardens, Wankhede etc have hosted huge number of games. Now obviously this factor adds an edge to the home teams for these stadiums- and indeed they have been the most successful teams in the history of the Tournament- Chennai Super Kings, Kolkata Knight Riders, Mumbai Indians etc. Although this is not the prime factor, yet has a weightage.
Multiple players who could have been a good potential to the world of Cricket- have got very less appearance opportunities, or have been dropped due to a few inconsistent performances. We often come across news of players in the Indian Premier League, who have left the game of cricket and resorted to means to support their families.
Since Each Team gets an opportunity to Play at least 7 matches in their Home Ground, most teams have also won the highest number of their wins in their Home Grounds. But Teams like Mumbai Indians and Chennai Super Kings have performed really well at away grounds too. This constitutes one of the major reasons, as to why these teams have been the most successful in the IPL History.
The Batting and Bowling Averages of most of teams are better in the First innings-as compared to the second innings

