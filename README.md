# Hybrid CNN-MLP for Predicting Daily Irrigation Water Amount

## Overview

This repository contains the implementation of a hybrid **CNN-MLP model** designed to predict the daily irrigation water amount required for greenhouse-grown plants. This work leverages climate and environmental data collected from a greenhouse to optimize water usage while maintaining crop quality. The model utilizes **CNN for feature extraction** from minute-level climate data and **MLP for predicting** daily irrigation needs.

### Features:

- Dimensionality reduction through Convolutional Neural Networks (CNNs)
- Predictive modeling using Multi-Layer Perceptron (MLP)
- Preprocessing of greenhouse climate data
- Code for training, validation, and testing the model

## Requirements

To run the project, you will need the following Python libraries:

- `TensorFlow`
- `Keras`
- `NumPy`
- `Pandas`
- `Matplotlib`

## Usage

### Data Preparation:

Prepare your data by organizing it into two datasets:

- Minute-level climate data for feature extraction (used by CNN).
- Daily irrigation data used for training the MLP.

Make sure to structure your data similar to the example provided in the `data/` folder.

### Viewing the Models Details:

Run the following command to train the model:

```bash
python Hybrid_CNN_LSTM.ipynb
```

## Results

The model outputs daily irrigation water predictions along with evaluation metrics (e.g., Mean Absolute Error, Root Mean Squared Error). A detailed comparison of predicted vs actual irrigation amounts is provided in the `results/` folder.

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute the code for **non-commercial** purposes. If you use this code in your research, please cite this repository. -Will be licensed soon--

## Disclaimer

This repository is provided for **research and educational purposes**. For any commercial use, please contact the authors for permission. The model has been trained using data from a controlled greenhouse environment and may require further tuning for use in other environments or at scale.

## Contributing

If you would like to contribute to this project, please submit a pull request.

## Contact

For questions or collaboration inquiries, please contact Hamed Laouz at laouz.hamed@univ-biskra.dz.
