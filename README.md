# django-db-logs
Django database hits logging 

## Easy log db queries on django shell
```python
import logging
l = logging.getLogger('django.db.backends')
l.setLevel(logging.DEBUG)
l.addHandler(logging.StreamHandler())
```
