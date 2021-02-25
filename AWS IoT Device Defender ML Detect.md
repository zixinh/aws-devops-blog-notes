**feature overview**
- ML Detect automatically set thresholds for the expected behaviour of IoT device
- available to set responses if threshold is met. e.x. quarantine a device

**workflow**
1. ML model training period: ML Detect will aggregate a minimum of 25,000 datapoints per metric for 14 days 
  - to know expected behaviours of IoT devices
3. ML model creation: after minimum data size is met, ML detect create a ML model
4. deployment: ML detect would start to detect anomalies
5. retraining: ML model is constantly updated and trained with minimum of 25,000 datapoints on the latest trailing 14 days





[blog link](https://aws.amazon.com/blogs/iot/ml-detect-for-device-defender/)
