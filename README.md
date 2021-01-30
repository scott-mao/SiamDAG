# SiamDAG


Our work is based on the open source code library [Trackit](https://github.com/researchmm/TracKit), and the related operations of the environment configuration are exactly the same. Thanks to the contributors of Trackit.

## Contributors 
- [Jian Huang](https://github.com/Huangggjian)



## How To Start
- Tutorial for **SiamDAG**

  Follow SiamDAG **[[Training and Testing]](https://github.com/researchmm/TracKit/blob/master/lib/tutorial/Ocean/ocean.md)** tutorial 



## Structure
- `experiments:` training and testing settings
- `demo:` figures for readme
- `dataset:` testing dataset
- `data:` training dataset
- `lib:` core scripts for all trackers
- `snapshot:` pre-trained models 
- `pretrain:` models trained on ImageNet (for training)
- `tutorials:` guidelines for training and testing
- `tracking:` training and testing interface

```
$TrackSeg
|—— experimnets
|—— lib
|—— snapshot
  |—— xxx.model/xxx.pth
|—— dataset
  |—— VOT2019.json 
  |—— VOT2019
     |—— ants1...
  |—— VOT2020
     |—— ants1...
|—— ...

```



## References
```
[1] Bhat G, Danelljan M, et al. Learning discriminative model prediction for tracking. ICCV2019.
[2] Chen, Kai and Wang, et.al. MMDetection: Open MMLab Detection Toolbox and Benchmark.
```
## Contributors of Trackit
- **[Zhipeng Zhang](https://github.com/JudasDie)**
- **[Houwen Peng](https://houwenpeng.com/)**
