# Convex Optimization Course Project Materials

This repo contains project definition and implementations for Convex Optimization Course. Currently, just the Persian version of the project definition is available.

- Course Name: Convex Optimization
- Course Number: CE-40837
- Instructor: Dr. Mahdi Jafari Siavoshani
- Institute: Sharif University of Technology
- Semester: Spring 2020
- Author: Erfan Loghmani


The project asks students to investigate two main areas in convex optimization. First, second-order methods such as the newton method and natural gradient. And second, variance reduction techniques like mini-batch SGD and SVRG.

## Second-order methods
In this part, students have to implement & compare following algorithms:
- Gradient Descent
- Newton Method
- Natural Gradient Method

Then evaluate them on a simple classification problem with artificially generated data. They also have to check the effect of reparametrization on each algorithm.


## Variance reduction
In this part, students should implement & compare on these algorithms:
- Stochastic Gradient Descent
- Mini-batch Stochastic Gradient Descent
- SVRG (Stochastic Variance Reduced Gradient)

Also, evaluate them on learning multi-class classification for the MNIST dataset. They have to evaluate the results based on loss decay, accuracy, and variance.

## Implementations
Implementations are available in the `code` directory.

To install requirements use `pip install -r requirements.txt`.

You can also find implementations in colab:

- [Second-order methods](https://colab.research.google.com/drive/1b7PgpI-ZpczfCyPZtvCnqJHZoaKDjBUR?usp=sharing)
- [Variance reduction](https://colab.research.google.com/drive/1AiCVsJLRfxRY6pu0aQd9T6lXssvD-uoY?usp=sharing)
