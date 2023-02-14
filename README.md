```python
#!/usr/bin/python
# -*- coding: utf-8 -*-

from github import README

class Programmer:

    def __init__(self):
        self.aliase = "Kyuubi"
        self.language = "en_GB"
        self.hobbies = ["Gaming", "Sports", "Programming"]
        self.projects = {
            "paid": {
                "earnings": 0,
                "total_projects": 0,
                "location": "unknown"
            },
            "public": {
                "total_projects": 0,
                "location": "https://github.com/Kyuubi1337?tab=repositories"
            }
        }

    def say_hello(self):
        print("Hey there, I hope you find some of my projects interesting.")

me = Programmer()
me.say_hello()
```
