## Was Ronaldo the cause of Rashford's poor performance

Before the start of the World Cup, Ronaldo criticised Manchester United and its manager Erik Ten Hag in an interview with Piers Morgan. Ronaldo left the club and joined Al Nassar after his World Cup journey. 
Departure of Ronaldo did not affect Manchester United in a negative way, instead the club won 23 points in ten games, the same amount as the first 15 games with Ronaldo in squad. One of the players who has benefited from Ronaldo departure is Rashford. He has scored 18 goals in 19 games after the World Cup, whereas he had only scored 5 goals in 15 games before the World Cup.   

By 'controlling variable', many people believe that the return of Ronaldo in 21/22 season was the cause of Rashford's poor performance. Although the two events sound irrelevant, the ratings from whoscored.com supports such ideas:

![image](https://user-images.githubusercontent.com/122363462/224631315-7adcb350-da40-4ef2-8e51-b55fbdcb1d9e.png)
<sub>*Figure 1.* Left: Rashford's rating without Ronaldo. Right: Rashford's rating with Ronaldo. </sub>

From the above chart, it can be seen that when Rashford plays alone, he can achieve a score of 7 or higher in 74% of the matches, and only 4% of the matches will receive a score below 6, which is unqualified. However, in matches where he played with Ronaldo, Rashford has never received a score above 8, and nearly 70% of the matches he only received a barely passing score (6-7). In addition, Rashford's average score when playing alone is 7.3, while his average score when playing with Ronaldo is only 6.5.

However, The ratings only quantify Rashford's performance, it does not illustrate the correlation between his performance and presence of Ronaldo. Therefore, we will need to explore more information to find the correlation between them. Below are heatmap of Rashford and Ronaldo:

![image](https://user-images.githubusercontent.com/122363462/224698400-c77739bc-5d08-4916-9262-9a37db32cc3a.png)                                               
 <sub>*Figure 2.* Heatmap of Rashford when played alone </sub>

 ![image](https://user-images.githubusercontent.com/122363462/224699646-409bd0ac-9e48-4060-bb12-b90c27acb44d.png)                                               
<sub>*Figure 3.* Heatmap of Rashford when played with Ronaldo </sub>

![image](https://user-images.githubusercontent.com/122363462/224699827-e753f61d-ddb9-4471-b1ad-a13bcb46d293.png)                                               
<sub>*Figure 4.* Heatmap of Ronaldo </sub>

As a right-footed player who likes to cut inside, Rashford has mostly played as a left winger since his debut. Even when playing as a right winger, he frequently swapped with the left winger. This can be seen in the heatmap above, where Rashford's density on the left half of the field was much higher than on the right half. Similarly, as a right-footed player, Ronaldo favours the left half of the field where the density is highest in this area.

![image](https://user-images.githubusercontent.com/122363462/224703125-1952032d-6dea-47b9-abf9-d7d6df90fb88.png)                                             
<sub>*Figure 5.* Heatmap of Ronaldo and Rashford in percentage </sub>

![image](https://user-images.githubusercontent.com/122363462/224703408-9054d7be-e13b-4a48-900f-d9e1e7d8235c.png)                                              <sub>*Figure 6.* Heatmap of Rashford when played with or without Ronaldo in percentage </sub>

Closely examining the heatmap, we can see that Rashford's areas of touches did not change significantly with Ronaldo's presence (as shown in Figure 6), but their favoured touching areas did overlap to some extent (as shown in Figure 5). Considering the existence of the left midfielder and left-back in the left half of the field, there were inevitably many issues in distributing the possession of the ball. As the official designated core player, Ronaldo had priority in ball possession, while both left-backs in the 21-22 season were left-footed players, making them almost the only choice for the team's attack on the left side (crossing into box from the baseline), and they naturally share a lot of ball possession. This made Rashford's situation in this area very awkward, as reflected in his average number of shots per game:

![image](https://user-images.githubusercontent.com/122363462/224705799-0ac837da-b11b-4ca6-b4c3-b28aaf156f51.png)                                             
<sub>*Figure 7.* Rashford's Shots per game in 21-22 and 22-23 season, as well as when played with or without Ronaldo </sub>

Although Rashford's average number of shots per game reached 2 when playing with Ronaldo, which does not seem significantly different from the 2.85 shots per game when playing alone, the actual probability of two values (2 and 2.85) being equal is only 0.055 [1]. Therefore, we may conclude that Rashford had more opportunities to shoot when playing alone. It is worth noting that Rashford's other key statistics (key passes, number and success rate of dribbles, and shot conversion rate) were not significantly different from last season. This suggests that as a right-footed left winger, his struggles in last season and early this season were primarily due to being crowded out in the left half of the field and lacking shooting opportunities. The introduction of forward coach McCarthy and tactical/encouragement from Ten Hag may have helped, but the most crucial factor is that Rashford can now play more freely in the area he favours.

[1] p-value = 0.055, t-value = 1.639, df = 35

* all data were collected from whoscored.com
* code used to generate heatmaps can be found in the 'Touch No R' folders
