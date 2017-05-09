# Distributed System Design for Deep Learning

Here, The materials are mainly about **Distributed Deep Learning/Machine Learning Systems Design**. Also, you want to learn more about distributed systems(e.g. Courses, Storage, Messaging systems), an awesome collection is [here](https://github.com/theanalyst/awesome-distributed-systems).

[toc]

## Bootcamp
Readings before you start. Definitely, Rome was not built in a day. 

### Popular Frameworks
* [Tensorflow](https://www.tensorflow.org) - Detailed tutorial, friendly to Newbie.
* [MXNet](https://github.com/dmlc/mxnet) - Efficiency and flexibility. Dynamic dependency scheduler + graph optimization.
* [Pytorch](http://pytorch.org) - Put `Python` first.
* [Caffe2](https://github.com/caffe2/caffe2) - 

### Landmark Paper
* [Tensorflow](https://arxiv.org/abs/1603.04467)
* [MXNet](https://arxiv.org/abs/1512.01274)
* [Parameter Server](https://www.usenix.org/system/files/conference/osdi14/osdi14-paper-li_mu.pdf)

### Recommanded Blogs
* [Distributed Deep Learning: An Introduction](http://engineering.skymind.io/distributed-deep-learning-part-1-an-introduction-to-distributed-training-of-neural-networks)

### Influential Books
* [Principles of Distributed Systems](http://dcg.ethz.ch/lectures/podc_allstars/lecture/podc.pdf) [ETH Zurich University]
* [Deep Learning](http://www.deeplearningbook.org) [An MIT Press book]


## Architecture Design

* [NNVM](https://github.com/dmlc/nnvm) By [Tianqi Chen](http://homes.cs.washington.edu/~tqchen/) - Co-author of MXNet

A modular, decentralized and lightweight part to help build deep learning libraries.

* [Weld - LLVM](https://weld-project.github.io) By [Matei Zaharia](https://cs.stanford.edu/~matei/)  - Co-author of Spark

A runtime for data analytics applications that changes the **interface** between software libraries to enable powerful cross-library optimizations. 


## Optimization

## Memory Design
* [Training Deep Nets with Sublinear Memory Cost](https://arxiv.org/abs/1604.06174) **Trade computation for memory** - giving a more memory efficient training algorithm with a little extra computation cost.
 
* [Memory-Efficient Backpropagation Through Time](http://papers.nips.cc/paper/6221-memory-efficient-backpropagation-through-time) [NIPS 2016] Reduce memory consumption for backpropagation through time (BPTT) algorithm in RNNs.

## Network Design
* RDMA-based 

