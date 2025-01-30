<p align="center"> <a target="_blank"> <img src="https://github.com/adgiz05/graph-neural-networks-dlmasterupm/blob/main/utils/upm_logo.png?raw=true" width="600" alt="UPM Logo"> </a> </p> 
<h1 align="center">
    Deep Learning for Natural Language Processing
    <br>
    <small>Master in Deep Learning - Universidad Politécnica de Madrid</small>
</h1> 
<p align="center">Welcome to the official repository for the <strong>Deep Learning for Natural Language Processin</strong> course of the <a href="https://masterdeeplearning.etsisi.upm.es/">Master in Deep Learning</a> at the Universidad Politécnica de Madrid (UPM).</p>
<p align="center">
<strong>Coordinator:</strong> Javier Huertas-Tato
<br> 
<strong>Teachers:</strong> Javier Huertas-Tato & Pablo Miralles-González
</p>

## 📖 Lectures
### Lecture 1 - Introduction to HuggingFace: datasets, tokenizers, models, and pipelines ([📈 Slides]() | [📎 Material](session_1))

**Main learning objectives**

**Secondary learning objectives**

### Lecture 2 - Text Classification ([📈 Slides](https://upm365-my.sharepoint.com/:p:/g/personal/pablo_miralles_upm_es/EcLo3mu0CqpCoGOxVk0T3N0BXrZh7NRmc0SNylF6qwqCYQ?e=4cQSqX) | [📎 Material](session_2))

**Main learning objectives**
- Learn the kind of text classification tasks you find in the real world (basic, pairs of texts, and token classification)
- Learn which type of pre-trained LMs are used most often for these problems
- Learn how to fine-tune an LM for text classification, freezing the backbone model partially or completely

**Secondary learning objectives**
- Learn how to perform zero-shot classification with decoder-only LLMs
- Learn how to perform zero-shot classification with sentence similarity models

### Lecture 3 - Text Generation ([📈 Slides]() | [📎 Material](session_3))

**Main learning objectives**

**Secondary learning objectives**

### Lecture 4 - Text2Text with summarization ([📈 Slides]() | [📎 Material](session_4))

**Main learning objectives**

**Secondary learning objectives**

### Lecture 5 - Text Retrieval ([📈 Slides]() | [📎 Material](session_5))


**Main learning objectives**

**Secondary learning objectives**

### Lecture 6 - Advanced LLM Prompting ([📈 Slides]() | [📎 Material](session_6))

**Main learning objectives**

**Secondary learning objectives**

## ✏️ Assignment

**Objective**:  

**Deliverables**:  
A Jupyter notebook containing:  

**Deadline**: TBD

Good luck, and happy coding!  

## 💻 Preparing the environment

### Local setup
With `conda` installed (or `mamba` or `micromamba`), run in your command line:
```bash
# if you have a gpu
conda env create --file conda-env-gpu.yml
# if you don't
conda env create --file conda-env-no_gpu.yml

# to activate the environment
conda activate mdl-dl_nlp
```

### Google Colab

To create the environment, add the following cells to the beginning of the notebook, after copying the `conda-env-gpu.yml` file to the directory.

**Step 1**: Install conda
```python
!pip install -q condacolab
import condacolab
condacolab.install()
```

**Step 2**: Create the environment
```python
!conda env create --file conda-env-gpu.yml
```

**Step 3**: Activate the environment
```python
!source activate mdl_gen
```