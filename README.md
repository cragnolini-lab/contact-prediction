# Contact Prediction

## BBK UoL, MSc Bioinformatics - Contact prediction for IDP-complexes

MSc project that intends to fine-tune the ESM-2 transformer model for unsupervised contact prediction in intrinsically disordered protein complexes. The project will focus on the mismatch repair protein system MutL and its associated partners.

## Getting started

Install dependencies in requirements in `requirements.txt`. It is recommended to create a virtual env to host the dependencies.

## Metrics logging

The project log training and memory usage metrics to the `runs` directory. Metrics are logged as TFEvents and can be seen using [Tensorboard](https://www.tensorflow.org/tensorboard). To launch Tensorboard, run `tensorboard --logdir=runs/<run name>`.

## Maintainers

Anugerah Erlaut - aerlau01@student.bbk.ac.uk