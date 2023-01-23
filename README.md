# Touch Write Analysis
Analysis of the data collected in https://github.com/tberkane/TouchWriteDataCollection and digit recognition from capacitance data.

# Data
Place the data in the directories inside the `data` directory.

# How to run
Create a conda environment using the provided `env.yml` file :
```shell
conda env create -f env.yml
```
Open the notebooks :
```shell
jupyter lab
```
Then go the prediction.ipynb notebook and run all the cells to execute the preprocessing and prediction pipeline.

# Project Organization
    ├── README.md          <- README for developers using this project.
    │
    ├── data
    │   ├── capacitance    <- Capacitance data collected by the tablet app.
    │   ├── depth          <- Depth data collected by the RealSense camera.
    │   └── hand_pose      <- Hand pose data collected by the Leap Motion.
    │
    ├── prediction.ipynb   <- Notebook containing the code to preprocess and make predictions from the capacitance data.          
    │
    ├── research.ipynb     <- Notebook to explore and experiment with the data.
    │
    └── report.pdf         <- Final report.

