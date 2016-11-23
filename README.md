# Memory Networks

This project contains implementations of memory networks.
This includes code in the following subdirectories:


* [MemN2N-lang-model](MemN2N-lang-model): This code trains MemN2N model for language modeling, see Section 5 of the paper "[End-To-End Memory Networks](http://arxiv.org/abs/1503.08895)". This code is implemented in [Torch7](http://torch.ch/) (written in Lua); more documentation is given in the README in that subdirectory.
 

* [MemN2N-babi-matlab](MemN2N-babi-matlab): The code for the MemN2N bAbI task experiments of Section 4 of the paper:

     [S. Sukhbaatar, A. Szlam, J. Weston, R. Fergus. End-To-End Memory Networks. arXiv:1503.08895](http://arxiv.org/abs/1503.08895).
 
  This code is implemented in Matlab; more documentation is given in the README in that subdirectory.

* [DBLL](DBLL): Code to train MemN2N on tasks from the paper "[Dialog-based Language Learning](https://arxiv.org/abs/1604.06045)". This code is implemented in [Torch7](http://torch.ch).

### Other 3rd party implementations
* [python-babi](https://github.com/vinhkhuc/MemN2N-babi-python): MemN2N implemenation on bAbI tasks with very nice interactive demo.
* [theano-babi](https://github.com/npow/MemN2N): MemN2N implementation in Theano for bAbI tasks.
* [tf-lang](https://github.com/carpedm20/MemN2N-tensorflow): MemN2N language model implementation in TensorFlow.
* [tf-babi](https://github.com/domluna/memn2n): Another MemN2N implementation of MemN2N in TensorFlow, but for bAbI tasks.
