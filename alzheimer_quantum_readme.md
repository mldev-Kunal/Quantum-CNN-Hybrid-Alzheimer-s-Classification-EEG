# Alzheimer's Classification using Quantum-CNN Model Architecture with EEG Dataset

A novel quantum-classical hybrid CNN model for classifying Alzheimer's disease stages using EEG signal analysis. This project leverages quantum computing principles integrated with classical deep learning for enhanced pattern recognition in neurological data.

## Overview

This project implements a cutting-edge approach to Alzheimer's disease classification by combining:
- **Classical Convolutional Neural Networks** for feature extraction
- **Quantum Computing circuits** for advanced pattern processing
- **EEG signal analysis** for non-invasive neurological assessment

The hybrid architecture utilizes quantum circuits strategically placed between the flattening and dense layers to enhance the model's capability in detecting subtle neurological patterns.

## Technology Stack

- **PennyLane**: Open-source quantum computing simulation library
- **Python**: Primary programming language
- **TensorFlow/Keras**: Classical neural network components
- **MATLAB**: Dataset format and preprocessing
- **Quantum Computing**: Circuit-based pattern recognition

## Classification Categories

The model classifies patients into three distinct categories:

| Class | Description | Abbreviation |
|-------|-------------|--------------|
| **Alzheimer's Disease** | Patients diagnosed with AD | AD |
| **Mild Cognitive Impairment** | Patients with MCI symptoms | MCI |
| **Healthy Control** | Normal/healthy patients | HC |

## Model Architecture

### Hybrid Quantum-Classical Design
1. **Classical CNN Layers**: Initial feature extraction from EEG signals
2. **Flattening Layer**: Preparation for quantum processing
3. **Quantum Circuit**: Advanced pattern recognition using quantum gates
4. **Dense Layers**: Final classification processing

### Quantum Circuit Integration
- Positioned strategically between flattening and dense layers
- Utilizes quantum superposition and entanglement for enhanced feature processing
- Simulated using PennyLane's quantum computing framework

## Dataset

### EEG Signal Data
- **Format**: MATLAB (.mat) files
- **Signal Type**: Electroencephalography (EEG) recordings
- **Classes**: Three-class classification problem
- **Non-invasive**: Safe neurological data acquisition method

### Dataset Files
- `AD.mat` - EEG readings from Alzheimer's Disease patients
- `MCI.mat` - EEG readings from Mild Cognitive Impairment patients  
- `normal.mat` - EEG readings from healthy control subjects

## Files Overview

### Code & Implementation
- `*.ipynb` - Jupyter notebook with complete executed code and analysis

### Model Architecture
- `quantum_circuit (1).png` - Detailed diagram of the quantum circuit architecture

### Performance Evaluation
- `NCM_1.png` - Normalized confusion matrix showing classification accuracy
- `roc_curves.png` - ROC curves for multi-class performance evaluation

### Dataset
- `AD.mat` - Alzheimer's Disease patient EEG recordings
- `MCI.mat` - Mild Cognitive Impairment patient EEG recordings
- `normal.mat` - Healthy control patient EEG recordings

## Key Features

- ✅ **Quantum-Classical Hybrid**: Combines best of both computing paradigms
- ✅ **Non-invasive Diagnosis**: Uses EEG signals for safe patient assessment
- ✅ **Multi-class Classification**: Distinguishes between AD, MCI, and healthy patients
- ✅ **Open-source Implementation**: Built with PennyLane quantum computing library
- ✅ **Medical Application**: Real-world healthcare problem solving
- ✅ **Advanced Visualization**: Comprehensive performance metrics and analysis

## Getting Started

### Prerequisites
```bash
pip install pennylane
pip install tensorflow
pip install numpy
pip install matplotlib
pip install scikit-learn
pip install scipy
```

### Installation
1. Clone the repository
```bash
git clone https://github.com/yourusername/Alzhiemer's-classification-using-quantum-CNN-model-architecture-using-EEG-dataset.git
cd Alzhiemer's-classification-using-quantum-CNN-model-architecture-using-EEG-dataset
```

2. Install required dependencies
```bash
pip install -r requirements.txt
```

3. Run the Jupyter notebook
```bash
jupyter notebook *.ipynb
```

## Model Performance

The hybrid quantum-classical model demonstrates:
- **Multi-class Classification**: Effective discrimination between AD, MCI, and HC
- **Quantum Enhancement**: Improved pattern recognition through quantum circuits
- **Clinical Relevance**: Potential for early-stage Alzheimer's detection

### Evaluation Metrics
- **Confusion Matrix**: Detailed classification accuracy per class
- **ROC Curves**: Sensitivity and specificity analysis
- **Performance Visualization**: Comprehensive result analysis

## Research Significance

This project contributes to:
- **Quantum Machine Learning**: Practical application of quantum computing in healthcare
- **Neurological Diagnosis**: Advanced EEG signal analysis techniques
- **Early Detection**: Potential for identifying cognitive impairment stages
- **Non-invasive Methods**: Safe diagnostic alternatives

## Future Enhancements

- [ ] Real quantum hardware implementation
- [ ] Larger dataset integration
- [ ] Real-time EEG signal processing
- [ ] Clinical validation studies
- [ ] Mobile deployment for point-of-care diagnosis

## Contributing

Contributions are welcome! Please feel free to:
- Report bugs or issues
- Suggest new features
- Submit pull requests
- Share dataset improvements

## Citation

If you use this work in your research, please cite:
```
[Your Name], "Alzheimer's Classification using Quantum-CNN Model Architecture with EEG Dataset", 
GitHub Repository, [Year]
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- **PennyLane Team**: For the excellent quantum computing simulation library
- **Medical Research Community**: For EEG dataset contributions
- **Quantum Computing Community**: For advancing hybrid classical-quantum approaches

---

*This project represents the intersection of quantum computing and healthcare, demonstrating the potential of hybrid AI systems in medical diagnosis.*