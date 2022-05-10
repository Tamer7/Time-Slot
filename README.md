# Downloading and installing the Project

1. Download the project and open it in a new code editor
2. CD into the project directory and make sure you can see the "manage.py" file if you ls
3. Download the requirements.txt file by using " pip install -r requirements.txt "
4. Once the dependencies have been installed you can simply run the server in cmd by using " python manage.py runserver " 
5. Simply navigate to the project url which is "http://127.0.0.1:8000/"


# Creating a SuperUser
If you need to access the admin page which contains the models of the database, you will need to create a super user. 

1. On the terminal in the project directory, simply type in " python manage.py createsuperuser " and follow the instructions. 
2. Once you create it you can run the server againa and head to "http://127.0.0.1:8000/admin" which will take you to the admin side, where you can view the stored data. 



