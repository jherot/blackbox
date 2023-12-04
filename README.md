
# Blackbox

[Blackbox](https://en.wikipedia.org/wiki/Black_box) is a Python library for analyzing algorithms in terms of time, space, and [determinism](https://en.wikipedia.org/wiki/Deterministic_algorithm). Its development is intended to facilitate research in theoretical computer science, primarily the [P versus NP problem](https://en.wikipedia.org/wiki/P_versus_NP_problem).

## Install

To install the current release:

```
pip install blackbox
```

To update Blackbox to the latest version, add the `--upgrade` flag to the above commands.

#### *Run your first Blackbox program*

```python
>>> import blackbox as bx
>>> bx.order(mergesort)
O(n log(n))
```

For more examples, see the [documentation](/Documentation/index.md).
