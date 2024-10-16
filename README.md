# Deep Learning Network

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction

This Repoisitory contains a segmentation network that intitialy tracks and then creates the segmentation result from the tracking result. 

## Features

- **Feature 1**: Combines tracking and segmentation.
- **Feature 2**: Utilizes discriminative loss in the model predictor to increase discriminative functionality of tracking part.
- **Feature 3**: Segmentation part consist of refinement modules to increase pixel wise acuracy.

## Installation

### Prerequisites

List any prerequisites that need to be installed for your project. For example:

- Python 3
- pip
- PyTorch

### Installing

Provide step-by-step instructions on how to install your project. For example:

```bash
# Clone the repository
git clone https://github.com/your-username/your-repo-name.git

# Navigate to the project directory
cd ./Network_Git

# Install the required packages
pip install -r requirements.txt

### Quick run

cd ./pytracking/ltr
python3 run_training.py dimp dimp_merged


