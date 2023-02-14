# ML_project
this is my first machine learning project

conda create -p venv python=3.7 -y
-------
conda activate venv/
------
pip install requirements.txt
-------

to check git status
----
git status

---

to check all version maintained by git
----
git log
---
to create version/commit all changes by git
git commit -m "message"

git remote -v

to send version/changes to github

'''''git push origin main
''''''''''


runing the code  after changes

git add .
git status
git commit -m "changes saved to github"
git push origin main
-----

to setup CI/CD pipeline in heroku we need 3 information

heroku-email=vemula.sandhya51@gmail.com
heroku-api-key=6d8833c6-03c1-49ee-9af5-0b0d9945fb09
heroku-app-name=ml-project-app


BUILD DOCKER IMAGE
-----
docker build -t <image_name>:<tagnaem> .
-----

image name for docker must be lowercase

to list docker image
----
docker images
----
run docker image
---
docker run -p 5000:5000 -e PORT=5000 imageid(f8c74973678)



to check running containers in docker

---docker ps----
too stop docker container
----
docker stop <container-id>
----
