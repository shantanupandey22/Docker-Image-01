For creating a Docker Image save all the files on your computer
Install VS Code and Docker Desktop application
Create a new folder on desktop
Open that folder and search cmd 
After opening of cmd type : 'code .' this will open your VS Code 
In this create a python environmet by Ctrl + Shift + P
In .venv environment craete a folder name 'app.py'
Paste all the code of app.py file which you downloaded by opening in new tab
Run the code of app.py file in localhost
Create a Docker file inside a venv folder named 'Dockerfile'
Paste the code of Docker file which you downloaded from it 
Open terminal and get inside the venv folder by run the command 'cd .venv' 
Use code 'pip freeze > requirements.txt' in terminal which contains all python libraries
There is a requirements file is created successfully 
Run the command in terminal to build a Docker Image 
Use code : 'docker build -t flask-app .'
Open Docker Desktop application and click on images to run the image 
Provide a name and port to that application
Run the application on localhost which is provided by your docker application
# Your Docker image has been created successfully
