

## Open Admin Page
- Make sure [server is running](https://github.com/TrinityTerry/django-directions/blob/master/contents/run_server.md#run-server)
- 
- You should see admin's login screen

    ![Admin Login Screen](../images/admin_login_screen.png)

## Enter Admin Site
- Login with the new login information you created with `createsuperuser`
- You should see this Admin Index Page
    ![Admin Index Page](../images/admin_index.png)
- On the page, you should see a few types of editable content: groups and users. They are provided by [`django.contrib.auth`](https://docs.djangoproject.com/en/3.0/topics/auth/#module-django.contrib.auth), the authentication framework shipped by Django.
