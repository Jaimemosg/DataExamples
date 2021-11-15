<<<<<<< HEAD
# Tennesee-Eastman Process

Each `.RData` file is an external representation of an R data frame that can be read into an R environment with the `load()` function. The data frames are named `faultfreetrainin` and `faultytesting`.

Each dataframe contains 55 columns:

1. Column 1 ('faultNumber') ranges from 1 to 20 in the “Faulty” datasets and represents the fault type in the TEP. The “FaultFree” datasets only contain fault 0 (i.e. normal operating conditions).

2. Column 2 ('simulationRun') ranges from 1 to 500 and represents a different random number generator state from which a full TEP dataset was generated (Note: the actual seeds used to generate training and testing datasets were non-overlapping).

3. Column 3 ('sample') ranges either from 1 to 500 (“Training” datasets) or 1 to 960 (“Testing” datasets). The TEP variables (columns 4 to 55) were sampled every 3 minutes for a total duration of 25 hours and 48 hours respectively. Note that the faults were introduced 1 and 8 hours into the Faulty Training and Faulty Testing datasets, respectively.

4. Columns 4 to 55 contain the process variables; the column names retain the original variable names.

This data and this documentation is copied from the original source. Here we work only with two data frames.

=======
# Tennesee-Eastman Process

Each `.RData` file is an external representation of an R data frame that can be read into an R environment with the `load()` function. The data frames are named `faultfreetrainin` and `faultytesting`.

Each dataframe contains 55 columns:

1. Column 1 ('faultNumber') ranges from 1 to 20 in the “Faulty” datasets and represents the fault type in the TEP. The “FaultFree” datasets only contain fault 0 (i.e. normal operating conditions).

2. Column 2 ('simulationRun') ranges from 1 to 500 and represents a different random number generator state from which a full TEP dataset was generated (Note: the actual seeds used to generate training and testing datasets were non-overlapping).

3. Column 3 ('sample') ranges either from 1 to 500 (“Training” datasets) or 1 to 960 (“Testing” datasets). The TEP variables (columns 4 to 55) were sampled every 3 minutes for a total duration of 25 hours and 48 hours respectively. Note that the faults were introduced 1 and 8 hours into the Faulty Training and Faulty Testing datasets, respectively.

4. Columns 4 to 55 contain the process variables; the column names retain the original variable names.

This data and this documentation is copied from the original source. Here we work only with two data frames.

>>>>>>> 516a12819b30589843e3ba3568cfdb2a501e2b0e
Source: https://www.kaggle.com/averkij/tennessee-eastman-process-simulation-dataset/activity