# DVR: Micro-Video Recommendation Optimizing Watch-Time-Gain under Duration Bias

This is our TensorFlow implementation for DVR.

The code is tested under a Linux desktop with TensorFlow 2.3 and Python 3.8.10.




## Model Training

Use the following command to train a DVR model on `Wechat` dataset: 

```
python examples/run_video_debias.py --dataset wechat
```

or on `Kuaishou` dataset:

```
python examples/run_video_debias.py --dataset kuaishou
``` 

## Note

The implemention is based on *[DeepCTR](https://github.com/shenweichen/DeepCTR)*.