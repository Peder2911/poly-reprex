# poly-reprex

This repo can be used to reproduce a bug in Python polylith where the deps
command fails if a component imports another component, but is not itself
imported by anything.

```
>>> # This raises an exception!
>>> rye run poly deps
```
