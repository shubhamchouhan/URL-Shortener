FROM python:3

 ADD apps.py /
 
 RUN pip install pystrich
 
 CMD [ "python", "./apps.py" ]
 
 RUN docker build -t URL-Shortner
