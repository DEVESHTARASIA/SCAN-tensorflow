# SCAN in Tensorflow
A Tensorflow implementation of DeepMind's Symbol-Concept Association Network ([SCAN: Learning Abstract Hierarchical Compositional Visual Concepts](https://arxiv.org/abs/1707.03389)).

<p align="center">
	<img src="https://github.com/naturomics/SCAN-tensorflow/blob/master/assets/SCAN-model.png?raw=true" alt="SCAN model architecture"/>
</p>

# Usage

## Prerequisites

* Python 3.4
* DeepMind Lab
* [Tensorflow 1.2](https://github.com/tensorflow/tensorflow/tree/r1.2)

This is my configuration, other versions might work, too. If don't, let me know.
It is worth mentioning that [the origin deepmind lab repo](https://github.com/deepmind/lab) hasn't been updated for months, and it doesn't support python3. On the other hand, I'm used to work on my Gentoo Linux with Python3. In order to make it work, I have forked this repo to [my github](https://github.com/naturomics/lab) and make it Gentoo and python3 supportable. See [here]{https://github.com/naturomics/lab} for details.

## Instructions for runing
```shell
$ git clone https://github.com/naturomics/SCAN-tensorflow.git
$ cd SCAN-tensorflow
```

```shell
$ python main.py
```


# Contributing
Contributions are always welcome! Please read [CONTRIBUTING](CONTRIBUTING.md) for details.

# Author
Naturomics Liao - [@naturomics](https://github.com/naturomics)

# LICENSE
The Apache License. Please read [License File](LICENSE) for details.
