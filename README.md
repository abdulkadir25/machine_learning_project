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


Build Docker Image 
```
docker build -t <image_name>:<tagname> .
```
> Note: Image name for docker must be in lowercase


To list docker image 
```
docker images
```
