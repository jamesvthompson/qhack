# Run:AI Instructions

## Step 1: Access the Login Page

Go to the URL provided and log in with your username and password.

## Step 2: Change Your Password

Once you have successfully logged in, you will need to change your password for security purposes.

<img width="381" alt="Screen Shot 2023-02-22 at 1 54 14 PM" src="https://user-images.githubusercontent.com/109220448/220733370-ccd911c3-c3fa-40a2-8499-d17be720d392.png">

## Step 3: Select the Jobs Tab

Once you have changed your password, select the "Jobs" tab on the left side of the screen.

<img width="1495" alt="1 Screen Shot 2023-02-22 at 1 54 45 PM" src="https://user-images.githubusercontent.com/109220448/220746133-1c94c4db-0f1f-4603-a913-23b31a2c9fee.png">

## Step 4: Select "New Job"

In the top right corner of the user interface, you will see a "New Job" button. Click on it to proceed.

<img width="1498" alt="1 Screen Shot 2023-02-22 at 1 55 52 PM" src="https://user-images.githubusercontent.com/109220448/220746225-2e26ea01-7d3f-4a60-b653-15600c5c8634.png">


## Step 5: Select Jobe Type

At the top of the screen select the interactive tab at the top of the jobs page.

## Step 6: Select Your Project

On the jobs page, select your project from the drop-down list. 

<img width="1487" alt="1 Screen Shot 2023-02-22 at 1 56 21 PM" src="https://user-images.githubusercontent.com/109220448/220746285-8c432741-f43c-4955-afa5-db02aa752e46.png">

You should only have 1 available project. 

<img width="879" alt="Screen Shot 2023-02-22 at 1 56 28 PM" src="https://user-images.githubusercontent.com/109220448/220733513-6d25b790-282c-4991-a969-3b32e73ceba9.png">

## Step 7: Select the "qhack-quickstart" Template

Once you have selected your project, you will need to select the "qhack-quickstart" template on the left side of the screen.

<img width="1351" alt="1 Screen Shot 2023-02-22 at 1 56 40 PM" src="https://user-images.githubusercontent.com/109220448/220746393-4aa14fae-c263-4fab-a76d-e5b1b479236f.png">

## Step 8: Submit the Job

After you have selected the template, you can click on the "Submit" button in the lower right corner of the screen to submit the job.

<img width="1470" alt="1 Screen Shot 2023-02-22 at 1 56 59 PM" src="https://user-images.githubusercontent.com/109220448/220746435-766e1459-5d82-4c3b-92c4-6fc1e047b54f.png">

## Step 9: Connect to Your Jupyter Notebook

Once the job has been submitted and the status is "running," you can either right-click on the job and connect or click on the job and then click on "Connect" in the top right of the page. This will allow you to connect to your Jupyter notebook on an A100 GPU.

<img width="1505" alt="1 Screen Shot 2023-02-22 at 1 59 07 PM" src="https://user-images.githubusercontent.com/109220448/220746496-b1d6eb68-6fb4-4d2d-a0be-89c9067aa190.png">

## Step 10: Install Pennylane Lightning

Each instance will come with the scipy jupyterlab set up. However, if you would like to install Pennylane lightning, you can follow the steps below:

Open a terminal in your Jupyter notebook.
Install Pennylane lightning by running the following command: 

```
conda install cuda -c nvidia/label/cuda-11.4.0
pip install cuquantum
pip install PennyLane==0.27.0 PennyLane-Lightning==0.27.0 Pennylane-lightning-gpu==0.27.0
```
