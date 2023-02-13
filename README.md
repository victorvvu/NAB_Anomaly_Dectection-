# NAB_Anomaly_Dectection


This repository was taken from Kaggle from NAB who have real life data of anomalies relating to machien temperature. This is univariate dataset with only temperature and the known times of incident (3).


## 1. Summary 


##### Technical Overview
The dataset is imbalanced in that there are only 3 occurences of failures of the machine. Here I wanted to experiment with an unsupervised anomaly detection technique, Isolated Forest. 

## 2. Results

In the notebook provided, I tested the model performance by adjusting the contamination value to see how the model would perform (.05 and .01), since changing the n_iters would not signficantly improve model performance. 


## 3. Data Description


- timestamp
- value (temperature if internal machine)

  
## 4. Libraries

-sklearn
- numpy
- pandas 

## 5. References

Lavin, Alexander and Ahmad, Subutai. "Evaluating Real-time Anomaly Detection Algorithms – the Numenta Anomaly Benchmark", Fourteenth International
Conference on Machine Learning and Applications, December 2015.
