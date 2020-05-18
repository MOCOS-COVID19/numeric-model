# Numerical computations used in the Paper

## Installation and run instructions
1. Installing 
 * Download Julia from [Julia's webpage](https://julialang.org)
 * Make sure GitLFS is installed

2. Install dependencies:
  * navigate into the main directory of the project
  * run Julia's REPL by, eg. running by `julia` command
  * enter Pkg by typing `]`
  * activate project by typing `activate .`
  * type `instantiate` to download and install dependencies
  * type `precompile` to force precompilation od dependencies (optional)

3. Run Jupyter
  * while running Pkg use `CTRL-C` or backspace to return from Pkg or start new Julia's REPL
  * type `Using IJulia` followed by `notebook()` to load the dependency and start Jupyter's notebook
  * you might be asked whether to install jupyter, if in doubt type `y`
  * a new browser window should open with Jupyter in it
  * within the browser, navigate to the project directory and open file `BJR solution.ipynb`
  * run and edit the code
