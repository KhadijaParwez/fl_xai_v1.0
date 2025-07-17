# Federated Learning for Medical Image Classification with Explainable AI

**🚀 Features**
* **Multiple Training Approaches**: Traditional centralized, federated learning, and individual client training
* **Medical Datasets Support**: Leukemia, Oral Cancer, Lymphoma, and HIV image classification
* **Explainable AI**: SHAP, LIME, GradCAM, GradCAM++, and other interpretation methods
* **Privacy Protection**: Image encryption/decryption capabilities
* **Comprehensive Evaluation**: Model performance metrics and visualization tools

## 🐳 Quick Start with Docker

### Prerequisites
- Docker installed on your system
- At least 8GB of available RAM

### Run from Docker Hub

Visit the Docker Hub repository: **[khadijaparwez/lukemia-lukemia-notebook](https://hub.docker.com/r/khadijaparwez/lukemia-lukemia-notebook)**

Pull the pre-built image:

```bash
docker pull khadijaparwez/lukemia-lukemia-notebook
```

Run the pre-built image with the following command:

```bash
docker run -p 8888:8888 khadijaparwez/lukemia-lukemia-notebook
```

### Accessing the Notebook
1. After the container starts, look for the Jupyter token in the output
2. Open your browser and navigate to `http://localhost:8888`
3. Enter the token when prompted, or use the full URL with token provided
4. Navigate to the main notebook file to start using the federated learning system

## 🎯 Supported Datasets
1. **Leukemia (C-NMC)**: Binary classification (ALL vs HEM)
   
## 🔧 Configuration

### Training Parameters
* `epochs`: Number of training epochs
* `batch_size`: Batch size for training
* `data_split_ratio`: Train/validation split ratio

### Federated Learning Parameters
* `iterations`: Number of federated rounds
* `num_clients`: Number of participating clients
* `num_edge_servers`: Number of edge servers
* `local_model_epochs`: Local training epochs per client

## 📊 Training Methods

### 1. Simple (Centralized)
Traditional centralized training on combined dataset

## 🔍 Explainable AI Features
* **SHAP**: SHapley Additive exPlanations
* **LIME**: Local Interpretable Model-agnostic Explanations
* **GradCAM**: Gradient-weighted Class Activation Mapping
* **GradCAM++**: Improved version of GradCAM
* **Saliency Maps**: Feature importance visualization
* **Integrated Gradients**: Attribution method for deep networks

## 📈 Evaluation Metrics
* **Model Performance**: Accuracy, Precision, Recall, F1-score
* **XAI Metrics**: Fidelity, Sensitivity, Stability
* **Federated Metrics**: Communication efficiency, convergence analysis

## 📄 Output
The system generates:
* Trained models for each approach
* Performance evaluation reports
* XAI explanation visualizations
* PDF reports with detailed analysis
* Confusion matrices and performance plots



## 📧 Contact
For questions or collaborations, please reach out through GitHub issues.

## 🙏 Acknowledgments
* TensorFlow and Keras teams for deep learning frameworks
* SHAP and LIME libraries for explainable AI
* Medical imaging dataset providers
* Federated learning research community
