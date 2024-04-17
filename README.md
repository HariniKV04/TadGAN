# TadGAN

TadGAN, an unsupervised anomaly detection approach built on Generative
Adversarial Networks (GANs). To capture the temporal correlations of time series
distributions, we use LSTM Recurrent Neural Networks as base models for
Generators and Critics. TadGAN is trained with cycle consistency loss to allow for
effective time-series data reconstruction. It uses several methods to compute
reconstruction errors, as well as different approaches to combine reconstruction
errors and Critic outputs to compute anomaly scores.
Time-series data often contain complex temporal correlations that traditional
anomaly detection methods struggle to capture effectively. In this paper, we propose
TadGAN, an unsupervised anomaly detection approach built on Generative
Adversarial Networks (GANs). TadGAN leverages the power of LSTM Recurrent
Neural Networks as base models for both Generators and Critics to effectively
capture the temporal dependencies present in time series data.
Central to TadGAN's effectiveness is its utilisation of cycle consistency loss during
training, which enables robust reconstruction of time-series data. By employing
LSTM-based Generators and Critics, TadGAN learns to generate realistic data
samples while simultaneously discerning anomalies from normal patterns.
Furthermore, TadGAN introduces multiple methods for computing reconstruction
errors, allowing for comprehensive evaluation of data fidelity. Additionally, it explores
various strategies for combining reconstruction errors with Critic outputs to compute
anomaly scores, enabling flexible adaptation to different anomaly detection tasks.
