-----
```python
from Github import GithubReadme

class NightMare:
    def __init__(self):
        self.name = "NightMare"
        self.age = "17"
        self.location = "Not From Earth"
        self.work = "Developer, Pentester"
        self.system = "Windows 10, x64"

    def skills(self):
        self.languages = {
            "main": ["Python", "Php", "Sql"],
            "learning": ["golang", "C++"]
        }


if __name__ == "__main__":
    readme = GithubReadme.create(NightMare)
```
-----
