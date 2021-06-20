# Techno-blog

I have deployed my project on Heroku server you can access through the link.

Here is the link for mytechno-blog : https://mytechno-blog.herokuapp.com 

# For local host
Installation. Pre-requisites including Git, Python 3.4x or newer, pip. To obtain a blank site, these are the steps to follow:

Clone this repo
git clone https://github.com/Suryanshm000/Techno-blog.git

Enter the cloned repo\
cd Techno-blog

# Install Django in the system
pip install django

 Install necessary Python packages \
pip install -r requirements.txt

\ Create the database and perform all migrations \
\ Database file "thetechblog.sqlite3" will be created \
python manage.py migrate

Start the server \
python manage.py runserver
