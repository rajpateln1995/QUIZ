# Django School


This is an example project to illustrate an implementation of multiple user types. In this Django app, teachers can create quizzes and students can sign up and take quizzes related to their interests.


Read the blog post [How to Implement Multiple User Types with Django](https://simpleisbetterthancomplex.com/tutorial/2018/01/18/how-to-implement-multiple-user-types-with-django.html).

## Running the Project Locally

First, clone the repository to your local machine:

```bash
git clone https://github.com/sibtc/django-multiple-user-types-example.git
```

Install the requirements:

```bash
pip install -r requirements.txt
```

Create the database:

```bash
python manage.py migrate
```

Finally, run the development server:

```bash
python manage.py runserver
```

The project will be available at **127.0.0.1:8000**.


## License

The source code is released under the [MIT License](https://github.com/sibtc/django-multiple-user-types-example/blob/master/LICENSE).
