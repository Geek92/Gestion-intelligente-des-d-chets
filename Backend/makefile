.PHONY: init run build test

init:
	python3 -m venv env
	. env/bin/activate && pip install -r requirements.txt

run:
	. env/bin/activate && flask run

build:
	docker-compose build

up:
	docker-compose up

down:
	docker-compose down

test:
	. env/bin/activate && pytest
