# PySpark Training

## Abstract

Resources to learn how to manipulate dataframes using PySpark.

## Pre-requisites

 1. Setup the data science VM on your laptop using the instructions at [https://github.com/raphslalom/ds-vm](https://github.com/raphslalom/ds-vm). Start from the beginning and stop at the end of the section "Start Hadoop". Make sure to read the instructions thoroughly and execute all the steps documented (and only these steps).
 
 2. Ssh into the VM: see https://github.com/raphslalom/ds-vm/tree/master/slalomdsvm#managing-the-vm) for details.

 3. Clone this repo on the VM to get the training notebook.

  ```bash
  mkdir repositories
  cd repositories
  git clone https://github.com/raphslalom/pyspark-training.git
  ```
 
 4. [optional] If you want to open the notebook in Jupyter:
      
      1. Launch a Jupyter server on the VM:
 
       ```bash
       jupyter notebook
       ```
       
      2. Open Jupyter at [http://slalomdsvm:8888/](http://slalomdsvm:8888/) and navigate in the UI to open the notebook under `pyspark-training/module7/module7-pyspark-df-manipulations.ipynb`. (When you are done: close the spark session from the notebook, halt and quite the notebookfrom Jupyter,  use CTRL-C to terminate the  Jupyter server running on the VM).

 4) Logout of the VM and hibernate it:
 
 ```bash
 logout
 vagrant suspend
 ```
