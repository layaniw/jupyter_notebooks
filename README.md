
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/layaniw/hands-on-jupyter)](https://github.com/layaniw/hands-on-jupyter/pulls)
[![GitHub Issues](https://img.shields.io/github/issues/layaniw/hands-on-jupyter?color=yellow)](https://github.com/layaniw/hands-on-jupyter/issues)
[![GitHub Repo Size](https://img.shields.io/github/repo-size/layaniw/hands-on-jupyter)](https://github.com/layaniw/hands-on-jupyter/usuals)
[![License](https://img.shields.io/github/license/layaniw/hands-on-jupyter?color=purple)](https://github.com/layaniw/hands-on-jupyter/usuals)
[![GitHub Fork](https://img.shields.io/github/forks/layaniw/hands-on-jupyter?style=social)](https://github.com/layaniw/hands-on-jupyter/usuals)
[![Stars](https://img.shields.io/github/stars/layaniw/hands-on-jupyter?style=social)](https://github.com/layaniw/hands-on-jupyter/usuals)

# Jupyter Notebook

This repository consists of two jupyter notebooks.

## 1. Post Correspondence Problem Notebook : post-correspondence.ipynb 

- Definition and explanation of the Post Correspondence Problem.
- Definition and explanation of the Bounded Post Correspondence Problem.
- Python function to solve the Bounded Post Correspondence Problem.
• Explanation of what an undecidable problem is in computability theory, with ref-
erence to the Post Correspondence Problem

## 2. Countdown Numbers Game Notebook : countdown.ipynb

- Overview and explanation of the Countdown Numbers Game.
- Complexity of the Countdown Numbers Game.
- Python function to solve the Countdown Numbers Game and explanation.

## Quick Way to Access the Notebooks

### Static Form

1. Post Correspondence Problem Notebook [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/layaniw/jupyter_notebooks/blob/cb537be048068e4402d00cf051d9e394c605489a/countdown.ipynb)

2. Countdown Numbers Game Notebook [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/layaniw/jupyter_notebooks/blob/cb537be048068e4402d00cf051d9e394c605489a/post-correspondence.ipynb)

### Dynamic Form

1. Post Correspondence Problem Notebook [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/layaniw/jupyter_notebooks/50d4ea18450ffd05af1dea84e3553815249f8f3c?filepath=post-correspondence.ipynb)

2. Countdown Numbers Game Notebook [![Binder](https://mybinder.org/badge_logo.svg)](https://hub.gke2.mybinder.org/user/layaniw-jupyter_notebooks-6q16hhms/notebooks/countdown.ipynb)

## Technologies

The technologies and libraries used are

- Jupyter
- Anaconda
- Docker
- numpy 
- python itertools 
- nbviewer
- Binder

## How to Install and Run the Project

### Run Jupyter Notebooks with Docker Container

Step 1. Install Docker

Use the link below to install Docker according to your operating system.

https://docs.docker.com/engine/install/

Step 2. Clone the Git Repository to your local machine

```sh
git clone https://github.com/layaniw/jupyter_notebooks.git
```

Step 3. Run the notebooks

Start Docker and navigate to the directory where the Dockerfile from this repository is stored. Open a command prompt and run

```sh
docker-compose up
```

This will build the docker image and run the container. You will see URLs at the end when everything is finished running in the terminal. If you are not navigated to one of those URLs automatically, you can copy-paste one of those URLs into a browser and open jupyter notebooks from there.

### Run Jupyter Notebooks using Anaconda

Step 1. Install Anaconda

Install the Anaconda distribution of Python. Download Anaconda at the following link

https://docs.anaconda.com/anaconda/install/index.html

Step 2. Clone the Git Repository to your local machine

```sh
git clone https://github.com/layaniw/jupyter_notebooks.git
```

Step 3. Go to the Windows start menu and select Anaconda Prompt

Step 4. Run jupyter notebook

At the Anaconda Prompt navigate to the folder with jupyter notebooks and type:

```sh
jupyter notebook
```

This command will start the Jupyter notebook server. The output in the Anaconda Prompt will include an URL. If you are not navigated to that URL automatically, you can copy-paste the URL from the Anaconda Prompt and paste it into a web browser. You can open Jupiter notebooks from there.

## Credits

Credit should go to Dr Ian McLoughlin (ian.mcloughlin@gmit.ie), whose instructions and guidance helped in build this repository.

## References :

- https://en.wikipedia.org/wiki/Post_correspondence_problem
- https://www.tutorialspoint.com/automata_theory/post_correspondence_problem.htm
- http://ianfinlayson.net/class/cpsc326/notes/15-undecidability
- http://www.cs.columbia.edu/~aho/cs3261/Lectures/L17-PCP.html

## License

https://github.com/layaniw/jupyter_notebooks/blob/main/LICENSE

## Contributing to the Project

Email layani92@outlook.com in case of any queries.


