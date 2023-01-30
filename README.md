# iCare
iCare is a computerized system to maintain all the information of hospital entities.

Steps for executing iCare program: 

1. Make sure your pc has all the required python modules. (Requirements attached below)
2. Extract the zip folder.
3. Move to project folder in Terminal. 
4. Then run following Commands:
				--> py manage.py makemigrations
				--> py manage.py migrate
				--> py manage.py runserver
5. Now enter the following URL in Your Browser: http://127.0.0.1:8000/



Requirements:
- python latest version
- django 
	- to install, type 'pip install django' (without quotes) in the windows terminal 
	  also install 'pip install django-widget-tweaks' in the windows terminal
-xhtml
	- to install, type 'pip install xhtml2pdf' (without quotes) in the windows terminal 
