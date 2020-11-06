<h2 "align=center">Hi, I'm Akarata welcome to my github profile 👋</h2>

<img src="https://telegra.ph/file/2f5ab3ce4a6844b91befd.jpg">

<h3 align="center"><b>Built with ♥ </b></h3><br>




<h3 align="center"><b>My Music Activity :</b></h3><br>
<p align="center">
  <a href="https://open.spotify.com/user/31cp7hzra2mdsswfwdt3v3xst6re?si=_FwOYKYoTKW7VweXV3a4bQ" > <img src="https://spotify-github-profile.vercel.app/api/view?uid=31cp7hzra2mdsswfwdt3v3xst6re&cover_image=true&theme=novatorem" alt="Spotify-Now" /></a><br>
  <a href="https://open.spotify.com/user/31cp7hzra2mdsswfwdt3v3xst6re?si=_FwOYKYoTKW7VweXV3a4bQ" > <img src="https://spotify-recently-played-readme.vercel.app/api?user=31cp7hzra2mdsswfwdt3v3xst6re&width=400" alt="Spotify-Recent" /></a>
  <a href="https://www.last.fm/user/Akarata" > <img src="https://lastfm-recently-played.vercel.app/api?user=Akarata" alt="Last.FM" /></a>
</p>

<br>
<p align="center"><a href="https://github.com/Akarata"><img src="https://github-readme-stats.vercel.app/api?username=Akarata&show_icons=true&theme=radical"></a></p>


<p align="center"><a href="https://github.com/Akarata"><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Akarata&theme=highcontrast&layout=compact"></a></p>



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
