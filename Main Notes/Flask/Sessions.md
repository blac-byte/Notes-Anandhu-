
Made - 2025-09-05                     Time - 22:01

status : 
tags : [[flask]]

# <u>Sessions</u>

Basically cache data that is encrypted and saved in the client browser about the user which gets deleted when the session ends.

_Session memory timeline, how long the cache is to be stored_
```python
from datetime import timedelta
app.permanent_session_lifetime=timedelta(days=3)
```
_Or to make the cache permanent_
```python
session.permanent=True
```
# cookies, sessions, token


# References