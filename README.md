# Optimization-of-Electricity-Demand-Reduction-with-Comfort-Conscious-Learning

## Dataset
Smart* Data Set for Sustainability - [UMass Smart* Dataset - 2017 release](http://traces.cs.umass.edu/index.php/Smart/Smart)

### Datetime encoding
[Encoding cyclical continuous features - 24-hour time](https://ianlondon.github.io/blog/encoding-cyclical-features-24hour-time/)

## Learning Algorithm
- [VPG](https://spinningup.openai.com/en/latest/algorithms/vpg.html)
- [PPO](https://spinningup.openai.com/en/latest/algorithms/ppo.html#)

## Reward Evaluation
- [需量反應負載管理措施](https://www.taipower.com.tw/upload/135/2018071708513325281.pdf)
- [臨時性減少用電措施－限電回饋型](https://www.taipower.com.tw/upload/135/2018121814155587242.pdf)

## Script
- [training.ipynb](./training.ipynb): take action from PPP and define environment with applianace and resident feedback
- [metrics.ipynb](./metrics.ipynb): calculate four evaluation metrics (power, reward, comfort, dr_rate)
