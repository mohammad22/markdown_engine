A pygments and MathJax-aware markdown engine, for rendering code snippets,
and math formulas using mistune. How to use:


```python
from markdown import Engine
markdown = Engine()
```

And then simply apply it to the markdown text:

```python
html = markdown(markdown_text)
```

