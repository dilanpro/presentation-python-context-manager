<!-- .slide: data-auto-animate -->

# Context Managers

---
<!-- .slide: data-auto-animate -->

# Context Managers
#### And Beyond

---
<!-- .slide: data-auto-animate -->

## What is a Context Manager?

- Manages setup and cleanup automatically
- Commonly used with the `with` statement

---
<!-- .slide: data-auto-animate -->

## Example

```python
with open("file.txt") as f:
    data = f.read()
