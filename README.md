# Storm Movement Machine Learning

Our Gated Recurrent Unit (GRU) model predicts a tropical cyclone's next 24 hours of movement based its last 24 hours of characteristics. The model is trained on a dataset of tropical cylones from 1851 to 2015. The dataset comprised of the features of storms at every 6 hour interval beginning with its genesis. There are a total of 2,864 storms consisting of 75,242 data points. Features used for training the model included the Longitude, Latitude, Maximum Wind, Status, and Hours since Genesis.

The dataset can be found on Kaggle under "Hurricanes and Typhoons, 1851-2014" from National Oceanic and Atmospheric Administration (NOAA).

https://www.kaggle.com/datasets/noaa/hurricane-database

## Getting Set Up
These are the instructions to set up the project locally.

### Prerequisites
There are two prerequisite to run this project. First, you require a software that allows you to open and run a .ipynb file, such as Visual Studio Code. Second, you require Python to run the code in the notebook, as well as to install the requirements for the project. You may also require Git to clone the repository.

### Repository
If you have Git installed on your PC, you can run the below Git clone command on a command-line interface.

Clone the Repository:
```sh
git clone https://github.com/MusongKwon/StormMovementMachineLearning.git
```
If you do not have Git installed and do not wish to, you can download the the repository as a ZIP file and unzip onto you PC.


### Installation
There are three python libraries required to run the project: pandas, numpy, and torch.

You can install the requirements directly onto your PC or create a virtual environment where you can install them instead.

Create a virtual environment (optional):
```sh
python -m venv venv
```
Activate the virtual environment on macOS or Linux (optional):
```sh
source venv/bin/activate
```
Activate the virtual environment on Windows (optional):
```sh
venv\Scripts\activate
```
Note that depending on your security configuration, you might not be permitted to run this activation command on PowerShell. Run instead on Command Prompt (CMD).

<br>

Install Required Libraries:
```sh
pip install -r requirements.txt
```
If you create the virtual environment, ensure that the notebook is running on the kernel within the virtual environment.
You will also require to install ipykernel on the virtual environment:
```sh
pip install ipykernel
```
