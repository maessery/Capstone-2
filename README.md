![Salary Image](https://static0.thesportsterimages.com/wordpress/wp-content/uploads/2015/06/nhl_money1.jpg)


# NHL-Salary-Predictor
## Springboard Data Science Career Track - Capstone 2


## 1. Problem Statement

How can a predictive salary model provide NHL teams a more efficient and consistent method for contract discussions between General Managers and Player Agents using all contractual and statistical data between the years of 2008 and 2021?



## 2.  The Data
The data came from two sources: Contract information came from www.capfriendly.com, statistics came from www.hockey-reference.com. When combined, the final dataset included 61 columns.
Since Skaters (Center, Left Wing, Right Wing, Defensemen) have different performance metrics than goalies, they were split up during EDA and modeling.
### Skater Stats
- **GP** - Games Played (regular season only)

- **G** - Goals

- **A** - Assists 

- **PTS** - Points (Points= Goals + Assists)

- **PPG** - Points per Game

- **PlusMinus** - Plus/Minus statistic; being on the ice for a team goal-for results in a +1 for that player, while being on the ice for a goal against results in a -1. The final value is a cumulative result

- **ATOI** - Average Time on Ice (per game); includes all situations

- **TOI(EV)** - Even-Strength Time on Ice; a player's amount of playing time solely in non-penalty situations

- **PIM** - Penalty Minutes 

- **PS** - Point Shares; an estimate of the number of points contributed by a player

- **EV_A** - Even-Strength Assists; number of assists in all non-penalty situations 

- **PP_A** - Power-Play Assists; number of assists in Power-play situations (opposing team is serving a penalty) 

- **SH_A** - Short-Handed Assists; number of assists while a team was a man down due to penalties

- **GW** - Game-winning Goals

- **S** - number of Shots on goal

- **S_Pct** - Shooting Percentage

- **BLK** - number of Blocked shots

- **HIT** - number of Hits

- **FOW** - number of Face-offs Won

- **FOL** - number of Face-offs Lost

- **FO_Pct** - Face-off win percentage

- **CF** - Corsi-For at Even-Strength; shots + blocks + misses

- **CA** - Corsi-Against at Even-Strength; shots + blocks + misses

- **CF_Pct** - Corsi-For Percentage at Even-Strength; CF/(CF+CA) ; above 50% means the team was controlling the puck more often than not with this player on the ice in this situation

- **CF_Pct_rel** - Relative Corsi-For Percentage at Even-Strength; CF% - CFoff%; on ice corsi for % - off ice corsi for %

- **FF** - Fenwick-For at Even-Strength; shots + misses

- **FA** - Fenwick-Against at Even-Strength; shots + misses

- **FF_Pct** - Fenwick-For Percentage at Even-Strength; FF/(FF+FA) ; above 50% means the team was controlling the puck more often than not with this player on the ice in this situation

- **FF_Pct_rel** - Relative Fenwick-For Percentage at Even-Strength; FF% - FFoff%; on ice fenwick for % - off ice fenwick for %

- **oiSH_Pct** - team On-Ice Shooting Percentage; team shooting % while this player was on the ice

- **oiSV_Pct** - team On-Ice Save Percentage; team save % while this player was on the ice 

- **PDO** -  the sum of a team’s shooting percentage and save percentage when both teams are at even strength and that player is on the ice

- **oZS_Pct** - Ofensive-Zone Start Percentage; offensive zone faceoffs/(offensive zone faceoffs + defensive zone faceoffs), that took place while on the ice 

- **dZS_Pct** - Defensive-Zone Start Percentage; defensive zone faceoffs/ (offensive zone faceoffs + defensive zone faceoffs), that took place while on the ice 

- **TK** - number of Takeaways

- **GV** - number of Giveaways

- **SAtt.** - total Shots Attempted in all situations

- **Thru_Pct** - percentage of shots taken that go on net

- **SOT_Att** - Shoot-Out Attempts taken

- **SOT_Scored** - number of Shoot-Out attempts resutling in a goal

- **SOT_Saved** - number of Shoot-Out attempts resulting in missed or stopped

- **SOT_Pct** - percentage of Shoot-Out attempts scored


### Goalie Stats

- **SOT_Pct** - percentage of Shoot-Out attempts saved

- **GS** - Games Started

- **W** - Wins

- **L** - Losses

- **TplutOTL** - Ties plus Overtime Losses

- **GA** - Goals Against

- **SA** - Shots Against

- **SV** - Saves

- **SV_Pct** - Save Percentage

- **GAA** - Goals Against Average

- **SUT** - Shut-Outs

- **GPS** - Goalie Point Shares; an estimate of the number of points contributed by a player due to his play in goal.

- **MIN** - Minutes played

- **QS** - Quality Starts; starts with SV% > average SV% for the year, or at least 88.5% on nights with 20 or fewer shots against

- **RBS** - Really Bad Starts; starts with a SV% below 85%



## 3. Target Audience: , Summary
## Data Wrangling
## EDA
## Data preparation and feature selection
## Model Performance
## Hyperparameter Tuning
## Conclusion
## Future Improvements
