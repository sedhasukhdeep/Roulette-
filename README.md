# Roulette-
Probability assignment [STAT 683]

Macquarie University
STAT 683: Introduction to Probability
Assignment 1 solution, First semester 2018

Assignment By	Sukhdeep Singh
Student ID	44442467


Game 1: Betting on red
	Expected value: This is a Bernoulli trial therefore expected value can be given by the following expression
E(X)=18/37*(1)+19/37*(-1)=-1/37
Where 18/37 is the probability of winning, 19/37 is probability of losing, 1 and -1 are the amount gained in a scenario of a win/loss respectively.

Simulation results for 100000 trials: -0.02342 (Percentage error = 0.0000358%)

	Proportion of wins: Number wins for this game will be theoretically equal to 

P(W)=18/37≈0.48648
	Simulation results for 100000 trials: 0.48651 (percentage error = 0.0000003%)

	Expected playing time = 1 bet

	Maximum money player can lose = $1 

	Maximum money player can earn = $1


Game 2: Betting on a number
	Expected value: This is a Bernoulli trial so the value of the winnings can be given by the following expression
E(X)=1/37*(35)+36/37*(-1)=-1/37≈-0.0270
Where 1/37 is the probability of winning, $35 amount won, 36/37 is the probability of losing,-1 is the money lost.

Simulation results for 100000 trials = -0.02152 ( percentage error = 0.0000548%)

	Proportion of wins: Theoretically the proportion of winning can be given by
P(W)=1/37  ≈0.0270
Simulation results for 100000 trials = 0.02584 (percentage error 0.0000116%)


	Expected playing time: 1 bet

	Maximum amount player can lose= $1

	Maximum amount player can earn= $35

Game 3: Martingale system of betting

	Expected winnings by simulation = -1.82907
	Proportion of wins by simulation = 0.9138
	Expected playing time by simulation = 16
	
	Maximum amount player can lose = $127
Consecutive losses since start = -1 -2 -4 -8 -16 -32 -64 = -127
	Maximum amount player can win= $10

Game 4: Labouchere System
	Expected winnings by simulation = -3.32318
	Proportion of wins by simulation = 0.95636
	Expected playing time by simulation = 4
	Maximum amount of money player can lose = $4940
Consecutive losses since start = -5 -6 -7 -8 … -99


	Maximum amount of money player can earn =$10


Game ID	Exp winnings (min,max)	Prop wins (min,max)	Exp play time(min,max)
Game 1	-0.02992,-0.023	0.48412,0.48795	1,1
Game 2	-0.02656,-0.012	0.02708,0.2748	1,1
Game 3	-2.08799,-1.8787	0.90861,0.9112	15,24
Game 4	-3.69058,-3.40586	0.95569,0.95768	2,20


Game ID	Winnings (mean, std dev)	Prop wins (mean, std dev)	Play time (mean, std dev)
Game 1	-0.02604, 0.9996659	0.48667, 0.499824	1, 0
Game 2	-0.019, 5.861227	0.02758, 0.164722	1, 0
Game 3	-1.98986, 38.03104	0.92482, 0.274563	17.46590,4.190035
Game 4	-3.897, 70.4128	0.95674, 0.204374	8.57188, 7.751844

Labouchere System’s  winning is most variable with std dev 70.41.28
Labouchere System’s play time is most variable with std dev 7.751844


Rcode: Github Link
https://github.com/sedhasukhdeep/Roulette-








