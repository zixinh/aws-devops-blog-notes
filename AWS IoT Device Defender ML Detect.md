**feature overview**
- ML Detect automatically set thresholds for the expected behaviour of IoT device
- available to set responses if threshold is met. e.x. quarantine a device

**workflow**
- ML model training period: ML Detect will aggregate a minimum of 25,000 datapoints per metric for 14 days 
  - to know expected behaviours of IoT devices
- ML model creation: after minimum data size is met, ML detect create a ML model
- deployment: ML detect would start to detect anomalies
- retraining: ML model is constantly updated and trained with minimum of 25,000 datapoints on the latest trailing 14 days





[blog link](https://aws.amazon.com/blogs/iot/ml-detect-for-device-defender/)
