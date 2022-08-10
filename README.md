# Learning event representations for temporal segmentation of image sequences by dynamic graph embedding
The repository contains our results and PyTorch code for the proposed algorithm described in our IEEE TIP 2021 [paper](https://upcommons.upc.edu/bitstream/handle/2117/343742/2389-Learning-event-representations-for-temporal-segmentation-of-image-sequences-by-dynamic-graph-embedding.pdf?sequence=1).

## <sub> Abstract </sub>
Recently, self-supervised learning has proved to be
effective to learn representations of events suitable for temporal
segmentation in image sequences, where events are understood
as sets of temporally adjacent images that are semantically
perceived as a whole. However, although this approach does not
require expensive manual annotations, it is data hungry and
suffers from domain adaptation problems. As an alternative,
in this work, we propose a novel approach for learning event
representations named Dynamic Graph Embedding (DGE). The
assumption underlying our model is that a sequence of images
can be represented by a graph that encodes both semantic and
temporal similarity. The key novelty of DGE is to learn jointly
the graph and its graph embedding. At its core, DGE works by
iterating over two steps: 1) updating the graph representing the
semantic and temporal similarity of the data based on the current
data representation, and 2) updating the data representation
to take into account the current data graph structure. The
main advantage of DGE over state-of-the-art self-supervised
approaches is that it does not require any training set, but
instead learns iteratively from the data itself a low-dimensional
embedding that reflects their temporal and semantic similarity.
Experimental results on two benchmark datasets of real image
sequences captured at regular time intervals demonstrate that
the proposed DGE leads to event representations effective for
temporal segmentation. In particular, it achieves robust temporal
segmentation on the EDUBSeg and EDUBSeg-Desc benchmark
datasets, outperforming the state of the art. Additional experi-
ments on two Human Motion Segmentation benchmark datasets
demonstrate the generalization capabilities of the proposed DGE.
#


#
![DGE_graphModel](https://user-images.githubusercontent.com/50593288/135725077-c7a743d5-905b-4424-bb29-b368fa6faebe.jpg)


## Citation

```js
@article{dimiccoli2020learning,
  title={Learning event representations for temporal segmentation of image sequences by dynamic graph embedding},
  author={Dimiccoli, Mariella and Wendt, Herwig},
  journal={IEEE Transactions on Image Processing},
  volume={30},
  pages={1476--1486},
  year={2020},
  publisher={IEEE}
}
