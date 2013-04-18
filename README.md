# Django Stormapth API integration

A Django application that uses Stormpath SDK API calls to provide authentication and access controls.

## Installation and requirements

The only requirement needed to run django-stormpath is stormpath-sdk for Python.

To install:

    # Download from GitHub
    git clone <repository>
    cd django-stormpath

    # Build
    python setup.py build

    # Install it
    python setup.py install


## Usage

Add "django_stormpath" to your INSTALLED_APPS in settings.py.

Add "django_stormpath.backends.StormpathBackend" to AUTHENTICATION_BACKENDS in settings.py
