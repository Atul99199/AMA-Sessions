## 1. What is `ALLOWED_HOSTS`?
`ALLOWED_HOSTS` tells Django which domain names or hosts are allowed to access the application.
It helps prevent requests from unknown or unsafe hosts.

## 2. What is the difference between a primary key and a foreign key?
A primary key uniquely identifies each record in a table.
A foreign key is used to connect one table with another table.

## 3. What does `build.sh` do?
`build.sh` is a shell script that contains commands needed to build or set up a project.
It allows us to run multiple commands together instead of running them one by one.

## 4. What is a closure?
A closure is a function that remembers variables from its outer function.
It can still use those variables even after the outer function has finished.

## 5. What is clickjacking?
Clickjacking is an attack where a user is tricked into clicking something different from what they see.
It can make the user perform an action without knowing it.

## 6. What is a CSRF token?
A CSRF token is a security token used to check that a request is coming from the correct website.
Django uses it mainly to protect forms and POST requests.

## 7. What is the difference between `get()` and `filter()` in Django?
`get()` is used when we expect only one object from the database.
`filter()` is used when we want to get multiple objects and returns a QuerySet.

## 8. What is a 400 error?
A 400 error means the server cannot understand or process the request.
It usually happens when the request contains invalid or incorrect data.

## 9. What is the event loop?
The event loop helps JavaScript handle asynchronous tasks like timers, API calls, and events.
It allows JavaScript to continue running other code instead of waiting for these tasks.

## 10. What is `dj_database_url` in Django?
`dj_database_url` is a package that helps Django configure the database using a database URL.
It is commonly used with environment variables such as `DATABASE_URL`.