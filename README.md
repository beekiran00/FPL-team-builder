# FPL-team-builder
A fantasy premier league team builder, made with Tableau and PowerBI

## This Project aims at making selection of players from the premier league pool easier with the help of dashboards.

###The dashboard is created in mind kepeing the restrictions imposed by a fantasy league team which are:

1. Each fantasy player starts with a limited budget of 100MM and has to buy 15 soccer players (11 for the main squad + 4 subs) in order to compete. You need to have at least 2 Goalkeepers, 5 Defenders, 5 Midfielders, and 3 Forwards in order to complete your squad and be eligible to play. You cannot have more than 3 players from the same soccer team
2. There is a budget/point limit of 100. This means that each player comes with a cost, i.e, there is a cost constraint over the limited selections of the players.

### The dashboard is created with aims to solve the following research questions and their answers as requirements:

Q1. Which of the players from each category gives good ROI (returns on investment) so as to make a good team?
R1: To answer Q1, the user needs to visualise Players from each positions, as well as their ROI. Some of the players might have ROI of a higher number, but that comes with a higher cost. Hence the user needs to easily pick the best ROI. For this, a tree map is a good view, with the size of each box corresponding to the player’s ROI. The tree map follows a colour gradient so the user can easily pick out the best ROI value for the price of the player.
Q2. To change and update the team with limited team budget, which of the players have been consistent this season based of performance and their value?
R2: For this there needs to be a few visual graphs that can satisfy the requirements. Firstly the user needs to be able to see how a particular player performed in the last season, and how they are performing this season along with their points per game. Scatter graphs would be a good visual as the user can easily hover over the desired cost per points and find out players
R3: An additional table visual would be useful to display useful information such as the number of red cards or yellow cards they have along with stats such as points per game, cost etc.
For all the requirements above, A filter would fit. This filter allows the user to select the player’s position such as forward, defender, mid fielder, goal keeper so as to make the process of team selection easier.


## How the dashboard works:

The same dashboard is created in Tableau as well as PowerBI

<img width="1116" alt="Screenshot 2022-09-25 at 4 09 47 pm" src="https://user-images.githubusercontent.com/63056373/192151298-f9b3a3d9-0169-4768-8c23-fc3caf9b521f.png">

![image](https://user-images.githubusercontent.com/63056373/192151339-c55bbb94-5da1-444b-a4e8-1c2ff414c14f.png)

