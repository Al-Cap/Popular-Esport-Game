# Popular Esport Game
<p align="center">
   <img src=https://github.com/Al-Cap/Popular-Esport-Game/blob/master/pictures/game-genre-icons.png />
<div align="center">
   <figcaption></figcaption>
</div>
</p>

## Overview

The University of Maryland Baltimore County (UMBC) is looking at Esports. They want to find which game to start with. By looking at three different aspects: players, tournaments, and earnings will be used to determine the most popular game.

## Repository Navigation
<pre>
Code               : <a href=https://github.com/Al-Cap/Popular-Esport-Game/blob/master/Notebook/Project_1.ipynb>Main Source</a>
Charts             : <a href=https://github.com/Al-Cap/Popular-Esport-Game/blob/master/Notebook/Untitled.ipynb>Modified Source</a>
</pre>

## ReadME Navigation

[Data](https://github.com/Al-Cap/Popular-Esport-Game#data) - 
[Modeling](https://github.com/Al-Cap/Popular-Esport-Game#modeling) - 
[Results](https://github.com/Al-Cap/Popular-Esport-Game#results) - 
[Future](https://github.com/Al-Cap/Popular-Esport-Game#future) - 
[Project Info](https://github.com/Al-Cap/Popular-Esport-Game#project-info)

## Data
The dataset is obtained from [Kaggle Esports Earnings](https://www.kaggle.com/rankirsh/esports-earnings). It includes 492 games ranging from 1981-2020. The data has been cropped so only the games from 2000-2020 are used.

![tour-rel.png](https://github.com/Al-Cap/Popular-Esport-Game/blob/master/figures/tour-rel_bar.png)

## Modeling

The data is split into three part: Players, Tournaments, and Earnings.

### Players

The total number of players are comapre to the different genres for games. This shows the genres that have the most player base. Total of players is then compared to the games in the specific genre with the most players. This being First-Person Shooter games. Data in second chart is modified to fit.

![genre-ply.png](https://github.com/Al-Cap/Popular-Esport-Game/blob/master/figures/genre-ply_barh.png)

![FirstP-Shooter.png](https://github.com/Al-Cap/Popular-Esport-Game/blob/master/figures/FirstP-Shooter_game-player_barh.png)

### Tournaments

Tournaments are comapre to the different genres for games. This shows the genres that has the most tournaments held for games of the same genre. Total of tournaments is then compared to the games in the specific genre with the most tournaments. This being Stratey games. Data in second chart is modified to fit.

![genre-tour.png](https://github.com/Al-Cap/Popular-Esport-Game/blob/master/figures/genre-tour_barh.png)

![Strategy.png](https://github.com/Al-Cap/Popular-Esport-Game/blob/master/figures/Strategy_game-tour_barh.png)

### Earnings

The total earnings for each genre of game are comapred. This shows the genres that earns the most money at tourenaments and other events. The total earnings is then compared to the games in the specific genre with the most earnings. This being Multiplayer Online Battle Arena games. Data in second chart is modified to fit.

![genre-tearn.png](https://github.com/Al-Cap/Popular-Esport-Game/blob/master/figures/genre-tearn_barh.png)

![MultiOnlineBattleArean.png](https://github.com/Al-Cap/Popular-Esport-Game/blob/master/figures/MultiOnlineBattleArean_game-earn_barh.png)

## Results

The results show that the most popular game among players is [Counter-Strick: Global Offensive](https://store.steampowered.com/app/730/CounterStrike_Global_Offensive/). Game with most tournaments is [Star Craft II](https://starcraft2.com/en-us/) and for total Earnings is [Dota 2](https://store.steampowered.com/app/570/Dota_2/).
the game for players shows the most popular game among a player base. The tournament game shows the most popular game among competetors. Lastly, th game for earnings shows how much money is put into one game whether this being tournaments, the fan base, or advertisements. 

Aspect | Game
---|---
Players | Counter-Strike: Global Offensive
Tournaments | Star Craft II
Earnings | Dota 2


## Future

UMBC can pick from the three games consisting of Counter-Strike: Global Offensive, Star Carft II, and Dota 2. However, the school does not have to go for these since they are vry popular. The school could pick a less popualr game with similar notoriety as the ones mentioned. 

## Project Info
<pre>
Contributors : <a href=https://github.com/Al-Cap>Alexander Caporale</a>
</pre>

<pre>
Languages    : Python
Tools/IDE    : Anaconda
Libraries    : pandas, matplotlib, numpy, xlrd
</pre>

<pre>
Duration     : September 2020
Last Update  : 09.17.2020
</pre>
