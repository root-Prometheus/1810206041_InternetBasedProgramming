virtualenv yüklü değilse:
	pip install virtualenv
virtualenv oluşturmak:
	virtualenv venv

Gereklilikleri indirmek:
	pip install -r requirements.txt

Database ' i migrate etmek için 
	python manage.py migrate

Admin girişi için superuser oluşturma:
	python manage.py createsuperuser


 python manage.py runserver --> Komutu ile server çalıştırılıyor