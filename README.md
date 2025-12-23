
git clone https://github.com/Vaishnav-188/METAZORD_IT_TEAM.git  

python -m venv env

env\Scripts\activate

cd Farmer

pip install -r requirements.txt

python manage.py makemigrations
python manage.py migrate


python manage.py createsuperuser


python manage.py runserver


