
Made - 2025-09-03                     Time - 21:50

status :
tags : [[flask]]

# <u>Methods</u>

Flask uses GET and POST to understand the orders given by a browser.
```python
@app.route('/',methods=['POST','GET'])
def index():
    if request.method=='POST':
        pass
    else:
        return render_template('index.html') 
        ```






# References