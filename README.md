# servaMap

## Local Deployment

> 1. Clone the repository to a local directory; the directory servaMap will be created
> 2. To start python virtual environment, create a new directory and cd into it
```
 mkdir test, cd test
```
> 3. Install and Create a virtual environment
```
 python3 -m pip install virtualenv
 virtualenv venv -p python3
```
> 4. Activate Virtual Environment
```
 source venv/bin/activate
```
> 5. Install Django
```
 pip install django
```
> 6. Install Django crispy forms
```
 pip install django_crispy_forms
```
> 7. Install GeoJson
```
 pip install geojson
```
> 8. To run the environment, cd back to the original directory that holds servaMap
> 9. cd into the servaMap directory
```
 python manage.py runserver
```
> 10. Click on the link that will pop up (http://127.0.0.1:8000/)
