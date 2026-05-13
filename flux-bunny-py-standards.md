# Flux Bunny Python Style Guide

This file documents Python style guidelines I prefer.

## Function Docstrings

```python
  def function_name(param_0: type, parameter_1: type) -> int:
    """
    Function doctrings shall take the format illustrated in this
    docstring. A docstring shall contain a brief description and the
    following headings: Parameters, Side Effects, and Returns. Do not
    include a colon or hyphen after headings.

    Parameter names shall be followed by a colon. All colons shall be
    lined up in the column of the next (2-space) tab stop after the last
    character of the parameter name. One space shall be inserted between
    the colon and the description of the parameter.

    Parameters
      param_0     : Since the second parameter for this function is
                    more characters than the first, there is additional
                    whitespace for this parameter in order to line up
                    colons.
      parameter_1 : The second parameter for this function.

    Side Effects
      Creates directory.

    Returns
      type describing what the output of this function is or what it
      might be used for
    """
```

## Naming Conventions

### Variables

Variables use `snake_case` i.e. all letters are lower case with words
separated by underscores.

```python
# Good example
flux_bunny: int = max(arr)

# Bad Examples
FluxBunny: int = max(arr)
fluxBunny: int = max(arr)
```

### Constants

Constants shall be written in `ALL_CAPS` with words separated by
underscores.

```python
PI: float = 3.1415926
```
