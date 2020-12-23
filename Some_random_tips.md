### 1. Jupyter Notebook:

// Get the right path for pip install packages, say, wordcloud

import sys
print(sys.executable)

path/to/python -m pip install some_package

//pretty print all cell's output and not just the last one

from IPython.core.interactiveshell import InteractiveShell
InteractiveShell.ast_node_interactivity = 'all'

//uninstall a python version on MAC

https://stackoverflow.com/questions/3819449/how-to-uninstall-python-2-7-on-a-mac-os-x-10-6-4

//Some tips for jupyter notebook
https://nbviewer.jupyter.org/github/MeierG/text-analysis-nsf-grant-abstracts/blob/master/notebooks/nsf-grants.ipynb

//Add a new path <br>
new_path = '/Library/Frameworks/Python.framework/Versions/3.7/lib/python3.7/site-packages' <br>
sys.path.append(new_path)
