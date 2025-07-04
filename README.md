# Automatic Piano Music Generation Using RNNs and GANs

Automatic music generation is an emerging field within artificial intelligence and machine learning. By leveraging various techniques such as Recurrent Neural Networks (RNNs) and Generative Adversarial Networks (GANs), it is possible to develop models capable of autonomously creating musical compositions.

## Project Overview

This project explores the use of **RNNs** and **GANs** to generate piano music based on a dataset of MIDI files, specifically the **MAESTRO** dataset.

The process begins with the **extraction of MIDI files** from MAESTRO, which contains high-quality piano recordings. These MIDI files are then **converted into dataframes** that represent musical notes and their characteristics in a structured format. Using these dataframes, neural network models are trained with the objective of **predicting the next note in a musical sequence**. This approach allows the model to learn temporal sequence patterns and relationships between notes over time, enabling it to generate new compositions based on learned data.

Beyond RNNs, which excel at modeling temporal sequences, the project incorporates a **Generative Adversarial Network (GAN)**. GANs improve the quality of generated music through a competitive process between a generator and a discriminator, enhancing the generator’s ability to produce increasingly realistic notes. Specifically, the **MuseGAN architecture** is used, which can generate multi-track music compositions with different voices, harmonies, or instruments simultaneously. Unlike autoregressive RNNs, MuseGAN does not rely on an autoregressive structure but instead generates entire sequences from a latent vector.

## Objective

The project presents an approach for automatic creation of musical compositions that preserve the structure and dynamics of piano music. It is primarily a basic exploration comparing autoregressive generative models and a GAN, trained on piano MIDI files to produce new musical pieces.
