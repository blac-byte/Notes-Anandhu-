
Made - 2025-09-10                     Time - 14:02

status :
tags : [[flask]]

# <u>Overriding Form action and Form method</u>

```python
<form id="myForm" method="POST">
    <input type="text" name="data" placeholder="Enter something">

    <!-- Button 1: submit via GET -->
    <button type="submit" formaction="{{ url_for('dashboard') }}" formmethod="GET">
        Submit with GET
    </button>

    <!-- Button 2: submit via POST -->
    <button type="submit" formaction="{{ url_for('dashboard') }}" formmethod="POST">
        Submit with POST
    </button>
</form>

```

- `formaction` → overrides the form’s `action` for this button.
    
- `formmethod` → overrides the form’s method (`GET` or `POST`) for this button.



# References

[[Methods - GET and POST]]