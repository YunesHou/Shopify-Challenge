# Shopify Challenge
This is Shopify Developer Intern Challenge for Yu Hou. The website is created by Django to realize CRUD functions. User can use this website to upload their images with title and description. And the image model will help user to save their images' title, description, and the real time they uploaded it. Not only we can use 'create' function, but also 'update' and 'delete' functions. For each image, users can edit their title, description and even cahnge the image. If users don't want to save any image anymore, then they can delete the image by clicking the delete button.

# How to use
To install Django, First you need to have Python Installed in your pc/laptop. Django can be easily installed using pip. If you have python 3.4, pip is included with it.
```bash
python -V

python -m pip --version

pip install django
```
To run/execute the project.
```bash
python manage.py migrate

python manage.py runserver
```
Then type the url in the search bar like "http://localhost:8000/"

You can start the journey by clicking 'ADD A NEW IMAGE' button to upload your first image.

# In the future
In the future, if I had more time, I would add the ability to search for images, so that users can find photos faster. Secondly, I will add a "category" attribute to the images, so that they can be organized, so that you can find the images you want both by searching time and by categorizing them.