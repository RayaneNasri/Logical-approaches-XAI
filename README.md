# Logical-approaches-XAI
This repository contains the Python code I developed during my research internship at LIP6. The code focuses on implementing and analyzing logical approaches to Explainable AI (XAI). It includes various scripts and modules aimed at enhancing the transparency and interpretability of symbolic machine learning models.

# Dependencies
During my internship, I utilized several external tools, including:
- The compiler **c2d**: http://reasoning.cs.ucla.edu/c2d/ <br>
- The Minimal Correction Subset enumerator **EnumELSRMRCache**: http://www.cril.univ-artois.fr/enumcs/ <br>
- The Minimal Hitting Set solver **Minihit**: https://github.com/TheMatjaz/minihit <br>

These tools are grouped in the **'tools'** directory.

# Code structure
As presented in my internship report, the code is consists of three files; *xALogic.ipynb, xRLogic.ipynb and xTLogic.ipynb*. In the first one, I implemented an algorithm to enumerate the sufficient reasons behind a decision made by a symbolic classifier based on **Deterministic Decomposable Negation Normal Form** as presented in the article by Adnane Darwiche and Auguste Hitrh (2020). In the second, I implemented an algorithm to enumerate the sufficient reasons and contrefactuals explanations for a decision based on **Minimal Unsatisfiable Subset** and **Minimal Correction Subset** as presented in the doctoral thesis of Ryma Boumazouza (2024). In the third file, I implemented my own approach to identify contrastive bi-factual explanations. The code deals with a very specific framework, that of acceptance to a master's program.

# Internship report
For a better understanding of the approach used, I encourage you to read my internship report.

# Author
- Rayane Nasri

