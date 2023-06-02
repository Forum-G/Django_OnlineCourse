
# Online Course Django APP

This is a full-stack online course hosting web application built with Django. Users can enroll in courses, read lessons, and take quizzes. The quiz score is also evaluated at the end.

## Database Structure
I have included a database schema for this project, which is shown below:

![Database Model](https://github.com/CodeForumizer/Django_OnlineCourse/assets/84411852/83154989-5d71-4a7e-8f43-f29d102f3846)

## Development
I have developed this web application using an existing database schema as a starting point.

If you want to contribute or further develop the project, you can clone this repository using the following command:


```bash
git clone https://github.com/CodeForumizer/Django_OnlineCourse.git
```

Install Python dependencies

```bash
pip3 install -r requirements.txt
```

Make sure to configure the settings.py file. I have configured it for deployment to Heroku, so you may need to remove the django_heroku package from requirements and adjust the database credentials accordingly.

Migrate the Django server:

```bash
python3 manage.py migrate
```

**Prerequisite**
- Python 3

Feel free to explore and contribute to the project!
