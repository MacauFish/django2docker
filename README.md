# django2docker
deploy django app on docker

step1 "docker-compose run web django-admin startproject mysite1 ."  创建mysite1
<br>
step2 modify mysite1/settings.py ALLOWED_HOSTS = [] 改成 ['*']
<br>
step3 "docker-compose up -d" 在后台运行容器
<br>
step4 "docker-compose exec web python3 manage.py startapp app1"  创建app1
<br>
