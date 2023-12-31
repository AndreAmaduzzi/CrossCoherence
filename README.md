# Looking at words and points with attention: a benchmark for text-to-shape coherence <br /> (ICCV 2023 Workshop "AI for 3D Content Creation")

![image](https://github.com/AndreAmaduzzi/CrossCoherence/blob/main/readme_pics/teaser.png?raw=true)

## Dataset GPT2Shape
Train-val-test splits of GPT2Shape dataset can be found in folder gpt2shape:
* [train](gpt2shape/train.csv)
* [val](gpt2shape/val.csv)
* [test](gpt2shape/test.csv)

Each CSV file contains the ShapeNet model_id of every shape, the corresponding textual description, the name and id of the category and other metadata.

## Installation

## Evaluation metric CrossCoherence - inference
### Inference 

## Evaluation metric CrossCoherence - training
### Training

## Human-validated test set HST


## Citation
If you find this work useful, please cite our paper:
```
@InProceedings{Amaduzzi_2023_ICCV,
    author    = {Amaduzzi, Andrea and Lisanti, Giuseppe and Salti, Samuele and Di Stefano, Luigi},
    title     = {Looking at Words and Points with Attention: a Benchmark for text-to-Shape Coherence},
    booktitle = {Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV) Workshops},
    month     = {October},
    year      = {2023},
    pages     = {2868-2877}
}