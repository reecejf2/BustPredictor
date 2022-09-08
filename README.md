# BustPredictor

When designing a bust predictor, what do we want to know?

What qualifies as bust
	Do injuries count?
	Relative to draft pick
	College stats are misleading?
	Years Played
	Size, shape / individual metrics


	Metric For Calling Someone a Bust. How do we quantify?

	Player Value. WAR. 
		How do we calculate WAR. How do we transpose it to basketball. How do we find. 	
			Called value over replacement player. We need this.

	Relative Player Value. What is the average value for each draft pick. 

	How many years to be 95% confident someone is a bust. Testing versus a model 

Implementation. Some natural first steps.
1. Setup a dev environment. This means get a file, a dataset, a terminal. Load the dataset and make sure it seems reasonable. Use Python.
2. The first thing we want to do is figure out WAR. We also need a new stat which we call relative WAR.
3. Once, we have this, lets look at the lowest relative WAR and try and identify benchmarks that these guys have that can relate to the qualitative term "bust".
