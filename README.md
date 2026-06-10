# Microservice Boundary Detection Using Developer Commit Patterns

## Overview

This project focuses on identifying potential microservice boundaries in a software system by analyzing developer commit patterns. The approach leverages commit history data to cluster software components that are frequently modified together, helping architects and developers make informed microservice decomposition decisions.

## Features

- Analyze developer commit history
- Detect component coupling based on co-change patterns
- Cluster related modules automatically
- Visualize microservice boundary candidates
- Data-driven microservice decomposition

## Project Structure


Microservice-Boundary-Detection/
│
├── Microservice_Boundary_Detection_Using_Developer_Commit_Patterns.ipynb
├── README.md
└── requirements.txt (optional)


## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## How It Works

1. Collect commit history data.
2. Analyze files modified together.
3. Build co-change relationships.
4. Apply clustering techniques.
5. Generate candidate microservice boundaries.

## Installation

Clone the repository:

--bash
git clone https://github.com/yourusername/Microservice-Boundary-Detection.git
cd Microservice-Boundary-Detection

Install dependencies:

pip install pandas numpy scikit-learn matplotlib jupyter
Running the Project

Start Jupyter Notebook:

jupyter notebook

Open:

Microservice_Boundary_Detection_Using_Developer_Commit_Patterns.ipynb

Run all cells sequentially.

Applications
Software Architecture Modernization
Legacy System Refactoring
Microservice Migration Planning
Dependency Analysis


##Author

Ramraju

License

This project is intended for educational and research purposes.


---
