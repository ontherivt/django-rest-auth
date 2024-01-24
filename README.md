# Welcome to django-rest-auth
Django-rest-auth provides a set of REST API endpoints for Authentication and Registration

The original [django-rest-auth](https://github.com/Tivix/django-rest-auth) package is no longer maintained. This repo is a fork of the original, updated for use with Django >= 4.

# Updates for Django >= 4

* `django.conf.urls.url` is deprecated in Django >= 4. This fork has been updated to use `django.urls` and `re_path`. ([docs](https://docs.djangoproject.com/en/dev/internals/deprecation/#deprecation-removed-in-4-0))
* `django.utils.encoding.force_text` is deprecated in Django >= 4. This fork has been updated to use `django.utils.encoding.force_str`. ([docs](https://docs.djangoproject.com/en/dev/internals/deprecation/#deprecation-removed-in-4-0))
* `django.utils.translation.ugettext_lazy` is deprecated in Django >= 4. This fork has been updated to use `django.utils.translation.gettext_lazy`. ([docs](https://docs.djangoproject.com/en/dev/internals/deprecation/#deprecation-removed-in-4-0))


# Documentation
* http://django-rest-auth.readthedocs.org/en/latest/


# Source Code
* Original - https://github.com/Tivix/django-rest-auth
* Fork - https://github.com/phelanjo/django-rest-auth


# Stack Overflow
* http://stackoverflow.com/questions/tagged/django-rest-auth
