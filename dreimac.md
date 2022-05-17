# DREiMac

These instructions take place on the command line. If you are windows we are
looking to launch the anaconda powershell prompt. You can do this from either
anaconda navigator or directly from the start menu.

## Installation

1. Create a new virtual environment by running `conda create -n dreimac
   python=3.8`
2. Activate the new virtual environment by running `conda activate dreimac`
3. Install pip and git `conda install git pip`
4. Install all the dependencies by running `pip install cython matplotlib numba
   numpy persim ripser scikit-tda scipy jupyter screeninfo`
5. Clone the DREiMac project by running `git clone
   https://github.com/ctralie/DREiMac.git`
6. Enter the DREiMac project by running `cd DREiMac`
7. Install DREiMac by running `python setup.py install`
8. You can now run the notebooks by running `jupyter notebook` and navigating
   to the notebooks folder

## Returning

Basically the same instructions can be followed to get back up and running,
only now you don't need to install anything. Launch the command line then:

1. Activate the virtual environment by running `conda activate dreimac`
2. Enter the DREiMac project by running `cd DREiMac`
3. You can now run the notebooks by running `jupyter notebook` and navigating
   to the notebooks folder
