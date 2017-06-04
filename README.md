# vet-resources

#**Resources**

##header

##Django virtualenv
	
	1.**Docs** [https://virtualenv.pypa.io/en/stable/userguide/#using-virtualenv-without-bin-python]

	1.1 **virtualenvWrapper Docs** [https://virtualenvwrapper.readthedocs.io/en/latest/install.html]
	  
	  * installs environment with pip and setuptools to allow installation of additional packages to virtualenv 
	  
	  *`virtualenv ENV`
	  
	  *`source bin/activate` activates shell environment
	  
	  *'deactivate' to return to home
	
	2. `ENV/bin/pip...<insert pip command>` to install packages into virtualenv
	  *`ENV/bin/pip install Django`

##Django project 1 tutorial [https://docs.djangoproject.com/en/1.11/intro/tutorial01/]
	
	1. `django-admin startproject mysite`
	2.	`python manage.py runserver` **worry about migrations after**
	  *change default server port using `python manage.py runserver <insert port number>`

**Projects vs. apps

What’s the difference between a project and an app? An app is a Web application that does something – e.g., a Weblog system, a database of public records or a simple poll app. A project is a collection of configuration and apps for a particular website. A project can contain multiple apps. An app can be in multiple projects.**

	3.`python manage.py startapp <app_name>`//