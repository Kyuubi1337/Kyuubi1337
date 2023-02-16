```python
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
                "total_projects": 1,
                "location": "https://github.com/Kyuubi1337?tab=repositories"
            }
        }
        self.socials = {
            "Youtube": "https://www.youtube.com/channel/UCYNv4KxXY1DjoQevfbnGsyA",
            "Reddit": "https://www.reddit.com/user/Kyuubi9669",
            "Spotify": "https://open.spotify.com/user/316jo4sabvpiivd6ti5y3bnlo3km?si=a8c47ff66ee447b2&nd=1",
            "Discord": "Kyuubi#4199"
        }

    def say_hello(self):
        print("Hey there, I hope you find some of my projects interesting.")

me = Programmer()
me.say_hello()
```
