# Classify song genres from audio data
 
With a dataset comprised of songs of two music genres (Hip-Hop and Rock), this project uses Python3, Numpy, Pandas, with Scikit-learn to train a classifier in order to distinguish between the two genres based only on track information derived from [Echonest](http://the.echonest.com/) (now part of Spotify)

## Installation

In order to run the project, Anaconda Distribution must be installed. Go [here](https://www.anaconda.com/distribution/#download-section) to download the installer for Python 3.7 version, remember to choose the right one for your environment.

After the download is finished, install Anaconda, choose one of the steps below based on your environment.
#### On Windows or macOS
Run the installer and follow the instructions.
#### On Linux
Open a terminal and type the following command:
```bash
bash ~/Downloads/Anaconda3-2019.03-Linux-x86_64.sh
```
After the installation is finished, you will be able to open Anaconda Navigator on Windows and macOS from Start menu and Launchpad respectively. For Linux users, to open Anaconda Navigator, open a terminal and type the following command:
```bash
anaconda-navigator
```

## Run the project
- Download the project and unzip it in your working directory.
- Open Anaconda Navigator and and launch Jupyter Notebook. A window will be opened for Jupyter Notebook.
- Inside Jupyter Notebook window, navigate to the unzipped project folder and click on the **.ipynb** file to open it.
- After opening the file, click "Run" button to run the project step by step or "Fast forward" button to run the whole project at once.
#### Create an environment for the project
If you are familiar with conda environments, you can create a seperate environment to run this project. To do it, open a terminal or the Anaconda prompt, navigate to the project folder and type the following command:
```bash
conda env create -f environment.yml
```
An environment named "used-cars" with necessary packages will be created. Use the command `conda activate csg` to use the environment. To return to your base environment, type `conda deactivate`.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
