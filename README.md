# Gender classification by transaction
 
## Summary
We have two files: trainingData.csv and trainingLabel.csv, accessible at:

[https://github.com/andynganle/Data-for-Assignment](https://github.com/andynganle/Data-for-Assignment)

trainingData.csv contains 15000 rows, each of which stores information of an user shopping session with four columns, separated by commas:
- The first column stores session ID.
- The second column stores start time of the session.
- The third column stores end time of the session.
- The last column contains a list of products ordered by view time, separated by semicolons. Each product consists of four IDs: the first three IDs are hierarchical category IDs while the last ID is the specific product ID.

trainingLabel.csv also contains 15000 rows that specify gender of corresponding users in
trainingData. The gender are either male or female.
 
In this project, we will extract some statistical information from the shopping session data, creating valuable features for the classification.

After that, an attemp to perform a gender classification for users based on their sessions's information will be demonstrated.

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
An environment named "used-cars" with necessary packages will be created. Use the command `conda activate shopping` to use the environment. To return to your base environment, type `conda deactivate`.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
