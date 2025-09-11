
Made - 2025-09-05                     Time - 20:53

status :
tags : [[flask]] [[html]]

# Jinja2
____
to make a sure website, templating is very important. [Flask](https://www.geeksforgeeks.org/python/python-introduction-to-web-development-using-flask/) is supported by inbuilt template support named Jinja2. Jinja2 is one of the most used Web template engines for Python. This Web template engine is a fast, expressive, extensible templating engine. Jinja2 extensively helps to write Python code within the [HTML](https://www.geeksforgeeks.org/html/html-tutorial/) file.

# Jinja2 template logic
---
## 1) Jinja Template Variables

To declare the variable using Jinja Template we use **{{variable_name}}** within the HTML file. As a result, the variable will be displayed on the Website.
```html
{{variable_name}}
```

## 2) Jinja Template if Statements

Just like declaring the variable in the Jinja2 template, if conditions have almost similar syntax. But here we specify the beginning and end of the if block.
```html
{% if name=='Billy' %}
	<h1>name</h1> 
{% endif %}
```

## 3) Jinja Template for Loop

Jinja for loop syntax is similar to the if statements, the only difference is for loop requires sequence to loop through.

## 4) url_for' instead of hard coding URLs
---
In flask/ python : [['url_for' instead of hard coding URLs]]

In HTML :
```html
{{ url_for('static', filename='<path of the file>') }}
```

# References