<h2 "align=center">Hi, I'm Prastiko welcome to my github profile 👋</h2>

<img src="https://telegra.ph/file/feedfae4550df60ba2380.jpg">

<h3 align="center"><b>Built with ♥ </b></h3><br>
<h3 align="center"><b>My Music Activity :</b></h3><br>
<p align="center">
  <a href="https://open.spotify.com/user/31cp7hzra2mdsswfwdt3v3xst6re?si=_FwOYKYoTKW7VweXV3a4bQ" > <img src="https://spotify-github-profile.vercel.app/api/view?uid=31cp7hzra2mdsswfwdt3v3xst6re&cover_image=true&theme=novatorem" alt="Spotify-Now" /></a><br>
  <a href="https://open.spotify.com/user/31cp7hzra2mdsswfwdt3v3xst6re?si=_FwOYKYoTKW7VweXV3a4bQ" > <img src="https://spotify-recently-played-readme.vercel.app/api?user=31cp7hzra2mdsswfwdt3v3xst6re&width=400" alt="Spotify-Recent" /></a>
  <a href="https://www.last.fm/user/Akarata" > <img src="https://lastfm-recently-played.vercel.app/api?user=Akarata" alt="Last.FM" /></a>
</p>
<h3 align="center"><b>My github stats :</b></h3><br>

[![Akarata's github stats](https://github-readme-stats.vercel.app/api?username=Akarata&count_private=true&show_icons=true&theme=vue-dark)](https://github.com/Akarata)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Akarata&count_private=true&layout=compact&theme=vue-dark)](https://github.com/Akarata)


![visitors](https://visitor-badge.laobi.icu/badge?page_id=Akarata)

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FAkarata&count_bg=%231EE510&title_bg=%23555555&icon=&icon_color=%23931414&title=account+views&edge_flat=false)](https://hits.seeyoufarm.com)

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
    'location': 'Jakarta,ID',
    'contact': {
        'email': 'prastiko46@gmail.com',
        'website': 'https://gmail.com',
    },
    'about': [
        '18 y.o' ,
        'A fan of python',
        'I\'m considering myself as a runner. (even tho rarely do it) xd',
        'Love editing & design',
        'Human.',
        'If i\'m born again i just want to be myself'
    ],
    }
```
