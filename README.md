# django3-bootstrap5-template

My first attempt to create a starter template for django

## Versions

- django 3.2.10
- bootstrap 5.1.3

## tl;dr

Assuming you have already created a virtual environment(venv) and activated it:

```python
django-admin startproject kamehameha --template https://github.com/devadalberto/django3-bootstrap5-template/archive/refs/heads/main.zip
```

```python
cd kamehameha
```

```python
pip install -r requirements/dev.txt
```

```python
python manage.py makemigrations
```

```python
python manage.py migrate
```

```python
python manage.py runserver
```

And you should see something like this:

![kamehameha_demo_startup](https://user-images.githubusercontent.com/18197046/145336560-087a2249-3ca1-42cd-8b7e-28abe3b790fa.png)

### More Details

... coming soon

### ToDo

- [x] Create an accounts application to expand the user model
- [x] Create README that can actually be used to copy and paste
- [ ] Document how to change DB (basically changing from dev to test or prod configs)
- [ ] Make a similar template with different css frameworks (SemanticUI / TailwindCSS)
