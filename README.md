# Particle-Classification

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ZOetULDi39aUoogFDGE0BjoyqdtuRM6t?usp=sharing)

**Problem statement**: Classification of particles (either photons or electrons) based on the data gathered from one of the detectors (the Electromagnetic Calorimeter or ECAL) used as a camera.

**Dataset**: Each pixel in the image corresponds to a detector cell, while the intensity of the pixel corresponds to how much energy is measured in that cell. Timing of the energy deposits are also available, though this may or may not be relevant. The dataset contains 32x32 Images of the energy hits and their timing (channel 1: hit energy and channel 2: its timing) in each calorimeter cell (one cell = one pixel) for the two classes of particles: Electrons and Photons. The dataset contains around four hundred thousand images for electrons and photons. Please note that your final model will be evaluated on an unseen test dataset.
