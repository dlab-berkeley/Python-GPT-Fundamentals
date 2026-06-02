# D-Lab's GPT Fundamentals in Python Workshop

[![DataHub](https://img.shields.io/badge/launch-datahub-blue)](http://dlab.datahub.berkeley.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fdlab-berkeley%2FPython-GPT-Fundamentals&urlpath=lab%2Ftree%2FPython-GPT-Fundamentals%2F)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dlab-berkeley/Python-GPT-Fundamentals/HEAD)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

This repository contains the materials for D-Lab's GPT Fundamentals workshop. 

## Prerequisites
No technical background is required, but we recommend attending [Python Fundamentals](https://github.com/dlab-berkeley/Python-Fundamentals) prior to this workshop in order to understand running Python code cells in Jupyter notebooks.

Check out D-Lab’s [Workshop Catalog](https://dlab-berkeley.github.io/dlab-workshops/) to browse all workshops, see what’s running now, and review prerequisites.

## Workshop Goals

This workshop offers a general introduction to the GPT (Generative Pretrained Transformers) model. We will explore the transformer architecture upon which GPT models are built, how transformer models encode natural language into embeddings, and how GPT predicts text.

## Learning Objectives

After this workshop, you will be able to:

* Understand what makes the "magic" of GPT and Large Language Models (LLMs) possible via foundational concepts of word embeddings and the transformer architecture.
* Get an intuition of word embeddings as numbers projected in vector space. 
* Distinguish components of the self-attention mechanism in transformer models.
* Adjust hyperparameters of GPT models to control output randomness. 
* Understand how geometric similarity approaches can be used to represent similarity between words.

This workshop does **not** cover the following:

* Prompt Engineering.
* RLHF finetuning.
* Working with the OpenAI API.
* The fundamentals of Python. See the list of workshops at the bottom of this page to get a better grasp of the Python language used in this workshop.

## Installation Instructions

We will use Python to go through the workshop materials. Complete the following steps:

1. Install the [Anaconda](https://www.anaconda.com/download) distribution of Python on your machine.
2. Download these workshop materials:
    * Click the green "Code" button in the top right of the repository information.
    * Click "Download Zip".
    * Extract this file to a folder on your computer where you can easily access it (we recommend Desktop).
3. Optional: if you’re familiar with git, you can instead clone this repository by opening a terminal and entering `git clone https://github.com/dlab-berkeley/Python-GPT-Fundamentals.git`

### Minimum Specifications:
* Processor: At least a modern quad-core processor (i5 or i7). More cores are beneficial for parallel processing.
* RAM: 8 GB is the bare minimum, but 16 GB or more is recommended, especially for larger models.
* Storage: SSD (Solid State Drive) is preferred for faster data reading and writing.
* Operating System: Linux or Windows with Python environment set up.

### Ideal Specifications:
* Processor: High-end i7 or i9, or an equivalent AMD Ryzen processor.
* RAM: 16 GB or more.
* GPU: A dedicated GPU with CUDA support is highly beneficial. Models like NVIDIA RTX 2060 or better can significantly speed up computation. The larger the model, the more VRAM is needed. * For the largest GPT-2 model, a GPU with at least 8 GB of VRAM is recommended.
* Storage: SSD with sufficient space for the model and your datasets.


## Is Python not Working on Your Computer?

If you do not have Python installed and the materials loaded on your
workshop by the time it starts, we *strongly* recommend using the UC Berkeley
Datahub to run the materials for these lessons. You can access the DataHub by
clicking the following button:

[![DataHub](https://img.shields.io/badge/launch-datahub-blue)](http://dlab.datahub.berkeley.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fdlab-berkeley%2FPython-GPT-Fundamentals&urlpath=lab%2Ftree%2FPython-GPT-Fundamentals%2F)

The DataHub downloads this repository, along with any necessary packages, and
allows you to run the materials in an RStudio instance on UC Berkeley's servers.
No installation is necessary from your end - you only need an internet browser
and a CalNet ID to log in. By using the DataHub, you can save your work and come
back to it at any time. When you want to return to your saved work, just go
straight to the [D-Lab DataHub](https://dlab.datahub.berkeley.edu), sign in, and
you click on the `Python-GPT-Fundamentals` folder.

If you don't have a Berkeley CalNet ID, you can still run these lessons in the cloud, by clicking this button:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dlab-berkeley/Python-GPT-Fundamentals/HEAD)

By using this button, however, you cannot save your work.

# Other D-Lab Python Workshops

Here are other Python workshops offered by the D-Lab:

## Introductory Workshops

* [Python Fundamentals](https://github.com/dlab-berkeley/Python-Fundamentals)
* [Python Intermediate](https://github.com/dlab-berkeley/Python-Intermediate) 
* [Python Data Wrangling](https://github.com/dlab-berkeley/Python-Data-Wrangling)
* [Python Data Visualization](https://github.com/dlab-berkeley/Python-Data-Visualization)
* [Python Geospatial Fundamentals](https://github.com/dlab-berkeley/Geospatial-Data-and-Mapping-in-Python)

## Advanced Workshops

* [Python Web Scraping and APIs](https://github.com/dlab-berkeley/Python-Web-Scraping)
* [Python Machine Learning](https://github.com/dlab-berkeley/Python-Machine-Learning)
* [Python Text Analysis](https://github.com/dlab-berkeley/Python-Text-Analysis)
* [Python Deep Learning](https://github.com/dlab-berkeley/Python-Deep-Learning)


# About the UC Berkeley D-Lab

D-Lab works with Berkeley faculty, research staff, and students to advance data-intensive social science and humanities research. Our goal at D-Lab is to provide practical training, staff support, resources, and space to enable you to use R for your own research applications. Our services cater to all skill levels and no programming, statistical, or computer science backgrounds are necessary. We offer these services in the form of workshops, one-to-one consulting, and working groups that cover a variety of research topics, digital tools, and programming languages.  

Visit the [D-Lab homepage](https://dlab.berkeley.edu/) to learn more about us. You can view our [calendar](https://dlab.berkeley.edu/events/calendar) for upcoming events, learn about how to utilize our [consulting](https://dlab.berkeley.edu/consulting) and [data](https://dlab.berkeley.edu/data) services, and check out upcoming [workshops](https://dlab.berkeley.edu/events/workshops).

# Contributors

Tom van Nuenen

Renata Barreto
