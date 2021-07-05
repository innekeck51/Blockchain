# Blockchain
learn about blockchain, with a simple case

#Istallation
1. Install Python 3.6+
2. Install [pipenv](https://github.com/kennethreitz/pipenv)
```Python
pip install pipenv
```
3. Install requirements
```Python
pipenv install
```
4. Run the server:
- ``` pipenv run python blockchain.py```
- ``` pipenv run python blockchain.py -p 5001```
- ``` pipenv run python blockchain.py --port 5002```
#Docker
Intruction to create a local Docker container:
1. Clone this respository
2. Build the docker container
```shell
docker build -t blockchain .
```
3. Run the container
```shell
docker run --rm -p 80:5000 blockchain
```
4. How to add more instance, with public port number before the colon:
```shell
docker run --rm -p 81:5000 blockchain
docker run --rm -p 82:5000 blockchain
docker run --rm -p 83:5000 blockchain
```
