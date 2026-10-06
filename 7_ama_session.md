# Django and JavaScript Questions

## 1. What is `JsonResponse`?

`JsonResponse` is used in Django to send data from the server to the client in **JSON format**.  
It is commonly used when creating APIs or sending data to JavaScript.

---

## 2. What is `WhiteNoiseMiddleware`?

`WhiteNoiseMiddleware` helps Django serve **static files** like CSS, JavaScript, and images.  
It is commonly used when deploying Django applications.

---

## 3. What is `HttpResponseForbidden`?

`HttpResponseForbidden` returns an **HTTP 403 status code**.  
It is used when a user is not allowed to access a particular resource.

---

## 4. What is a Promise?

A Promise represents the result of an **asynchronous operation** in JavaScript.  
It can be **pending, fulfilled, or rejected**.

---

## 5. What is Callback Hell?

Callback hell occurs when multiple callbacks are **nested inside each other**.  
It makes the code difficult to read and maintain.

---

## 6. What does `fetch()` return?

`fetch()` returns a **Promise**.  
When the request completes, the Promise provides a `Response` object.

---

## 7. Why do we use multiple apps in Django?

Multiple apps help divide a Django project into **separate modules based on functionality**.  
This makes the project easier to organize, maintain, and scale.

---

## 8. What is the difference between a Generic Foreign Key and a normal Foreign Key?

A normal `ForeignKey` creates a relationship with **one specific model**.  
A `GenericForeignKey` can create a relationship with **objects from different models**.

---

## 9. What is the `get_or_create()` function?

`get_or_create()` first tries to find an existing object.  
If it does not exist, Django creates a new object and returns it.

---

## 10. What is the difference between `Meta` in a Django model and `Meta` in a Django form?

Model `Meta` defines **options for the model**, such as ordering and constraints.  
Form `Meta` defines the **model and fields** that should be used in the form.