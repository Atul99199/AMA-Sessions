```md
## 1. How can you check for errors without running the server?
We can use `python manage.py check` to check for common errors in a Django project.
It checks configurations and identifies potential problems without starting the server.

## 2. What is the base command in Django?
The base command to manage a Django project is `python manage.py`.
We use it to run commands like `runserver`, `migrate`, and `createsuperuser`.

## 3. Name some databases that follow ACID properties.
PostgreSQL, MySQL (InnoDB), Oracle Database, and Microsoft SQL Server support ACID properties.
ACID stands for Atomicity, Consistency, Isolation, and Durability.

## 4. What are the three states of a promise?
The three states of a JavaScript Promise are `Pending`, `Fulfilled`, and `Rejected`.
Pending means unfinished, Fulfilled means successful, and Rejected means failed.

## 5. What is the difference between a foreign key and a primary key?
A primary key uniquely identifies each record in a table and cannot contain duplicate or NULL values.
A foreign key connects tables by referencing a key in another table.

## 6. What is `urls.py` in the root directory?
The root `urls.py` file defines the main URL patterns of a Django project.
It maps incoming URLs to views or includes URL patterns from individual apps.

## 7. What is the difference between `blank=True` and `null=True`?
`blank=True` allows a field to be left empty during form validation.
`null=True` allows the database to store `NULL` for that field.

## 8. What is `settings.py` in Django?
`settings.py` contains the project's configuration, such as installed apps, database settings, and middleware.
It also defines settings for templates, static files, and security.

## 9. What is a viewport?
A viewport is the visible area of a webpage on a device's screen.
The viewport meta tag helps a webpage adjust its layout to different screen sizes.

## 10. How does Django decide whether to use ASGI or WSGI?
Django uses the ASGI or WSGI application specified in the server configuration.
`wsgi.py` supports synchronous applications, while `asgi.py` supports asynchronous applications.

## 11. What is `JsonResponse`?
`JsonResponse` is a Django class used to send data from the server to the client in JSON format.
It is commonly used in APIs to return data that JavaScript can process.
```