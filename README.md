# blueberry-python-data

Sample Repo For Data Experiment with fNIRS - Hemodynamic Response Data
https://medium.com/blueberryx/learn-to-work-with-next-gen-neurotech-data-fnirs-with-this-easy-tutorial-7ce9272ee9fb
---

#Steps


### Step 1:
```
Install the required libraries for scikit learn and pandas (tools for managing the data + performing some of the initial analysis) - this notebook was built using Python 3 Kernel
```

### Step 2:
```
Explore initial types of analysis to run on fNIRS data, most statistical analysis will try out 4 in this tutorial:
	Standard Deviation
	Mean/Average
	Rolling Average 
	Volatility and Change in Rolling Average

In each case a window of time is selected to get a snapshot of what the data looks like.
Hemodynamic responses in fNIRS data typically occur over a 5 to 25 second window of time.
```

### Step 3: 
```
From the rolling average of the HbO change it becomes possible to see a pattern or rhythm of rise and fall of HbO during a task period
In the sample data provided over it is possible to see the overall rise and fall 2 times. Rhythmic Mayer Waves are present in blood flow data though!
```

### Step 4: 
```
Potential methods to determining the 'brain activity' signal from the Mayer Waves
To account for this rhythmic signal within the data we can filter the dataset to try to get the overall trend.
```

### Step 5: 
```
Exploring potential rate of change and volatility as a method to explore clearer identification of periods where overall increasing rates of change of HbO2 become evident in the signal to determine a level of brain activity or mental effort/stress - this is one sample set of data from a period of work
```

### Step 6: 
```
Experimenting volatility and  standard deviation to determine an impact of higher or lower rate of change in overall trend of HbO2 changes as measured by the sensor
```

### Step 7: 
```
Comparing to WPM to HbO2. Here is the preliminary result which shows an increase in brain activity at points of difficulty during the writing session. This was a fun self assessment to see what changes could be identified.
```