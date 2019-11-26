# awesome-streaming-outlier-detection [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

This list contains resources, implementations and benchmarks about streaming outlier detection algorithms.

## Papers and Implementations

1. **[Data Outlier Detection using the Chebyshev Theorem](https://www.researchgate.net/publication/224624985_Data_outlier_detection_using_the_Chebyshev_theorem) - Brett G. Amidan, Thomas A. Ferryman, and Scott K. Cooley, 2005.** The implementation for an onine version of the algorithm using for the NAB can be found [here](https://github.com/kyrcha/NAB/blob/master/nab/detectors/chebyshev/chebyshev_detector.py). A short write-up of how the algorithm works can be read in this [blog post](http://kyrcha.info/2019/11/26/data-outlier-detection-using-the-chebyshev-theorem-paper-review-and-online-adaptation).

## Datasets

- [The Numenta Anomaly Benchmark (NAB)](https://github.com/numenta/NAB) - NAB is a novel benchmark for evaluating algorithms for anomaly detection in streaming, real-time applications. It is composed of over 50 labeled real-world and artificial timeseries data files plus a novel scoring mechanism designed for real-time applications.

## Benchmarking

| Algorithm  | NAB Standard Profile  | NAB Reward Low FP  |  NAB Reward Low FN  |
|---|-------|-------|-------|
| 1 | 18.44 |  13.18 | 23.21 |
