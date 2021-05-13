# Markdown **101**.

## Headers.

To add two first headers are two syntax ways for display:
- First syntax form.

  ```md
  First level header
  ==================

  Second level header
  ------------------
  ```
- Second syntax form.

  ```md
  # First level header

  ## Second level header
  ```

and both showing same output:

> <h1> First level header </h1>
> <h2> Second level header </h2>

To add more header levels its only necessary add `#` as shown:
```md
### Third level header
#### Fourth level header
```
output:
> <h3> Third level header </h3>
> <h4> Fourth level header </h4>

## Emphasis.

This table is taken from the [Markdown guide](https://colab.research.google.com/notebooks/markdown_guide.ipynb#scrollTo=70pYkR9LiOV0) on Google Colab.

Markdown | Preview
--- | ---
`**bold text**` | **bold text**
`*italicized text*` or `_italicized text_` | *italicized text*
`` `Monospace` `` | `Monospace`
`~~strikethrough~~` | ~~strikethrough~~

## Lists
Enumerated list.
```
1. Computer
2. Keyboard
3. Mouse
```
output:
<ol>
<li> Computer </li>
<li> Keyboard </li>
<li> Mouse </li>
</ol>

Bullet list.
```
- Computer
- Keyboard
- Mouse
```
output:
<ul>
<li> Computer </li>
<li> Keyboard </li>
<li> Mouse </li>
</ul>

## Links

Link without title.
```md
To go the Github page click [here](https://github.com/)
```
output:
> To go the Github page click [here](https://github.com/)

Link with title.
```md
To go the Github page click [here](https://github.com/ "Github Home")
```
output:
> To go the Github page click [here](https://github.com/ "Github Home")

File in repository.
```md
To see the code file click [here](../master/path/to/file)
```

## Images

Inline image without title.
```md
![Github logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Logo.png)
```
output:

![Github logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Logo.png)

Inline image with title.
```md
![Github logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Logo.png "Github Logo")
```
output:

![Github logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Logo.png "Github Logo")

Inline image file in repository.
```md
![txt](../master/path/to/img)
```

## Code

To showing a code block use this syntax
````
```python
  def sum(a, b):
      return a + b
```

```cpp
  void sum(int a, int b) {
      return (a + b)
  }
```
````
output:
```python
  def sum(a, b):
      return a + b
```
```cpp
  void sum(int a, int b) {
      return (a + b);
  }
```

## References
- [Markdown Basic Syntax](https://www.markdownguide.org/basic-syntax/)
