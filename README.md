# Car_Price_Prediction

1) Create **Second_Hand_Car_Price_Prediction** repo on your github, clone it local side/machine.
2) open that repo or folder (Second_Hand_Car_Price_Prediction) -> go to View -> Command Pallete -> python:Select interpreter -> select conda's python interpreter (Base environment of conda is selected.base conda python interpreter is of 3.11.4 version),,,bcz i am going to create virtual environment using **conda** command,,,bcz it gives us easyness compare to global python interpreter.....then **close the current opened terminal and open new one,,so that selected python interpreter is activated for use**
    ie;in Global python interpreter -> if u want to create virtual env then write command **python -m venv .myvenv**,,and to install a python in to this environment is a tidious task,,,,,,,,so use conda

    ie; in conda python interpreter ->  **conda create -p car_price_pred_venv python=3.11.9 -y** in this repo or folder,,,car_price_pred_env this virtual env is created with python 3.11.9 (ie;python.exe),,thus any .py from this environment is going to execute by accessing this python interpretr..
3) **conda env list** to see all virtual env present inside selected environment,ie;if you selected base then you will notice all venv present in that env.activate the virtual env using this command **conda activate .\car_price_pred_venv**,,,,,,,,,,,,,and then write this command **python --version**,,if you successfully activated or gone inside this car_price_pred_env then it should show 3.11.9,,bcz you installed this version python interpreter in this virtual env....
if you are getting 3.11.4,,that means not activated,,,3.11.4 is a conda base python interpreter version,,which we are selecetd to create virtual env...
OR view -> command palette -> select python interpreter -> ('car_price_pred_venv':conda) .\car_price_pred_venv\python.exe,,,
now close the current terminal and open it again,,now you can see a pop up which is showing that you are in car_price_pred_venv,,,,note:in terminal it will not display  that u are in this env,,,so  run python --version and check that python version is same as we installed in car_price_pred_venv..
5) pip install -r requirements.txt...................better is to mention version of each library,,so that easy for other users to run it successfully,,,,,,,,,,,,but if you are using Docker to make IMAGE of this project,,,then no need to mention version,,,it will automatically infer.
6) create **Experiments.ipynb file**,,,where all our ML code and experimentaion is done,,,and after getting best performing model,,i am going to save that model using pickle and use that model in my streamlit application..
7) to run jupyter notebook in vs code,,open Experiments.ipynb file -> click on 'select kernel' -> select python interpreter -> recommended is python interpreter from car_price_pred_venv,,ie;python.exe from this virtual env...3.11.9,,, -> when you run any cell then pop up is come out which indiactes you to download ipykernel package,,so click on install,,it will install those package and store it in car_price_pred_venv virtual env,,,,,,,,,,,,,,,
8) now you can perform you experimentaions
9) while importing any library u get any error then upgrade that library,,pip install --upgrade scikit-learn

![Screenshot (285)](https://github.com/user-attachments/assets/8e6cca83-458d-404c-9145-1dcb082da438)

![Screenshot (286)](https://github.com/user-attachments/assets/a5f7f686-697a-47c4-a2e8-788e9ef0b59c)

![Screenshot (287)](https://github.com/user-attachments/assets/b301b017-6ac7-4904-8e12-04a27a23dd6f)

