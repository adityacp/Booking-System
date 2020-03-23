Booking System
==============

Introduction
^^^^^^^^^^^^

A Django based booking system for any kind of resources


Requirements
^^^^^^^^^^^^

- Python 3.6
- Django 3.0.4
- django-auth-ldap 2.1.0
- django-recurrence 1.10.2
- python-ldap 3.2.0
- pandas 1.0.1
- mysqlclient 1.4.6

Installation
^^^^^^^^^^^^

- Installing system requirements
      
      
      **Debian/Ubuntu**
      ::
       
          $ sudo apt-get install libsasl2-dev python3-dev libldap2-dev libssl-dev
          
      ::
       
          $ sudo apt-get install default-libmysqlclient-dev
      
      
      **Centos/RedHat**
      
      ::
          
          $ sudo yum install python3-devel openldap-devel
          
      ::
          
          $ sudo yum install mysql-devel
  
  
-  Clone the repository

      ::

          $ git clone https://github.com/adityacp/Booking-System.git

-  Go to the project directory

      ::

          $ cd Booking-System


- Installing project packages

      ::

          $ pip install -r requirements.txt


- Create superuser

      ::

          $ python manage.py createsuperuser
