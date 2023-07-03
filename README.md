# IPL-Runs-Earned-


Cricket teams win matches by earning more runs than their opponent. The
following questions suppose that you’ve been tasked with developing an in-game
tool to help IPL cricket teams assess their run production performance in first
innings. This is to be completed using the attached data. The following tasks 
will relate to the development of a statistical model for run evaluation.


Task 1:
Most cricket teams expect run production to vary significantly
with overs and wickets remaining. Derive a variable runs earned
that is the total runs scored from any combination of overs_remaining or
wickets_remaining. For example, if a team earned 200 runs in an innings and
20 of those runs happened in the first over without a wicket earned, then the
runs earned would be 200 with 20 overs and 10 wickets remaining and then
180 with 19 overs and 10 wickets remaining.
* Create a function to assign this variable to your dataset.
*  Identify if there are any outliers in runs earned and describe what you find.
*  Take any steps that you think are necessary for handling any outliers you find and explain your reasoning.

Task 2:
Create a visualization to show how runs earned varies with overs
and wickets remaining. Interpret the relationship you observe.


Task 3:
Build a model to estimate the average expected runs that can be
earned from any possible combination of overs and wickets remaining.
Show code to fit the model and evaluate it’s performance.
