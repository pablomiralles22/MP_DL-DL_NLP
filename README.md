# Master in Deep Learning - Deep Learning for Natural Language Processing

Welcome to the base repository of the "Deep Learning for Natural Language Processing" course! In this README you will find:
- **Overview of the lectures**. An overview of each of the lectures, with a brief summary, the learning objectives and links to the slides.
- **Assignment**. A brief description of the assignment.
- **Environment setup**. Some simple steps to recreate our conda environment, which should have everything you need for the course!

You will also find one directory for each class. Inside, you will find an accompanying notebook to the lectures, as well as notebooks with exercises and their solutions.

## Lectures
### Lecture 1 -  ([Slides]())

### Lecture 2 -  ([Slides]())

**Main learning objectives**


**Secondary learning objectives**

### Lecture 3 - Introduction to Generative Adversarial Networks ([Slides]())

**Main learning objectives**

**Secondary learning objectives**

### Lecture 4 - Generative Adversarial Networks assignment ([Slides]())

### Lecture 5 - Autoregressive text generation ([Slides]())


**Main learning objectives**

**Secondary learning objectives**

### Lecture 6 - Diffusion models ([Slides]())

## Assignment: 

**Objective**:  

**Deliverables**:  
A Jupyter notebook containing:  

**Deadline**: TBD

**Grading Criteria**:  
- Completeness of implementation
- Model performance and results
- Clarity and organization of the notebook
- Quality of explanations and visualizations

Good luck, and happy coding!  

## Preparing the environment

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