### 1. Jupyter Notebook:

// Get the right path for pip install packages, say, wordcloud

import sys
print(sys.executable)

path/to/python -m pip install some_package

//pretty print all cell's output and not just the last one

from IPython.core.interactiveshell import InteractiveShell
InteractiveShell.ast_node_interactivity = 'all'
