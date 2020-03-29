# myst-parser[sphinx]

`myst-parser[sphinx]` is a Markdown parser (`.md` files) that allows you to
combine all the power of Markdown with all the potential of
Sphinx. All at once!


```{note} This whole page is written in Markdown (see [Show Source](https://sphinx-extensions.readthedocs.io/en/latest/_sources/myst-parser.md.txt)).

As you can see, Sphinx extenions continue working without any customization.
```

% I had to add an absolute link, because I didn't find how to make it relative


## Installation

```bash
pip install myst-parser[sphinx]
```


## Configuration


```python
# conf.py
extesions = [
    '...',
    'myst_parser',
]
```