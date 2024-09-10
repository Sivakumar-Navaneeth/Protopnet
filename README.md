# ProtoPNet: Prototype Classification Network

This repository implements the **ProtoPNet** (Prototype Classification Network), a deep learning model that enhances interpretability by leveraging class-specific prototypes for image classification. ProtoPNet is a hybrid model combining the predictive power of CNNs with human-friendly, interpretable prototypes to explain the model’s decisions.

## Key Features

- **Prototype-based Interpretability**: The model uses class-specific prototypes to explain its classification decisions, making the decision process transparent and understandable.
- **CNN Backbone**: Utilizes a standard convolutional neural network (CNN) as a feature extractor.
- **Similarity Matching**: Calculates the similarity between input image patches and learned prototypes, guiding the classification decision.
- **Visualization**: Provides visualization of prototypes and the parts of the image that influenced the final decision.
