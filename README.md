# Machine Learning Coursework

Practical machine learning coursework spanning classical algorithms, neural networks, computer vision, and natural language processing. The collection brings together mathematical foundations, implementations from scratch, and applications using modern machine learning libraries.

## Topics and Projects

| Area | Notebook | Topics |
| --- | --- | --- |
| Supervised Learning | [Regression and Perceptron](supervised-learning/Regression%20and%20Perceptron.ipynb) | Polynomial regression, model selection, perceptron classification |
| Supervised Learning | [Titanic Survival Prediction](supervised-learning/Titanic/titanic.ipynb) | Exploratory data analysis, preprocessing, random forests, feature importance |
| Unsupervised Learning | [Gaussian Mixture Models](unsupervised-learning/GMM/GMM.ipynb) | Customer segmentation, expectation maximization, Bayesian information criterion |
| Unsupervised Learning | [K-Means Image Segmentation](unsupervised-learning/K-Means/K-Means.ipynb) | Clustering from scratch, image segmentation, elbow method |
| Dimensionality Reduction | [PCA Image Compression](unsupervised-learning/PCA/PCA.ipynb) | Principal component analysis from scratch, image reconstruction, reconstruction error |
| Neural Networks | [Neural Networks & Optimization](neural-networks/Neural%20Networks%20%26%20Optimization.ipynb) | NumPy MLP, backpropagation, gradient checking, optimizers, regularization |
| Computer Vision | [CNN Fine-Tuning](computer-vision/CNN_Finetuning_Completed.ipynb) | Transfer learning, flower classification, pretrained convolutional networks |
| Computer Vision | [CNN and Neural Style Transfer](computer-vision/CNN-NST-completed.ipynb) | Convolution filters, feature visualization, VGG, neural style transfer |
| Natural Language Processing | [NER: BiLSTM to BERT](natural-language-processing/ML_HW5_NER_BiLSTM_to_BERT.ipynb) | Sequence labeling, recurrent networks, attention, BERT-style architectures |
| Natural Language Processing | [Word Embeddings & Fine-Tuning](natural-language-processing/ML_HW5_WordEmbeddings_and_FineTuning%20%282%29.ipynb) | Word embeddings, GloVe, transformer fine-tuning, LoRA, DoRA |

## Repository Structure

```text
machine-learning-coursework/
├── supervised-learning/
│   ├── Regression and Perceptron.ipynb
│   ├── skyfuel_final_model.pkl
│   └── Titanic/
├── unsupervised-learning/
│   ├── GMM/
│   ├── K-Means/
│   └── PCA/
├── neural-networks/
├── computer-vision/
├── natural-language-processing/
├── requirements.txt
└── README.md
```

## Getting Started

Clone the repository and create a Python environment:

```bash
git clone https://github.com/oAmirrezao/machine-learning-coursework.git
cd machine-learning-coursework
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter lab
```

On Windows, activate the environment with `.venv\Scripts\activate`.

The root `requirements.txt` provides dependencies for the classical machine learning and NumPy notebooks. Computer vision and NLP notebooks use additional libraries listed in their import and installation cells, including PyTorch, torchvision, TensorFlow, Transformers, Datasets, and PEFT.

Run each notebook from its containing directory to resolve relative file paths. Dataset and model downloads are configured within the relevant notebooks; prepare any referenced local datasets and image directories before execution. A GPU is useful for deep learning experiments.

## Tools and Libraries

- **Scientific computing:** NumPy, pandas
- **Classical machine learning:** scikit-learn
- **Visualization:** Matplotlib, Seaborn
- **Deep learning:** PyTorch, TensorFlow, torchvision
- **Natural language processing:** Hugging Face Transformers, Datasets, PEFT, Gensim
- **Development:** Python, Jupyter

## Acknowledgments

Developed as part of machine learning coursework at Sharif University of Technology, Fall 2025. Original assignment prompts and teaching-team credits are preserved in the notebooks. Third-party datasets, pretrained models, and course materials remain attributable to their respective creators.
