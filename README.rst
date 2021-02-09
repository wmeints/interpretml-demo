Fairlearn demo
===============
Welcome to this repository. In this repository you'll find a demonstration of some of the capabilities that `fairlearn`_ offers.

.. contents:: We'll cover the following topics in this README:

The importance of explainers and interpretable models
-----------------------------------------------------

When we build machine learning models we're building something that's a pretty-much a blackbox.
Usually you get good results when you've got a good dataset and trained the model with enough samples.
However, there are cases where machine learning models have produced good results for the wrong reasons.
In other cases machine learning models produced completely wrong results.

At Info Support we believe that it is important to be able to pull open the blackbox and explain what 
machine learning models do. There can be one of three reasons why you would want to use a model 
explainer or an interpretable model:

* You're required by law to show that the model works correctly.
* You want to demonstrate to your client that the model works as expected.
* You want to get a better understanding why a model produced the wrong results.

InterpretML is a library that helps you provide explanations for models and build interpretable models.

What does this repository demonstrate?
---------------------------------------

In this repository you'll find two notebooks:

* :code:`notebooks/interpretable-model.ipynb` - Shows how to train an interpretable model.
* :code:`notebooks/explainers.ipynb` - Shows how to generate an explainer for a model.

Please check the description in the notebooks to get a better understanding of the 
difference between interpretable models and explainers.

System requirements
--------------------
To run this demo, you'll need:

* `Python 3.8`_ 
* Windows 10, Mac OS, or Linux

Running the demo code
----------------------
Follow these steps to run the code:

1. First, install the requirements for the notebooks: :code:`pip install -r requirements.txt`
2. Next, start jupyter notebooks from the root of the repository: :code:`jupyter notebook`

The notebooks are located in the :code:`notebooks` folder. You can execute 
the notebooks out of order.

We recommend using a virtual environment for this demo.

.. _`Python 3.8`: https://www.python.org/downloads/release/python-386/
