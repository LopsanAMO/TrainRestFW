# TrainRestFW
Versión arrglada de RestFrameworkTraining

### Guía de instalación.

#### Clona el proyecto.
```
git clone https://github.com/omarsalazar/TrainRestFW
cd TrainRestFW
```

#### Entorno virtual

Instalación del entorno.
```
pip3 install virtualenv
```
Creación del entorno virtual.
```
virtualenv -p python3 myvenv
```
Activación.
```
source myvenv/bin/activate
```

#### Instalación de dependencias.
```
pip3 install -r requirementos.txt
```
### Ejecuta el proyecto.
```
python3 manage.py migrate
python3 manage.py runserver 0.0.0.0:8000
```
