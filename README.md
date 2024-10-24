# TU Wien: Deep Learning in Natural Language Processing

This repository includes a collection of exercises and lecture materials that I developed during my role as a teaching assistant for the [Deep Learning in Natural Language Processing (DL in NLP) course](https://tiss.tuwien.ac.at/course/courseDetails.xhtml?dswid=4514&dsrid=859&semester=2024W&courseNr=192039) at TU Wien. It covers various topics in NLP, emphasizing the challenges of practical implementation of the key concepts.


# Environment setup

This repository uses `poetry` to ensure reporoducibility.
Follow this steps to configure the environment:

1. Install [conda](https://www.anaconda.com/).
1. Install [poetry](https://python-poetry.org/).
1. `poetry config virtualenvs.create false`.
1. Create a conda environment with python>=3.11: `conda create -n pcax python=3.11`.
1. Activate the environment: `conda activate pcax`.
1. `cd` into the root pcax folder.
1. `poetry install --no-root`.
