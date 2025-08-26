.PHONY: install migrate run collectstatic test

    install:
	pip install -r requirements.txt

    migrate:
	python manage.py migrate

    run:
	python manage.py runserver 0.0.0.0:8000

    collectstatic:
	python manage.py collectstatic --noinput

    test:
	python manage.py check
