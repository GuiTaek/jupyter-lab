# You want to pip install jupyterlab, not this

This is a stub project to prevent [dependency confusion](https://cwe.mitre.org/data/definitions/427.html)
luckily, it isn't needed as pypi itself has a basic dependency confusion protection: every ".", "-", "_" is
ignored when checking if some repository already exists. In fact, I wasn't even able to publish this package
The characters aren't ignored though when pip installing, but that's no secury issue
