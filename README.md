## Multioutput-Regression+Optimization

Here we will be tackling an operational research problem while dealing with multiple target variables.
(For a simpler example, refer my repository named 'Operational Research using R')

Here we are looking to optimize the manufacturing process for a particular product across multiple metrics,
- Yield (output)
- Time (Duration)
- Quality
First we will categories the variables/columns in our dataset into 3 types,
- Raw Material Properties
- Process Parameters
- Targets (Yield, Time, Quality metrics)
Essentially for a set of raw material properties, we want to suggest process parameters, such that we are mazimizing our output (yield), minimizing time (duration) while ensuring/maintaining product quality.

Have a look at the data file at this point to get a clear picture of the problem at hand.
To solve this we will divide our problem into 3 steps,
- Clean/Preprocess Data (Including feature selection & EDA)
- Train the model on the polished dataset
- Use the trained model to optimize the process for specific inputs
