ML Maestro (Ongoing)
==============================
A virtual teacher to teach Machine Learning using LLM and Generative AI. The solution uses RAG system built using Mistral 7B open source LLM

## Need

With the growth of AI, thre is a huge curiosity among massess to learn more about the field. There are many software engineers with an extensive programming background who want to build technical skills in the field; but, unfortunately, a lot of material on the internet is either too generic or assumes existing field knowledge. Further, many learning programs focus on teaching individual pieces first such as statstics, modelling, etc., which are important but starting with those can be demotivating for many. 

The ideal way to teach a subject like Data Science/ Machine Learning/ AI would be through teaching the whole game first - which means showing the big picture - and then teaching small steps to build the big picture. That means if you are teaching piano you first take the student to a piano concert or making them play piano. You don't teach them about reading music sheets or how a piano works. This is approach is based on the book Making Learning Whole by Harvard professor David Perkins. I came across this approach while going through fast.ai course and I was just amazed at how much progress I could make in a short time while going through the course. 

**The aim of this project to build a personal tutor using a RAG system that can teach the topic of Machine Learning like a personal tutor would do by using the 'big picture' approach described above.**

## Technologies
- Python, PyTorch
- HuggingFace Transformers
- LlamaIndex
- AutoML + Databricks + Azure ML (For Production)

![image](https://github.com/siddhantgithub/MLTutor_LLM_RAG/assets/1327717/e0fe2808-d4d4-486d-a153-adb1289347fc)

Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
