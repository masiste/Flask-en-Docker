# Flask-en-Docker
https://testdriven.io/blog/dockerizing-flask-with-postgres-gunicorn-and-nginx/

## Practica de contenedores con el framework Python

#### Listado de comandos para crear entorno de desarrollo de la aplicacion 
```
 mkdir services && cd services
 mkdir web && cd web
 
 mkdir project
 
 python3 -m venv env
 
 source env/bin/activate
 
 pip install flask==1.1.2
```
# Harold


$ docker-compose build

ERROR: Version in "./docker-compose.yml" is unsupported. You might be seeing this error because you're using the wrong Compose file version. Either specify a supported version (e.g "2.2" or "3.3") and place your service definitions under the `services` key, or omit the `version` key and place your service definitions at the root of the file to use version 1.
For more on the Compose file format versions, see https://docs.docker.com/compose/compose-file/


sudo apt-get remove docker-compose
sudo curl -L "https://github.com/docker/compose/releases/download/1.23.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose
