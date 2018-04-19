---
title:  "Code"
layout: archive
permalink: /code/
author_profile: true
comments: true
---

Singularity-level Function

```python
def tgca():
  return ''.join(['A','C','G','T'][::-1])
```

```python
sorted(list(tgca()))[::-2]
```
    ['T', 'C']