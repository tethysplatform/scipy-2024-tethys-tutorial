# Tethys Platform Tutorial (SciPy 2024)

## Setup Instructions

We recommend creating a separate conda or virtual environment to install tethys-platform. Here are instructions for creating the environment with conda and venv.

### Conda

```commandline
conda create -n tethys -c conda-forge tethys-platform
conda activate tethys
```

### Venv/Pip

UNIX:

```commandline
python -m venv ./tethys
. ./tethys/bin/activate
pip install tethys-platform
```

Windows:

```commandline
python -m venv .\tethys
tethys\Scripts\activate.bat
pip install tethys-platform
```

## Outline

Participants will install Tethys Platform on their computers and build a Tethys App from scratch. We will provide an overview of Tethys Platform while they are getting setup, but the rest of the tutorial will be hands-on exercises.

### Part 1. Tethys Platform Key Concepts
Content will be drawn from the [Key Concepts Tutorials](https://docs.tethysplatform.org/en/stable/tutorials/key_concepts.html)
- Install Tethys Platform and Overview (15 min.)
- Beginner Concepts (50 min.)
  - Scaffold a new app
  - Anatomy of a Tethys App
  - App Settings
  - Add Map and Button to Home Page
  - Create a new page
  - Build out navigation to the page
- Break (10 min.)
- Intermediate Concepts (45 min.)
  - HTML Forms and User Input
  - Handling Form Submission
  - File-based model
  - Spatial Input with Forms
  - Render Spatial Data on Map


### Break (15 min.)

### Part 2. Convert a Panel Jupyter Notebook into a Tethys App
Content will be drawn from the [Bokeh Integration Tutorial](https://docs.tethysplatform.org/en/stable/tutorials/bokeh.html)
- Introduction (10 min.)
  - Demo the notebooks that will be converted (pre-existing)
  - Integrate Bokeh Notebook into Tethys App (45 min.)
- Break (10 min.)
- Add Panel to App (40 min.)
  - Introduce Panel/Panel Notebook
  - Integrate Panel dashboard into Tethys app
