# Non-English-NLP-Tutorial

## About

These Jupyter notebooks contain tutorials and sample code for preforming analysis on non-English texts using Natural Language Processing methods, including Python scripts to clean, analyze, and visualize text. These notebooks accompany a workshop offered by University of Texas Libraries. They were created by Ian Goodale, European Studies Librarian, and Madeline Goebel, Graduate Research Assistant for Global Studies Digital Projects.

## Installation

Install required dependencies:

```
pip3 install -r requirements
```

## Troubleshooting

This code uses Python 3 syntax. If you are running Python 3.8, you will need to modify the code in this tutorial in order to use Gensim for topic modeling. Uncomment the following lines in the topic modeling cell:

```python
import multiprocessing
from multiprocessing import Process, Queue

multiprocessing.set_start_method("fork")
```

## Scope

This tutorial is intentionally simple and introductory, and aims to offer users a jumping off point for further exploration of NLP and computational tools for use in text analysis and linguistic research. Due to the varied nature of NLP and text analysis work, there is no one size fits all approach to writing code for these projects; as such, you should be prepared to write your own code when performing any kind of work for your own research. Tasks such as training models for named entity recognition were omitted from this tutorial for simplicity’s sake, but should not be skipped when working on your own project. Notes accompany places in the code where such steps could be  performed to help guide you in your own work.
