
Made - 2025-09-06                     Time - 15:26

status :
tags : [[flask]]

# <u>Permanent sessions</u>

Used to extend the time that the session data gets stored in the server.

```python 
from flask import Flask, render_template, session, url_for
from datetime import timedelta
  

app=Flask(__name__)

app.permanent_session_lifetime=timedelta(days=5)
```

  

# References
[[Sessions]]