
# Forked from: Steerable discovery of neural audio effects 

[Original Repository](https://csteinmetz1.github.io/steerable-nafx)

```bibtex
@inproceedings{steinmetz2021steerable,
        title={Steerable discovery of neural audio effects},
        author={Steinmetz, Christian J. and Reiss, Joshua D.},
        booktitle={5th Workshop on Creativity and Design at NeurIPS},
        year={2021}}
```

This forked repository contains:

[00 - Dataset Analysis](00-DatasetAnalysis.ipynb)
An analysis of the dataset, with plots, statistics, and the audio feature extraction to create the metadata.

[01 - Pre-Processing](01-PreProcessing.ipynb)
This is the pipeline to convert a subset of the dataset into audio file in order to be used with the baseline model.

[02 - Training Comparison](02-TrainingComparison.ipynb)
First training of the baseline model with different parameters and the converted subset of the Spring Reverb dataset.

[03 - Spring Dataset](03-SpringDataset.ipynb)
The Pytorch class to load the Spring Reverb dataset and some analysis of the loaded data as verification of the correct loading. 

[04 - Testing the Baseline](04-TestingBaseline.ipynb)
Testing the baseline model with the Spring Reverb dataset, no conversion to wav, the entire dataset is used and an evaluation of the results is performed.