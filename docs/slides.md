<!-- .slide: data-auto-animate -->

# Context Managers

---
<!-- .slide: data-auto-animate -->

#### A context manager is an object that properly sets up and tears down a resource.

---
<!-- .slide: data-auto-animate -->

#### It's commonly used with `with` statement.

---
<!-- .slide: data-auto-animate data-filename="main_context.py"-->


```python
with open("data.txt", "r") as file:
    data = file.read()
```

```bash
$ python3 main.py
Context manager demo executed successfully!
```