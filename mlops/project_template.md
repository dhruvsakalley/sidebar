# ML Systems Thinking.

ML practices come from the team, each team operates at a different capacity, skill and timeline. While some might want it to be lightweight, while others would like to put practices before delivery. 
My personal style goes something along these lines… Be lazy, be smart, be kind. I’ll probably not overthink the processes and start by clearly documenting the basics. Which according to me are:

Data attributes:
	Source details, preprocessing instructions, metadata etc.
	Allowed assumption with the underlying data. 
	Feature Stores / Feature transforms.
Problem description
	Clear target variable (what are we optimizing)
	KPO and the relation to the target variable (how does it affect the customer, possibly estimate effect size…. X% change has y impact)
Experiment design 
	Clear decision criteria for stopping (budget, time, error margin, etc).
	Evaluation criteria and Annotation Rubric.
	Iteration criteria.
Model train
	Hyperparams
	Training stats (compute, model maturity).
Model retrain
	Drift assessment and thresholds.
	Estimated retrain cadence.
	Reproducibility and Rollback.
Model Serve
	Regular API design question, benchmarks, tests, cost management
	Day 1, Day 1+ sequence diagrams
