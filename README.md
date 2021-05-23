# Clone Reddit API 

- Install Anaconda;
- Create a enveronment;
  ```
  conda create --name django-api python
  ```
  ```
  conda activation django-api
  ```
- Inside of django-api create a new project
  ```
  django-admin startprojet reddit_api_project
  ```
- create a new app
  ```
  python manage.py startapp posts
  ```

  - makemigrations
  ```
  python manage.py makemigrations
  ```

  - create a new app
  ```
  python manage.py migrate
  ```
    - create a superuser
  ```
  python manage.py createsuperuser
  ```