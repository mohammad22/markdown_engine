A  [pygments](http://http://pygments.org/) and  [MathJax](https://www.mathjax.org/)-aware markdown engine, for rendering code snippets,
and math formulas using [mistune](http://mistune.readthedocs.org/en/latest/). How to use:


```python
from markdown import Engine
markdown = Engine()
```

And then simply apply it to the markdown text:

```python
html = markdown(markdown_text)
```

