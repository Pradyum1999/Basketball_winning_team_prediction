# Basketball_winning_team_prediction
This course was completed as a part of final project for the course Machine Learning with Python IBM on edx. The dataset features 354 basketball team's data.

This dataset is about the performance of basketball teams. The cbb.csv data set includes performance data about five seasons of 354 basketball teams. It includes following fields:

Field	Description

TEAM	The Division I college basketball school

CONF	The Athletic Conference in which the school participates in (A10 = Atlantic 10, ACC = Atlantic Coast Conference, AE = America East, Amer = American, ASun = ASUN, B10 = Big Ten, B12 = Big 12, BE = Big East, BSky = Big Sky, BSth = Big South, BW = Big West, CAA = Colonial Athletic Association, CUSA = Conference USA, Horz = Horizon League, Ivy = Ivy League, MAAC = Metro Atlantic Athletic Conference, MAC = Mid-American Conference, MEAC = Mid-Eastern Athletic Conference, MVC = Missouri Valley Conference, MWC = Mountain West, NEC = Northeast Conference, OVC = Ohio Valley Conference, P12 = Pac-12, Pat = Patriot League, SB = Sun Belt, SC = Southern Conference, SEC = South Eastern Conference, Slnd = Southland Conference, Sum = Summit League, SWAC = Southwestern Athletic Conference, WAC = Western Athletic Conference, WCC = West Coast Conference)

G	Number of games played

W	Number of games won

ADJOE	Adjusted Offensive Efficiency (An estimate of the offensive efficiency (points scored per 100 possessions) a team would have against the average Division I defense)

ADJDE	Adjusted Defensive Efficiency (An estimate of the defensive efficiency (points allowed per 100 possessions) a team would have against the average Division I offense)

BARTHAG	Power Rating (Chance of beating an average Division I team)

EFG_O	Effective Field Goal Percentage Shot

EFG_D	Effective Field Goal Percentage Allowed

TOR	Turnover Percentage Allowed (Turnover Rate)

TORD	Turnover Percentage Committed (Steal Rate)

ORB	Offensive Rebound Percentage

DRB	Defensive Rebound Percentage

FTR	Free Throw Rate (How often the given team shoots Free Throws)

FTRD	Free Throw Rate Allowed

2P_O	Two-Point Shooting Percentage

2P_D	Two-Point Shooting Percentage Allowed

3P_O	Three-Point Shooting Percentage

3P_D	Three-Point Shooting Percentage Allowed

ADJ_T	Adjusted Tempo (An estimate of the tempo (possessions per 40 minutes) a team would have against the team that wants to play at an average Division I tempo)

WAB	Wins Above Bubble (The bubble refers to the cut off between making the NCAA March Madness Tournament and not making it)

POSTSEASON	Round where the given team was eliminated or where their season ended (R68 = First Four, R64 = Round of 64, R32 = Round of 32, S16 = Sweet Sixteen, E8 = Elite Eight, F4 = Final Four, 2ND = Runner-up, Champion = Winner of the NCAA March Madness Tournament for that given year)

SEED	Seed in the NCAA March Madness Tournament

YEAR	Season

I have used kNN, Decision Trees, Support Vector Machines and Logistic regression. The metrics used were: Jaccard index, F1-score. Highest accuracy reported was 0.68
