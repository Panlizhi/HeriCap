# Hierarchical Encoder-decoder for Image Captioning (HeriCap)

## Introduction
The official repository for “HeriCap”.

HeriCap is a model to  .

<p align="center">
    <img src="img/overview.png" width="95%"> <br>
    The framework of the proposed Dynamic Transformer Network (DTNet) 
</p>


<p align="center">
    <img src="img/cell.png" width="95%"> <br>
    The detailed architectures of different cells in the spatial and channel routing space.
</p>

## News

- 2025.12.24: Released code

## Environment setup

Please refer to [meshed-memory-transformer](https://github.com/aimagelab/meshed-memory-transformer)

## Data preparation
* **Annotation**.
* **Feature**. 
* **evaluation**. 


## Training
```python
python train.py  
```
## Evaluation
```python
python eval.py  
```

## Performance

<p align="center">
    <img src="img/performance.png" width="55%"> <br>
    Comparisons with SOTAs on the Karpathy test split.
</p>


## Qualitative Results

<p align="center">
    <img src="img/vis.png" width="75%"> <br>
    Examples of captions generated by Transformer and DTNet.
</p>


<p align="center">
    <img src="img/path_number.png" width="55%"> <br>
    Images and the corresponding number of passed cells.
</p>

<p align="center">
    <img src="img/path_vis.png" width="75%"> <br>
    Path Visualization.
</p>


## Acknowledgements
- Thanks the [meshed-memory-transformer](https://github.com/aimagelab/meshed-memory-transformer).
- Thanks the amazing work of [grit](https://github.com/davidnvq/grit). 

## Citations
```
```

