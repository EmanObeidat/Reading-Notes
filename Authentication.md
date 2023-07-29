## Q1:What is the primary purpose of JSON Web Tokens (JWTs) and how do they work in terms of encoding and decoding data?

```
JSON Web Tokens (JWTs) serve as a secure way to transmit information between parties in a compact and self-contained format. The primary purpose of JWTs is to authenticate and authorize users or entities, enabling them to access certain resources or perform specific actions within an application or system. They are commonly used in web applications, APIs, and single sign-on (SSO) implementations.

A JWT consists of three parts separated by dots: a header, a payload, and a signature. Each part is base64-encoded and combined to form the token



When the recipient receives the JWT, they can validate the signature by using the same secret key and the same algorithm used by the issuing party. After validation, the recipient can decode the payload and access the information contained in the token.

It's essential to keep the secret key secure, as anyone with access to the key can create and tamper with JWTs, potentially compromising the security of your application.
```



## Q2:How does JWT Authentication integrate with Django REST Framework to secure API endpoints, and what are the key components involved in this process?
JWT authentication can be integrated with Django REST Framework (DRF) to secure API endpoints, allowing users to access protected resources only if they have a valid JWT

**The key components involved in this process include:**

```
1.Django REST Framework (DRF):DRF is a powerful and flexible toolkit for building Web APIs in Django. It provides various authentication classes, including JWT authentication, to secure API endpoints.

2.djangorestframework_simplejwt:
To implement JWT authentication in DRF

3.Settings Configuration:
In your Django project's settings file (settings.py), configure the authentication classes for DRF to include JWT authentication.

4.Obtaining JWT Tokens:
To obtain a JWT token, users need to authenticate by providing valid credentials (usually a username and password) to a designated login endpoint.

```

## Q3:Why is Django’s built-in runserver not suitable for production environments, and what are some alternative server options that should be considered for deploying a Django application?

When deploying Django in a production environment, it's also essential to configure your server with appropriate settings, such as enabling HTTPS, setting up caching, load balancing, and implementing security measures to protect your application from various threats.

Always ensure that your production environment is set up securely and efficiently to handle real-world traffic and to provide a reliable and smooth experience for your users.

**Django's built-in development server, runserver, is not suitable for production environments for several reasons:**
```
-Limited Features and Performance
-Single-Threaded:meaning it can only handle one request at a time. In a production environment with multiple concurrent requests, this can lead to poor performance and slow response times.
-No Automatic Restart
-Lack of Security Features

```