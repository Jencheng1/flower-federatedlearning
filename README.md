
# Flower Federated Learning with PyTorch

This repository contains introductory examples and strategies for implementing Federated Learning (FL) using [Flower](https://flower.dev/), a flexible framework for Federated Learning research and deployment, with PyTorch.

## Overview

Federated Learning is a decentralized approach to machine learning that allows models to be trained on data located across multiple devices or servers without centralizing the data itself. This repository demonstrates how to use Flower with PyTorch to train models in a federated setting.

The content is divided into two primary sections:

1. **Introduction to Federated Learning with PyTorch**:
   - This notebook provides a foundational understanding of Federated Learning using PyTorch and Flower. It walks through the setup of a basic federated learning environment, enabling multiple clients to collaboratively train a model without sharing their data.

2. **Federated Learning Strategies with PyTorch**:
   - This notebook delves into various federated learning strategies using Flower and PyTorch, exploring different approaches to enhance the federated training process. Strategies include FedAvg, FedProx, and others, each designed to address specific challenges in federated settings.

## Prerequisites

- Python 3.8 or later
- PyTorch
- Flower (Installation: `pip install flwr`)

Refer to the [requirements.txt](requirements.txt) file for additional dependencies.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/Jencheng1/flower-federatedlearning.git
   cd flower-federatedlearning
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Introduction to Federated Learning with PyTorch**:
   - Open the `Flower_1_Intro_to_FL_PyTorch.ipynb` notebook and follow the instructions to learn the basics of Federated Learning.

2. **Federated Learning Strategies with PyTorch**:
   - Open the `Flower_2_Strategies_in_FL_PyTorch.ipynb` notebook to explore advanced federated learning strategies and understand their impact on the training process.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

[MIT License](https://opensource.org/licenses/MIT)

## Contributing

Feel free to open issues or submit pull requests if you would like to contribute to the project.
