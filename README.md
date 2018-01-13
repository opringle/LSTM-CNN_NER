## Goal

[Implenting state of the art NN architecture from this paper](https://www.aclweb.org/anthology/Q16-1026) for the task of named entity recognition in MXNet.

## To do

- CNN feature generation/preprocessing
- Custom loss function: sentence level log likelihood (use ignore is potentially sufficient...)

[custom softmax allowing weighted labels](https://github.com/apache/incubator-mxnet/blob/v1.0.0/example/sparse/weighted_softmax_ce.py)
[gluon loss function example](http://gluon.mxnet.io/chapter05_recurrent-neural-networks/rnns-gluon.html)

- Train model to high standard on [small kaggle dataset](https://www.kaggle.com/abhinavwalia95/entity-annotated-corpus)
- Prove performance on real dataset after requesting access

## Dataset

- [Download the dataset](https://www.clips.uantwerpen.be/conll2003/ner.tgz)
- [Request access to Reuters Corpora](http://trec.nist.gov/data/reuters/reuters.html)
- Follow the instructions in the [README](https://www.clips.uantwerpen.be/conll2003/ner/000README) to generate training files

## [State of the art](https://aclweb.org/aclwiki/CONLL-2003_(State_of_the_art))




