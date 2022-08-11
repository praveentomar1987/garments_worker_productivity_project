# garments_worker_productivity_project
garments_worker_productivity_project 

### Software and account requirements.

1. [Github Account](https://github.com)
2. [Heroku Account](https://id.heroku.com/login)
3. [VS Code IDE](https://code.visualstudio.com/download)
4. [Git cli](https://git-scm.com/downloads)

Creating Conda Environment
```
conda create -p venv python==3.7 -y
```

```
conda activate venv/
```
or
```
conda activate venv
```

```
pip install -r requirements.txt
```

To add files to git
```
git add .
```
OR
```
git add <file_name>
```

> Note: To ignore file or folder we can write name of file/folder in .gitignore file

To check the git status
```
git status
```
To check all versions maintained by git
```
git log
```

To create version/commit all changes to git
```
git commit -m "message"
```

To send changes/versions to git 
```
git push origin main
```

To check remote url
```
git remote -v
```

To set CI/CD pipeline in heroku we need 3 informations

1. HEROKU_EMAIL = ch.praveentomar@gmail.com
2. HEROKU_API_KEY = <>
3. HEROKU_APP_NAME = garments-worker-prod-app

BUILD DOCKER IMAGE
```
docker build -t <image_name>:<tagname> .
```
> Note: Image name for docker must be lowercase

To list docker image
```
docker images
```
RUN docker image
```
docker run -p 5000:5000 -e PORT=5000 f89e99843ab3
```

To check running containers in docker
```
docker ps
```

To stop any docker container
```
docker stop <container_id>
```

