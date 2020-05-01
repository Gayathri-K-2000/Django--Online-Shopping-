# Django--Online-Shopping

This is a simple Django project to show up your products in your online store. And it is purely for beginners and perfect for beginners.

Lets get started.
Before downloading this repository, I recommend to follow the below steps:

 # Setting up
 
 I have used Windows OS and pip command in case of python. The method differs in case of different OS and if conda is used.
 
 Step 1: Download and install Python 3. (Don't forget to add path while installing)
 
 Step 2: Go to terminal (Command prompt). 
 
        => pip install django
 Step 3: Now, we have to create virtual environment to work with Django. To do that go with the following command:
 
        => pip install virtualenvwrapper-win
 Step 4: Go to the directory where you want to create virtual environment using cd command.
 
        => mkvirtualenv vir-env
 Now the virtual environment is created. 

# Starting your project

{ 
   NOTE: Always when working with your django project, you have to be in virtual environment. Each time you work on django, go to the    root directory of where the virtual environment is created using cd and you can find Scripts folder there. Go to that directory using cd  and type the following command:

           => activate.bat
   This activates the virtual environment to work with django.
}

Step 1: Change to the directory where you want to create your project using cd command.

Step 2: We are now going to create a folder to work on your project. Type the following command:

         => django-admin startproject pyshop .
Step 3: Now we can see the auto generated python files and packages in your directory.

        => python manage.py runserver
  This runs the server and copy & paste the address you see in your terminal. (You can see an url address while running the server in your terminal.)
  
Step 4: We can now create the other folders. Use the following command to create the required folders/ packages so that it's inner gets autogenerated.

       => python manage.py startapp products

# Admin page

In Django, Admin page is generated by default. That's a positive part of Django. Go to terminal and type:

      => python manage.py createsuperuser
   Give username, email and password and yes! Go to url-address/admin. Login in and play with it by adding products.
   
# Working of the project

The basic steps are complete.

Now Download the repository. Copy and replace only the python files other than those inside migrations folder. Go to terminal:

      => python manage.py makemigrations
      => python manage.py migrate
 This migrates the changes in your database to dbsqlite. This is the default databse used by django. You can also use other databases like SQL, MYSQL, Oracle.
 
 Make the required replacements of your code and the folders with the ones in the repository. 
 
 And that's it.
 
 I request not to download and run this project as it is. This may not work in your system So make only the replacements in the code.
 
 Happy learning!
        
