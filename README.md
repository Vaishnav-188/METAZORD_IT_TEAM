Project name : Farmer support system

Description :
    This project's End user is Farmers , Merchants.
    It allows below Features :
    Features :
        Irrigations tips
        Business 
        weather update
        Disease control type
        Account

1.clone the repo;

git clone https://github.com/Vaishnav-188/METAZORD_IT_TEAM.git

2.Create environment: 

python -m venv env
env\Scripts\activate

3.Change directory - farmer:

cd Farmer

4.Install requirements:

pip install -r requirements.txt

5.Migrations:

python manage.py makemigrations 
python manage.py migrate

6.Create Superuser:

python manage.py createsuperuser

7.Run command:

python manage.py runserver
