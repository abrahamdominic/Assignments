
## Task Title: Week 4 Python Task: Pip, Virtual environments and intro to Django
In this project i modify my models.py file inside the “musicapp” application we created,
in week 4 task.
The following Models and Attributes were added to the model.

Model: Artiste, Song, Lyric

Attributes for “Artiste” : first_name, last_name, age

Attributes for “Song” : title, date released, likes, artiste_id

Attributes for “Lyric”: content, song_id

And i specify the foreignkey relationship between the models.


## Run Locally

Clone the project

```bash
  git clone https://github.com/abrahamdominic/assignment.git
```

Go to the project directory

```bash
  cd https://github.com/abrahamdominic/assignment/tree/week5/songcrud
```

Install dependencies

```bash
  py -m pip freeze > requirement.txt
```

Start the server

```bash
  py manage.py runserver
```


## Design

This project was designed using visual studio code



## FAQ

#### What is model?

A Django model is a table in your database. 
SQLite Database. When we created the Django project, 
we got an empty SQLite database.
Django was design to follow the pattern MVT (Model View Template)

## Authors

- [@AbrahamDominic](https://www.github.com/abrahamdominic)

