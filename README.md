# REST API

## Made with Django="2.0.13" and Python="3.6.8"

## Required
+ django-tastypie

`python manage.py runserver` to start  

## Requests
+ `<POST> http://127.0.0.1:8000/api/note/ ` 

```javascript
{
    "title": <title-placeholder>,
    "content":<content-placeholder>,
    "created_at": <default= timezone.now>,
}
```

+ `<GET/PUT/DELETE> http://127.0.0.1:8000/api/note/<id>/` 

> http://localhost:8000 doesnt work (add to ALLOWED_HOST in settings.py if needed)


