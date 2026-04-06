# PyTorch Fashion-MNIST Classifier

A simple feedforward neural network built with PyTorch that classifies clothing images from the Fashion-MNIST dataset into 10 categories.

## Categories

T-shirt/Top, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot

## Setup

```bash
python3 -m venv venv
source venv/bin/activate
pip install torch torchvision
```

## Usage

Load and explore the dataset:
```bash
python3 datasets.py
```

View the model architecture:
```bash
python3 neural_networks.py
```

Train the model:
```bash
python3 optimize_models.py
```

## Model

- 3-layer feedforward network (784 → 512 → 512 → 10)
- ReLU activations
- Adam optimizer
- CrossEntropy loss
- Achieves ~88% accuracy after 15 epochs
