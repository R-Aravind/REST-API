# REST API

`python manage.py runserver` to start  

`<GET/POST/PUT/DELETE> http://127.0.0.1:8000/api/note/ ` Requests

> http://localhost:8000 doesnt work (add to ALLOWED_HOST in settings.py if needed)

```javascript
Objects:
{
    "title": <title-placeholder>,
    "content":<content-placeholder>,
    "created_at": <default= timezone.now>,
}
```
