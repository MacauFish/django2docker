# django2docker
deploy django app on docker

step1 "docker-compose run web django-admin startproject mysite1 ."
step2 modify mysite1/settings.py ALLOWED_HOSTS = [] to ['*']
step3 "docker-compose up
