<h1 align="center">IBM Query Challenge </h1>
<p>
</p>

> Natural Language Processing of Search Queries
## About

This notebook classifies search queries according to their "topic" based on named entity recognition and explores features relevant to search optimization and UX design based on their grammaticality, length, and feature distribution.

## Install

```sh
git clone https://www.github.com/lorarjohns/ibm-query-nlp.git
```

## Usage

You can run the notebook by setting up an NLP environment with the Docker Compose cookiecutter available at [my GitHub repo](https://github.com/lorarjohns/cookiecutter_compose):

```sh
cookiecutter https://github.com/lorarjohns/cookiecutter_compose.git
```

But the easiest way to run this notebook may be to use the Docker container available at [this repo](https://github.com/ml-tooling/ml-workspace): 

```sh
docker run -p 8080:8080 mltooling/ml-workspace:latest
```

If not already installed, you'll need to install the spaCy pretrained word vectors from the command line. The easiest way to do so is by running:

```sh
spacy download en_core_web_lg
```

### Requirements and Packages:

- spaCy
- Keras/TensorFlow
- Seaborn
- numpy
- pandas

## Author

👤 **Lora Johns**

* Website: www.espritdecorpus.com
* Github: [@lorarjohns](https://github.com/lorarjohns)