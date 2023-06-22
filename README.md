# Articulation Trainer
## Introduction

The Articulation Trainer project aims to help users improve their speech articulation and pronunciation skills. The project consists of several components that work together to provide a comprehensive training experience.

## Components

The Articulation Trainer project includes the following components:

- train.py: This script is responsible for training the articulation model using user data. It takes in audio recordings of users pronouncing specific words or phrases and uses them to train a machine learning model.
- keyword_spotting_service.py: This script provides a keyword spotting service. It takes an audio input and detects specific keywords or phrases related to articulation training. This service can be used for real-time feedback during practice sessions.
- prepare_datatest.py: This script generates specially curated sentences for testing and evaluating the user's articulation. These sentences are designed to include challenging phonetic combinations to help users identify and correct specific articulation errors.
