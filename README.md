# Medico.AV

This was our skill development project which focuses on improving the medical system in our country. The doctor to patient ratio in our country is huge and both doctors and patients face difficulties in completing the required procedures to get medical treatment. So, we have implemented an application which has the ability to predict diseases using AI algorithms. This makes helps patients get early diagnosis and also reduces load on doctors by eliminating patients who are not from their domain of practice.

P.S: We are not trying to replace doctors using this project. 

Modules: 

There is an admin module and a user module. Admins will be able to change the internal functions of the application while the users will be able to use the application as the end product.

## Screenshots

Homepage: 
![image](https://user-images.githubusercontent.com/74983916/209926325-cdd438ae-5ea3-4311-9c83-327b5c17119f.png)

Login Page: 
![image](https://user-images.githubusercontent.com/74983916/209926389-1bada258-fbdd-44c3-a6fb-9359ee16c9cb.png)

Profile page:
![image](https://user-images.githubusercontent.com/74983916/209926419-cb4efa0c-1402-4f90-ae4c-8ba3b3cc7162.png)

Add Symptoms page: 
![image](https://user-images.githubusercontent.com/74983916/209926458-e191fac6-ff47-444c-81b2-4cf78010efc5.png)

Result Page: 
![image](https://user-images.githubusercontent.com/74983916/209926490-e9ce9fe6-12ed-438f-ae39-c7285530d26e.png)

Hospital Search Page:
![image](https://user-images.githubusercontent.com/74983916/209926522-d2918524-44d1-4d63-ba3b-446ae63ec9dc.png)

## How to run the project?

Make sure you have pip installed in your system. Once that is done, open the project folder and install virtualenv using

    pip install virtualenv

Once that is done, create a virtual environment using

    virtualenv venv
  
When virtual environment is created, activate it using
	

    venv/Scripts/activate

Now, you would need to install all the required packages. You can do this by running

    pip install -r requirements.txt

Change your database configurations in the *settings.py* file, once that is done, you need to migrate the databases to your database
	

    python manage.py makemigrations
    python manage.py migrate

Your project is ready to be run, the final step is to run

    python manage.py runserver

## Contribution Guide

We will be accepting any valuable contributions in this project. There are some issues open so try to solve those first. While making contributions, **do not change the folder structure at any cost.** You can create new apps and link it. You can also make changes to the html and css codes.     
