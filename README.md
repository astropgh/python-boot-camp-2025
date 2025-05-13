**2020**: [GitHub](https://github.com/astropgh/astropgh-boot-camp-2020) / [website](https://astropgh.github.io/astropgh-boot-camp-2020/) (inc., Astropy, Pandas, Altair, Git/Github, linear regression, resampling, and debugging)

**2021**: [GitHub](https://github.com/astropgh/python-boot-camp-2021) / [website](https://astropgh.github.io/python-boot-camp-2021/) (inc., Astropy and Pandas)

**2022**: [GitHub](https://github.com/astropgh/python-boot-camp-2022) / [website](https://astropgh.github.io/python-boot-camp-2022/) (inc., Astropy and Pandas)

**2023**: [GitHub](https://github.com/astropgh/python-boot-camp-2023) / [website](https://astropgh.github.io/python-boot-camp-2023/)

**2024**: [GitHub](https://github.com/astropgh/python-boot-camp-2024) / [website](https://astropgh.github.io/python-boot-camp-2024/)

**2025**: [GitHub](https://github.com/astropgh/python-boot-camp-2025) / [website](https://astropgh.github.io/python-boot-camp-2025/)

Welcome to the 2025 AstroPGH Python Boot Camp for summer undergraduate students and early PhD students new to Python.  This 3 day program is designed to help you learn the basics of using Python for astrophysics and physics research.


## Boot Camp
### Installation and Setup
#### Python
Please install Python 3 before the Boot Camp. I recommend using [Miniconda](https://www.anaconda.com/docs/getting-started/miniconda/main) **_for Python 3.12_**. Here are Miniconda installation guides:
- [Windows](https://www.anaconda.com/docs/getting-started/miniconda/install#windows-installation)
- [macOS/linux](https://www.anaconda.com/docs/getting-started/miniconda/install#macos-linux-installation)

To avoid licensing issues, we want to switch the `conda` channel from `defaults` to `conda-forge`. Here's a step-by-step guide to do this: [Miniconda + conda-forge setup guide](https://dev.to/kaamisan/using-miniconda-with-conda-forge-to-avoid-anaconda-licensing-issues-5hkj) (though please use python 3.12).

Then install the following packages by copy and pasting the following lines into the terminal:
```bash
conda install numpy scipy pandas matplotlib astropy jupyter ipython
conda install -c conda-forge jupyterlab
pip install ipympl
```

If you have trouble with installing Jupyter Lab, see [Jupyter Lab installation guide](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html).

From the terminal, launch Jupyter Lab (see [Staring Jupyter Lab guide](https://jupyterlab.readthedocs.io/en/stable/getting_started/starting.html) for more details):
```bash
jupyter lab
```

#### Test Your Conda Installation

1. Open a new Anaconda prompt or terminal.
2. Type `ipython` into the terminal to open an interactive python session (the prompt should say `In [1]:`).
3. Copy this code:
```python
import numpy
import scipy
import matplotlib
import astropy
import pandas
```
4. Type into the iPython shell the word `paste`, and press enter.
5. If no errors are raised, you're ready for bootcamp. You may close the terminal window.

If you are having difficulties with installation, please do not hesitate to reach out to Brett Andrews on Slack or via email.

### Instructors
- [Collin McLeod](https://collinmcleod.github.io/): Python Basics
- [Tori Bonidie](https://toribonidie.github.io/): Data Structures
- [Lorena Mezini](https://lmezini.github.io/): Functions and Modules
- Cullen Abelson: Matplotlib
- Lauren Elicker: Numpy 1a
- Nathalie Chicoine: Numpy 1b
- [Travis Court](https://courtt.github.io/): Numpy 2a
- Jake Magee: Numpy 2b
- Finian Ashmead: Numpy 3a
- Marcos Tamargo-Arizmendi: Numpy 3b
- Chris Hernandez: Numpy 4a
- Julissa Sarmiento: Numpy 4b

### Schedule

| Time (ET) | Monday (5/19) | Tuesday (5/20) | Wednesday (5/21) |
|:-----:|:-----:|:-----:|:-----:|
| 10:00-11:15 | Python Basics | Numpy 1a | Numpy 3a |
| 11:45-1:00 | Data Structures | Numpy 1b | Numpy 3b |
| 2:00-3:15 | Functions and Modules | Numpy 2a | Numpy 4a |
| 3:45-5:00 | Matplotlib | Numpy 2b | Numpy 4b |


<a href="url"><img style="padding: 0px 20px;" src="https://github.com/astropgh/python-boot-camp-2021/blob/main/etc/NSF_4-Color_bitmap_Logo.png?raw=true" align="left" height="128" width="128"></a>

This material is based upon work supported by the National Science Foundation grant number AST-2009251. Any opinions, findings, and conclusions or recommendations expressed on this website are those of the participants and do not necessarily reflect the views of the National Science Foundation or the participating institutions.
