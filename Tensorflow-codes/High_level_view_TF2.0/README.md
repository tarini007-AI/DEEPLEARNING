# TensorFlow 2.0 Overview

TensorFlow 2.0 is both simple and flexible, focusing on features like:
- Fast model design and high-level control with Keras
- Estimator API for machine learning workflows, with premade models for regression, boosted trees, and random forests
- Eager execution for imperative programming, with AutoGraph for taking advantage of graph execution
- SavedModel for exporting trained models and deploying on any platform
For our first lessons, we'll take a quick look at some MNIST examples with fully-connected and convolutional neural networks to get familiar with the core features of TensorFlow 2.0:

- **tf.keras:** A high-level, object-oriented API for fast prototyping of deep learning models
- **tf.GradientTape:** Records gradients on-the-fly for automatic differentiation and backprop
- **tf.function:** Pre-compile computational graphs from python functions with AutoGraph

# Fully-connected Network

For our first lesson, we'll train a fully-connected neural network for MNIST handwritten digit recognition. Let's start by setting up some methods to load MNIST from **keras.datasets** and preprocess them into rows of normalized 784-dimensional vectors.
