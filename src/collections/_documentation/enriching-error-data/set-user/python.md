```python
from sentry_sdk import configure_scope

with configure_scope() as scope:
    scope.user = {"email": "{{ page.example_user_email }}"}
```
