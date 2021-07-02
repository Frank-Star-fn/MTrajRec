# MTrajRec
<p align="center">
<img src="img/intro.png" width="54%" height="80%">
<img src="img/model_framework.png" width="45%" height="50%">
</p>

## About
Source code of the KDD'21: [MTrajRec: Map-Constrained Trajectory Recovery via Seq2Seq Multi-task Learning](doc/KDD21_MTrajRec_Huimin.pdf)
## Requirements
* Python==3.6
* `pytorch==1.7.1`
* `rtree==0.9.4`
* `GDAL==2.3.3`
* `networkx==2.3`

## Usage
### Installation
#### Clone this repo:
```bash
git clone git@github.com:huiminren/MTrajRec.git
cd MTrajRec
```
#### Running
  `python multi_main.py`

#### Dataset
We provide sample data under data/.

Please note that the sample data is generated with the structure as the original data.

## Acknowledge
Thanks to [Sijie](https://github.com/sjruan/tptk) to support data preprocessing.
