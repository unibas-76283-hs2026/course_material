# What to install for this class


## Prequistes

Please install the following software before starting:

- **R**
- **RStudio**
- **Git**


If you don't have admin rights on your computer, ask your organisation's IT support.


## Clone the project

On the browser, copy the repository URL (green button Code).

For this project, it is 
https://github.com/unibas-76283-hs2026/course_material.git

With Rstudio, create a new project

File -> New project -> Version control -> Git

Chose option sign in with your browser.

You can chose the place where you clone the repository. 

I personally like to clone it in the Documents folder of my local computer.

## Workflow

- Pull before you start working
- Commit once you are finished with a chunk of work and add message to explain what you did
- Push



## Recommended project structure

I recommend the following project structure:

```text

course_material/
├── README.md
├── examples/
├── shared_code/
├── natacha/
├── student_1/
│   ├── data/
│   └── script/
├── student_2/
│   ├── data/
│   └── script/
├── student_3/
│   ├── data/
│   └── script/
└── student_4/
│   ├── data/
│   └── script/
├── README.md
├── INSTALL.md
├── .gitignore
└── project-name.Rproj
```

## Gitignore

This file lists all the files which should be ignored by GIT and will not be committed nor pushed. 
I usually place here all the figures and PDF/HTML produced by the scripts.

## Optional: Fork (Git Client)

Install [Fork](https://git-fork.com/) as Git GUI:

1. Download and install from https://git-fork.com/
2. Launch Fork, set your Git username and email if asked 

## Optional: Git LFS

Git LFS (Large File Storage) is a Git extension for managing large files. 

On a mac, yu can install it with Homebrew, but I don't know how to install on the PC.

```bash
brew install git-lfs
git lfs install
```





