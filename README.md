# Northflank Python Django template

<a target="_blank" rel="noopener noreferrer" href="https://www.northflank.com">
    <img alt="Northflank" align="right" src="/media/logo.svg" width="35%" />
</a>

Deploy this Python Django server easily with [Northflank](https://www.northflank.com):

- [Create a service from template on Northflank](https://app.northflank.com/s/project/create/template-service)
- Select the Python Django template
- Wait for the app to build and visit the newly assigned URL. That's it!

You can now clone your repository locally and start making changes. Push your changes to automatically build and deploy the updated application!

[Learn more about using Northflank](https://northflank.com/docs/).

#### Authorizing hosts

This application has been configured to [authorize hosts](https://docs.djangoproject.com/en/4.1/ref/settings/#allowed-hosts) passed via the environment variable `NF_HOSTS`. You can change this, if necessary, by manually setting the environment variable or changing `ALLOWED_HOSTS` in the Ruby environments in `example/settings.py`.

### Live demo
[https://example--python-django--examples--nort-kcwl.code.run](https://example--python-django--examples--nort-kcwl.code.run)

## About Django
[Django](https://www.djangoproject.com/) is a high-level Python Web framework that encourages rapid development and clean, pragmatic design. Built by experienced developers, it takes care of much of the hassle of Web development, so you can focus on writing your app without needing to reinvent the wheel. It’s free and open source. 

## 🚀 Quick start

1.  **Install packages.**

    ```shell
    pip install -r requirements.txt
    ```

    Make sure you are using Python 3.11 or above.

1.  **Start developing.**

    Navigate into your new site’s directory and start it up.

    ```shell
    python manage.py runserver 0.0.0.0:80
    ```

1.  **Visit your site.**

    Navigate to http://localhost and view your site while developing.
