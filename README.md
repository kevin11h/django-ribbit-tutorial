# Hello, Django!

I'm following up on the Ribbit Django 2013 tutorial from [code.tutsplus.com](http://code.tutsplus.com/tutorials/building-ribbit-in-django--net-29957)

some issues I've ran into:

For Part 1
* [pip needs to be upgraded](https://meejah.ca/blog/pip-install-layout)
* django needed to be down-graded to 1.6 (i.e. sudo ./ribbit_env/bin/pip install -U Django==1.6)
*  'django.middleware.security.SecurityMiddleware', 
'django.contrib.auth.middleware.AuthenticationMiddleware', and
'django.contrib.auth.middleware.SessionAuthenticationMiddleware' needed to be commented out