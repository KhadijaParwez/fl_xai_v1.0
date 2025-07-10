# Federated Learning for Medical Image Classification with Explainable AI

## 🚀 Features

- **Multiple Training Approaches**: Traditional centralized, federated learning, and individual client training
- **Medical Datasets Support**: Leukemia, Oral Cancer, Lymphoma, and HIV image classification
- **Explainable AI**: SHAP, LIME, GradCAM, GradCAM++, and other interpretation methods
- **Privacy Protection**: Image encryption/decryption capabilities
- **Comprehensive Evaluation**: Model performance metrics and visualization tools

## 📋 Requirements

```bash
tensorflow
keras
numpy
pandas
matplotlib
scikit-learn
lime
shap
tf-keras-vis
ipywidgets
xplique
plotly
opencv-python
scikit-image
```

## 🎯 Supported Datasets

1. **Leukemia (C-NMC)**: Binary classification (ALL vs HEM)
2. **Oral Cancer**: Binary classification (Normal vs Infected)
3. **Lymphoma**: Multi-class classification (CLL, FL, MFL)
4. **HIV**: Medical imaging classification


## 🔧 Configuration

### Training Parameters
- `epochs`: Number of training epochs
- `batch_size`: Batch size for training
- `data_split_ratio`: Train/validation split ratio

### Federated Learning Parameters
- `iterations`: Number of federated rounds
- `num_clients`: Number of participating clients
- `num_edge_servers`: Number of edge servers
- `local_model_epochs`: Local training epochs per client

## 📊 Training Methods

### 1. Simple (Centralized)
Traditional centralized training on combined dataset

### 2. Traditional Federated Learning
Standard federated approach

### 3. Our Federated Learning
Novel federated learning approach

### 4. Individual Clients
Train separate models for each client

## 🔍 Explainable AI Features

- **SHAP**: SHapley Additive exPlanations
- **LIME**: Local Interpretable Model-agnostic Explanations
- **GradCAM**: Gradient-weighted Class Activation Mapping
- **GradCAM++**: Improved version of GradCAM
- **Saliency Maps**: Feature importance visualization
- **Integrated Gradients**: Attribution method for deep networks

## 🔒 Privacy Features

- Image encryption/decryption using random keys
- Secure model aggregation in federated settings
- Privacy-preserving evaluation metrics

## 📈 Evaluation Metrics

- **Model Performance**: Accuracy, Precision, Recall, F1-score
- **XAI Metrics**: Fidelity, Sensitivity, Stability
- **Federated Metrics**: Communication efficiency, convergence analysis

## 📄 Output

The system generates:
- Trained models for each approach
- Performance evaluation reports
- XAI explanation visualizations
- PDF reports with detailed analysis
- Confusion matrices and performance plots


## 📧 Contact

For questions or collaborations, please reach out through GitHub issues.

## 🙏 Acknowledgments

- TensorFlow and Keras teams for deep learning frameworks
- SHAP and LIME libraries for explainable AI
- Medical imaging dataset providers
- Federated learning research community
