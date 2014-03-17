# MATLAB Spring 2014 – Research Plan

> * Group Name: PrisonBreak
> * Group participants names: Robert H.W. ten Brincke
> * Project Title: Cooperation and (Conditional) Social Value

## General Introduction

Many of the interactions in modern society depend on successful cooperation between individuals, groups or even governments. In pre-industrialised societies such as that of the people of Lamalera in Indonesia, hunters cooperatively hunt for whales (Alvard, 2003) for their livelihood. Friendship, relationships, business agreements, contracts and international agreements, such as the Kyoto initiatives to reduce CO2 emissions, are all examples of cooperation. Such cooperation may however be costly to the individual and hence form a source of conflict. Relationships end, business settle matters in court and CO2 targets are frequently not met or even agreed upon. Furthermore it can be tempting for individuals to unilaterally back out of the agreement while still enjoying the benefits.

The Prisoner's Dilemma is arguably one of the most important classes of economic games. This strategic situation precisely represents those situations in which mutual cooperation is beneficial, but defection from doing so is tempting. The standard solution of the Prisoner's Dilemma comes from game theory in the form of a Nash equilibrium. A Nash equilibrium is a strategy profile in which neither player can be better off by unilaterally deviating from that profile. The equilibrium situation for the Prisoner's Dilemma is mutual defection. This equilibrium is however Pareto deficient. Both players could be better off by instead cooperating. It is one of the most widely studied games in history, starting at the famous RAND corporation in the early 1950s. A popular account was written by Poundstone (1992). The results of many experiments can be found in Rapoport and Chammah (1965) and Camerer (2003).

## The Model

In this project we consider a repeated Prisoner's Dilemma (PD) in which subjects are unaware of the number of repetitions. While the one shot Prisoner's Dilemma has been widely studied, repeated interactions result in profoundly different behavior (Camerer, 2003). Once repeated interactions come into play, learning becomes an important factor. Research on how people learn to cooperate in repeated games is scarce (Gonzalez et al., in press). Additionally it has long been recognized that social preferences may play an important role in game theory (Rabin, 1993; Camerer, 2003). Recently these two have been integrated in papers by Gonzalez et al. (under review), Gonzalez et al. (in press), Ben-Asher & Gonzalez (2013) and Murphy & Ackermann (working paper).

In their model, Gonzalez & Ben-Asher (under review) (hence GBA) use an Instance-Based Learning (IBL) model with dynamic social preferences to explain the various rates of cooperations in different manifestations of the repeated PD. Social preferences (SP; Murphy and Ackermann, 2013) are linearly defined as the weight that is placed upon the other person's payoff in addition to the own (utility=my_payoff+SP*other_payoff). By dynamically adjusting SP over time depending on past interactions, the authors are able to explain the level of cooperation for a variety of Prisoner's Dilemma games by using simulations.

## Fundamental Questions

GBA simulate 200 repeated PD games for which they took data from Rapoport and Chammah (1965). Murphy and Ackermann (working paper) however show that with an upper and lower bound, all PD games can be represented as a combination of two values. It is interesting to see if there are certain regimes within which GBA's model predicts cooperation and other regimes within which defection is predicted. Such results could be compared against other results in literature. It could for example be that the majority of PD games are those exactly in a certain regime.

Secondly, GBA have some important assumptions in their model. One of those assumptions leads to the implicit result that the first game is very important for the model results. It is prudent to test the robustness of results once we modify those assumptions.

Thirdly, GBA assume the linear function

	utility = my_payoff+SP*other_payoff
	
for which higher values of social preferences (SP; meaning placing more weight on the other person's payoff and hence being more pro-social) may be contingent upon the other person's cooperation. Such contingent social preferences appear to play an important role (Ackermann et al., 2013). A model that takes into account such contingent social preferences may outperform the current model and better explain rates of cooperation.

## Expected Results

I will attempt to replicate GBA's results and extend these to all Prisoner Dilemma games within two bounds. I expect to find regions within the full set in which cooperation is predicted and regions in which defection is predicted. Certain assumptions may have a large effect on what these regions look like and I expect the assumption that the first observation is so strong may play a large role in the model. I then expect models that incorporate contingent cooperation to perform at least as well or even outperform the current model.

## References 

Ackermann, K. A., Fleiss, J., & Murphy, R. O. (2013). Reciprocity as an individual difference. Manuscript in preparation.

Ben-Asher, N., Dutt, V., & Gonzalez, C. (2013). Accounting for integration of descriptive and experiential information in a repeated prisoner's dilemma using an instance-based learning model. In B. Kennedy, D. Reitter & R. St. Amant (Eds.), Proceedings of the 22nd Annual Conference on Behavior Representation in Modeling and Simulation. Ottawa, Canada: BRIMS Society.

Camerer, C. F. (2003). "Behavioral game theory: Experiments in strategic interaction." Princeton, NJ: Princeton University Press.

Gonzalez, C., Ben-Asher, N., Martin, J. M., & Dutt, V. (in press). Emergence of cooperation with increased information: Explaining the process with instance-based learning models. Cognitive Science.

Gonzalez, C. and Ben-Asher, N (under review). Learning to cooperate in the Prisoner's Dilemma: Robustness of Predictions of an Instance-Based Learning Model. Cognitive Science.

Murphy, R. O., & Ackermann, K. A. (2013). Social value orientation: Theoretical and measurement issues in the study of social preferences. Personality and Social Psychology Review (in press).

Poundstone, William. "Prisoner's Dilemma: John von Neuman, Game Theory, and the Puzzle of the Bomb." (1992). University of Michigan Press.

Rabin, Matthew. "Incorporating fairness into game theory and economics." Advances in Behavioral Economics (1993): 297.

Rapoport, A., & Chammah, A. M. (1965). "Prisoner's dilemma: A study in conflict and cooperation." Ann Arbor: University of Michigan Press.

Related projects from previous years are Learning Dynamics in Social Dilemmas of FS2012 and the Axelrod Tournament of FS2011.

## Research Methods

Discrete modelling, learning models, social value models and Bayesian learning models.

## Other

Data on PD games is widely available in many books and papers. The book by Rapoport and Chammah (1965) contains sufficient data for carrying out this project, but PG games have been a topic of research for many recent years.