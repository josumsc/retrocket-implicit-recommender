# Implicit Recommender with ALS: The Rocket of Retail 🚀

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/josumsc/retrocket-implicit-recommender/blob/master/src/retrocket-implicit-recommender.ipynb)

When data is available, we can use it to build a recommender system based on the reviews left by our customers to
their favorite products. An example of this use case can be found at [this repository using the MovieLens dataset](
https://github.com/josumsc/movielens-recommender).

Nevertheless, we are often faced with the problem of building a recommender system without any explicit feedback from the
user, which is a common problem in the industry. Sometimes users are not able or willing to leave a  review, but are well
aware of their preferences. These preferences manifest by visiting the product page,  adding those products to our cart 
or purchasing the product.

In this notebook, we expect to give clarity to the use of these kind of datasets based on implicit feedback to build a
recommender system that can be used to enhance the user experience.

## Installation of the environment

You can follow up this notebook in your machine by downloading Anaconda and then running the following command in the terminal:
```python
conda env create --file retrocket-implicit-recommender.yml
```
This should have you prepared to run jupyter notebook in the terminal and then running the mentioned code using that familiar interface.

Please note that I've used a M1 Mac, so the installation might suffer from some problems if you are using a different CPU architecture. In those cases do not hesitate to look up information on the official sources such as PyPi to solve your occasional errors during the installation.

## References

- [Implicit Feedback Deep Collaborative Filtering Product Recommendation System](https://arxiv.org/abs/2009.08950)
- [Implicit Documentation](https://implicit.readthedocs.io/en/latest/als.html)
