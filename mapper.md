# Open source mapper implementations

These instructions take place on the command line. If you are windows we are
looking to launch the anaconda powershell prompt. You can do this from either
anaconda navigator or directly from the start menu.

## Installation

1. Create a new virtual environment by running `conda create -n mapper`
2. Activate the new virtual environment by running `conda activate mapper`
3. Install pip and git `conda install git pip`
4. Install all the dependencies by running `pip install kmapper giotto-tda
   scikit-learn networkx flask flask_assets statsmodels jupyter`
5. Clone the mapper interactive project by running `git clone
   https://github.com/MapperInteractive/MapperInteractive`
6. Enter the mapper interactive project by running `cd MapperInteractive`
7. If you want to run MapperInteractive run `python run.py` and in your web
   browser (MapperInteractive recommends using google chrome) go to
   [127.0.0.1:8080](127.0.0.1:8080). To stop MapperInteractive go back to the
   command line and hit `ctr+c`.
8. To follow along with the tutorial jupyter notebooks:

   1. We download the data with `git clone https://github.com/erooke/iowa-tdv`
   2. Enter the directory `cd iowa-tdv/mapper`
   3. Run jupyter notebook with `jupyter notebook`

## Returning

Basically the same instructions can be followed to get back up and running,
only now you don't need to install anything. Launch the command line then:

1. Activate the virtual environment by running `conda activate mapper`
2. Enter the mapper interactive project by running `cd
   MapperInteractive`
3. To run MapperInteractive run `python run.py`
3. To run the notebooks enter the notebook folder `cd iowa-tdv/mapper`
4. Run the jupyter notebook with `jupyter notebook`
