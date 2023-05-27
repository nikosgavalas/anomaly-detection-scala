## Implementations of selected algorithms for Anomaly Detection in Apache Flink

For an explanation about the algorithms, experiments etc., see my thesis [here](https://dspace.lib.ntua.gr/xmlui/bitstream/handle/123456789/49060/thesis_gavalas.pdf).

#### Algorithms
1. Isolation Forest ([paper](https://cs.nju.edu.cn/zhouzh/zhouzh.files/publication/icdm08b.pdf)). This is not a full implementation - it only loads an already trained model and performs inference. To train and export a model use [this](https://github.com/nikosgavalas/anomaly-detection-python) Python package.
2. Multivariate Gaussian ([paper](http://cs229.stanford.edu/section/gaussians.pdf)) - Batch and Stream.
3. Half-Space Trees ([paper](https://www.ijcai.org/Proceedings/11/Papers/254.pdf)) - Stream.
4. LODA (Lightweight Online Detector of Anomalies) ([paper](https://link.springer.com/content/pdf/10.1007/s10994-015-5521-0.pdf)) - Stream.
