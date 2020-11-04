### Hi there 👋

<img src="https://camo.githubusercontent.com/992babdffd8c74a1502de375fbdf7e4d54773242/68747470733a2f2f6d656469612e67697068792e636f6d2f6d656469612f53576f536b4e36447854737a71494b4571762f67697068792e676966" width="495px">

```python3

from dataclasses import dataclass
from typing import Tuple


class Meta(type):
    def __new__(cls, name, bases, attrs):
        for attr in attrs:
            if not attr.startswith("_"):
                __annotations__[attr] = Tuple[str, ...]
        attrs["__annotations__"] = __annotations__
        new_cls = super().__new__(cls, name, bases, attrs)
        new_cls = dataclass(new_cls)
        return new_cls


class Stack(metaclass=Meta):
    languages   = ("Python", "Bash")
    ongoing     = ("C")


print("A little more about me")

Akarata = {
    'pronouns': 'he' or 'him' or 'his',
    'fullname': 'Prastiko Sasmitho',
    'nationality': ['Indonesia', 'ID'],
    'location': 'ID',
    'contact': {
        'email': 'Prastiko46@gmail.com',
        'website': 'https://gmail.com',
    },
    'about': [
        '16 y.o' ,
        'A student',
        'A fan of python',
        'I\'m considering myself as a runner. (even tho rarely do it) xd',
        'Love gaming',
        'Human.',
        'If i'm born again i just want to be myself'
    ],
    }
```
