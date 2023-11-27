# machine_learning_project
This is machine learning project from INeuron

To Start with the ML project we need:

1) [Github Account](https://github.com/)
2) Heroku Account
3) VS C0de IDE
4) GIT CLI 



Creating Conda Environment
```
conda create -p venv python==3.7 -y

```


Activate Conda Environment
```
conda activate venv/

```


Install packages from requirements.txt file
```
pip install -r requirements.txt

```

To Set up CI/CD pipeline in heroku we need 3 information
1. HEROKU_EMAIL 
2. HEROKU_API_KEY
3. HEROKU_APP_NAME



Build Docker Image 
```
docker build -t <image_name>:<tagname> .
```
> Note: Image name for docker must be in lowercase


To list docker image 
```
docker images
```


Run docker image 
```
docker run -p 8080:8080 -e PORT=8080 ddbc14215046
```

To check running container in docker 
```
docker ps
```


To stop docker image
```
docker stop <container_id>
```

