# Bike_sharing_pattern_detection

In this project, we detect the supply-demand gap of Bikes using a Deep Neural Network. The project focused more on building the Neural Network from scratch to help develop a better understanding, instead of using a library such as pytorch. 



## 1. Installation

Download Anaconda

|        | Linux | Mac | Windows | 
|--------|-------|-----|---------|
| 64-bit | [64-bit (bash installer)][lin64] | [64-bit (bash installer)][mac64] | [64-bit (exe installer)][win64]
| 32-bit | [32-bit (bash installer)][lin32] |  | [32-bit (exe installer)][win32]

[win64]: https://repo.anaconda.com/archive/Anaconda3-2018.12-Windows-x86_64.exe
[win32]: https://repo.anaconda.com/archive/Anaconda3-2018.12-Windows-x86.exe
[mac64]: https://repo.anaconda.com/archive/Anaconda3-2018.12-MacOSX-x86_64.sh
[lin64]: https://repo.anaconda.com/archive/Anaconda3-2018.12-Linux-x86_64.sh
[lin32]: https://repo.anaconda.com/archive/Anaconda3-2018.12-Linux-x86.sh

**Install** [Anaconda](https://docs.anaconda.com/anaconda/install/) on your machine. Detailed instructions:

## 2. Create and Activate the Environment

Please go though this [doc](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html) before you creating an environment.
After that create a environment using following command

```
conda create --name deep-learning
```

Then activate the environment using following command

```
activate deep-learning
```

#### Git and version control
These instructions also assume you have `git` installed for working with Github from a terminal window, but if you do not, you can download that first with the command:
```
conda install git
```

**Now, you can create a local version of the project**

1. Clone the repository, and navigate to the downloaded folder. This may take a minute or two to clone due to the included image data.
```
git clone https://github.com/shehrum/Bike_sharing_pattern_detection.git
cd Bike_sharing_pattern_detection


```

2. That's it!, Now run the project using following command, check you default browser and open Your_first_neural_network.ipynb file

```
jupyter notebook
```

