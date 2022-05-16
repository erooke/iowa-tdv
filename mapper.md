# Open source mapper implementations

These instructions take place on the command line. If you are windows we are
looking to launch the anaconda powershell prompt. You can do this from either
anaconda navigator or directly from the start menu.

## Installation

1. Create a new virtual environment by running `conda create -n mapper`
2. Activate the new virtual environment by running `conda activate mapper`
3. Install pip and git `conda install git pip`
4. Install all the dependencies by running `pip install kmapper giotto-tda
   scikit-learn networkx flask flask_assets statsmodels`
5. Clone the mapper interactive project by running `git clone
   https://github.com/MapperInteractive/MapperInteractive`
6. Enter the mapper interactive project by running `cd MapperInteractive`
7. You can now run MapperInteractive by running `python run.py`

After running the last command you should have a webserver start. To see the
program go to your browser (MapperInteractive recommends using google chrome)
and navigate to `127.0.0.1:8080`. `ctrl-c` in the command line should stop the
program.

## Returning

Basically the same instructions can be followed to get back up and running,
only now you don't need to install anything. Launch the command line then:

1. Enter the mapper interactive project by running `cd MapperInteractive`
2. You can now run MapperInteractive by running `python run.py`
