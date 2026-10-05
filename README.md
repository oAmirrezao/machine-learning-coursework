# Machine Learning Coursework

A collection of practical machine learning assignments covering supervised learning, clustering, dimensionality reduction, neural networks, computer vision, and natural language processing. The notebooks include assignment prompts, implementations, and written analysis; some exercises remain unfinished.

## Coursework

| Area | Notebooks | Topics |
| --- | --- | --- |
| Supervised learning | [Regression and Perceptron](supervised-learning/Regression%20and%20Perceptron.ipynb), [Titanic](supervised-learning/Titanic/titanic.ipynb) | Polynomial regression, model selection, perceptron, preprocessing, random forests |
| Unsupervised learning | [GMM](unsupervised-learning/GMM/GMM.ipynb), [K-Means](unsupervised-learning/K-Means/K-Means.ipynb), [PCA](unsupervised-learning/PCA/PCA.ipynb) | Gaussian mixtures from scratch, expectation maximization, BIC, image segmentation, image compression |
| Neural networks | [Neural Networks & Optimization](neural-networks/Neural%20Networks%20%26%20Optimization.ipynb) | NumPy MLP, gradients, optimizers, regularization |
| Computer vision | [CNN Fine-Tuning](computer-vision/CNN_Finetuning_Completed.ipynb), [CNN and Neural Style Transfer](computer-vision/CNN-NST-completed.ipynb) | Transfer learning, flower classification, convolution filters, VGG, neural style transfer |
| NLP | [NER: BiLSTM to BERT](natural-language-processing/ML_HW5_NER_BiLSTM_to_BERT.ipynb), [Word Embeddings & Fine-Tuning](natural-language-processing/ML_HW5_WordEmbeddings_and_FineTuning%20%282%29.ipynb) | Embeddings, sequence labeling, attention, BERT, LoRA, DoRA exercises |

## Running the notebooks

For the supervised and unsupervised notebooks and the NumPy neural network exercises:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter lab
```

Run each notebook with its working directory set to its containing folder so that relative dataset and image paths resolve. Bundled CSV files and images remain beside their notebooks. The regression notebook also includes a saved model artifact.

Computer vision and NLP notebooks require additional packages shown in their import/install cells, including PyTorch/torchvision, TensorFlow, Hugging Face datasets/transformers, and PEFT. Install these in separate environments as needed; GPU resources and external dataset/model downloads may be required.

## Current limitations

- NLP notebooks contain unimplemented exercises (`NotImplementedError`); they are included as coursework in progress, rather than completed projects.
- The neural network notebook includes abstract/base-method placeholders.
- The computer vision archives did not include the flower dataset or the `Images/` directory referenced by the style-transfer notebook. Supply these inputs and adjust paths before running.
- Saved outputs and execution counts were cleared during privacy cleanup. Models have not been retrained or notebooks rerun as part of this preparation, so no fresh benchmark results are claimed.
- Dependency versions are not pinned because the original archives did not include a tested environment specification.

## Provenance and privacy

These are machine learning course materials from Fall 2025. Original assignment prompts and instructor/assignment-author credits are retained; those portions are distinct from student implementations. Dataset contents (including historical Titanic passenger names) are retained as learning inputs.

Student identity fields, personal notebook metadata, and saved execution outputs were removed from this repository. Original ZIP archives are excluded. No additional license is asserted over third-party course materials or datasets.
