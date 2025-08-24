# ism-python-setup
A repository that shows the preferred way of setting up the environment for Python, including VS Code as the IDE.

## Setup

1. Install [Visual Studio Code](https://code.visualstudio.com/). This is a very popular IDE (integrated development environment) and we will work inside it during this course. It somes pre-installed with extensions that will allow you to work with Jupyter Notebooks.
2. Go to the extensions tab via the toolbar on the right in VS Code and enter "@recommended" into the search bar. There should be four extensions in the list, install them all.
3. Install [uv](https://docs.astral.sh/uv/getting-started/installation/#installation-methods). Make sure to follow the relevant guide based on your operating system.
4. In VS Code, open the terminal and run the `uv sync --frozen` - this will install all of the packages we will use in this course.
5. Open the example notebook in the notebooks folder click `Select Kernel`. You should be able to choose the repository's kernel.

