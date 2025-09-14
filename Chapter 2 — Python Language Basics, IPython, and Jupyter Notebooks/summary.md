# Chapter 2 — Python Language Basics, IPython, and Jupyter Notebooks
 ---
## The Python Interpreter
- Python is **interpreted** → executes code **one statement at a time**.  
- Start interpreter:
```bash
$ python
>>> a = 5
>>> print(a)
5
Prompt: >>>

Exit: exit() or Ctrl-D (Linux/macOS)

Run .py file:

bash
Copy code
$ python hello_world.py
IPython/Jupyter often used for data analysis.

IPython Basics
Enhanced interactive shell.

Launch:

bash
Copy code
$ ipython
Numbered prompts: In [1]:

Execute code:

python
Copy code
In [1]: a = 5
In [2]: a
Out[2]: 5
Magic commands: %run script.py, %timeit, etc.

Pretty-printing for better readability.

Can execute blocks of code or entire scripts.

Jupyter Notebook
Web-based interactive document → code + Markdown + visualizations

Uses IPython kernel

Start notebook:

bash
Copy code
$ jupyter notebook
Create new → Python 3 → type code → Shift+Enter to run

Saves as .ipynb → self-contained (code + outputs)

Rename, load, close notebooks from landing page

Closing browser does not stop kernel; use File → Close and Halt
