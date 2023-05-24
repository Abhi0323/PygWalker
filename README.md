# PyGWalker: Simplifying Data Analysis and Visualization in Jupyter Notebook 🚀

<p align="center"><a href="https://github.com/Abhi0323"><img width=100% alt="" src="<img width="767" alt="" src="https://github.com/Abhi0323/PygWalker/assets/112967999/5456dca1-9980-4330-8bcb-2e5df93e8fc4"></a></p>


Welcome to PyGWalker, an innovative library designed to make your data analysis workflow more efficient and interactive.

PyGWalker (or "Pig Walker", as we like to call it) is a Python binding for Graphic Walker, offering a powerful open-source alternative to Tableau. With PyGWalker, your pandas or polars dataframe is transformed into a Tableau-style User Interface within Jupyter Notebook, empowering you with simple drag-and-drop operations for visual exploration and creating stunning visualizations.

Join the PyGWalker community today and experience data analysis and visualization like never before!

Quick Start 🚀
Getting started with PyGWalker is super simple. Follow these steps and you'll be creating amazing data visualizations in no time!

Step 1: Installation
Install PyGWalker via pip. Run the following command in your terminal:

bash
Copy code
pip install pygwalker
Step 2: Import PyGWalker and Seaborn
After successful installation, import PyGWalker and Seaborn into your Jupyter Notebook.

python
Copy code
import pygwalker as pyg
import seaborn as sns
Step 3: Load Dataset
Load your preferred dataset. For demonstration purposes, we're using the 'flights' dataset from seaborn's built-in datasets.

python
Copy code
flight = sns.load_dataset('flights')
Step 4: Initialize PyGWalker
To start using PyGWalker, pass your dataset into the walk function.

python
Copy code
x = pyg.walk(flight)
Step 5: Start Visualizing
Now, the world of PyGWalker's interactive visualization is at your fingertips. Start exploring and creating amazing visualizations!

Contributing
Your contributions are always welcome! Please have a look at the contribution guidelines first.

License
PyGWalker is released under the MIT License.

Get In Touch
For any queries or feedback, feel free to reach out to us. We'd love to hear from you!

Enjoy your journey with PyGWalker! 💫🎉
