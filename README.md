# Placement-Eligibility-App-using-Streamlit-in-Python

### An User Interactive Dashboard Creation using Streamlit package in Python
### This has been prepared and developed in Windows 11 Pro OS Environment
### This is very good for the freshers to learn and start the web application without any IT Knowledge.

In this App, I have createdad the following tables as per the requirements and filled some values randomly using Faker library in python 
  1. Students
  2. Programming
  3. Softskill
  4. Placement

## STEP 1: Created an environment for this projects like as follows using Conda:

  1. Open the Anaconda Navigator which hase installed in my laptop.
  2. In the Home page, click the options "Environments" in the menu at LHS.
  3. Click on the "Create" button in the center pane of the home page.
  4. I named it as "Placement_Eligibility"
  5. After the successful creation of the environment, it will be appearing in the center pane of the home page.
  6. Click on the environment named as "Placement Eligibility", and click on the option is "Open in Terminal"
  7. In the opened terminal window, I installed Jupyter notebook like as follows.
       $ conda install jupyter notebook -y
  8. After the successful completion of the above command, I confirmed the installation with following commands
       $ conda list
  9. Again, Go back to the home page of Anaconda Navigator. Click on the "Environments" option in the menu at LHS and click on "Placement Eligibility" environment in the center pane of the home page. Select and click on the option "Open in Jupyter Notebook"
  10. It will take you to browser and jupyter notebook page.

## STEP 2: Run the teble_generation.iynb file:

  1. Go to your working directory and keep this table_generation.iynb file.
  2. After that, go to the jupyter notebook page. It will shoe this file in the root directory.
  3. Just a click on the file, it will take you to python terminal where you can run this code one by one.
  4. Now, you can run line by line simply. It will genereate your dataset for the development of placement eligibility app.
  5. Next, move to the next step.

## STEP 3: Create an virtual environment: 

### These steps has been executed in VS code editor and Python in the local machine.

  1. First, Install the VS Code Editor from https://code.visualstudio.com/download
  2. Second, Install the python in the system and configure the evironment variable also properly.
  3. Opened the VS code Editor and load your current working directory using the "File" menu --> "Open Folder" Option.
  4. Download the .rar file from here and extract it, also keep it in the currently working directory.
  5. Go to the "Terminal" menu and click on the "New Terminal" option.
  6. In the bottom side, a terminal will open. Then run the following command to configure the streamlit environment.
       $ python -m venv placement_eligibility
       $ .\placement_eligibility\Scripts\acitivate
       $ python -V (should me >=3.10
       $ pip install streamlit
       $ pip install matplotlib
  7. After the completion of the above commands, go to the current working directory, where you extracted the downloaded streamlit application.
  8. Run the following command to start the application.
       $ streamlit run placement_eligibility.py
  9. It would be started and opened the default browser with respective URL of your streamlit application automatically.
  10. That's all.

#  This is the way of running this streamlit application on your Windows PC. Thank you once again for visiting!!!
