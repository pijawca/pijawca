![logo](https://i.imgur.com/x0yM7Pa.png)

![code](https://img.shields.io/badge/Code-Python-informational?style=flat&logo=python&logoColor=white&color=6aa6f8)
![platform](https://img.shields.io/powershellgallery/p/DNS.1.1.1.1)
![pypi](https://img.shields.io/pypi/pyversions/py)
[![github](https://img.shields.io/github/followers/pijawca?style=social)](https://github.com/pijawca)

```python
import sqlite3

def main():
    connection = sqlite3.connect("pijawca.db") 
    cursor = connection.cursor()
    print (cursor.execute(f"SELECT * FROM user VALUES(?, ?)").fetchall())

def hack():
    pass #TODO

if __name__ == '__main__':
    main()
    
>>> {'name': 'Porotnikov Ilya', 'age': '24', 'skill': 'Amateur', 'mainWork': 'Welder and Electrician', 'language': 'ru-RU, en-US'}
```
---
| Repo name                       | Status                                                                                                                                              | Private   | WORK            |
|---------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|-----------|-----------------|
| **auto-#############-########** | [![badge](https://img.shields.io/github/last-commit/pijawca/auto-participation-lolzuguru)](https://github.com/pijawca/auto-participation-lolzuguru) | **TRUE**  | **NEED UPDATE** |
| **pijawcabot**                  | [![badge](https://img.shields.io/github/last-commit/pijawca/pijawcabot)](https://github.com/pijawca/pijawcabot)                                     | **TRUE**  | **STABLE**      |
| **radiophonebot**               | [![badge](https://img.shields.io/github/last-commit/pijawca/radiophonebot)](https://github.com/pijawca/radiophonebot)                               | **FALSE** | **STABLE**      |
| **##############**              | [![badge](https://img.shields.io/github/last-commit/pijawca/lolzothronebot)](https://github.com/pijawca/lolzothronebot)                                          | **TRUE**  | **NEED UPDATE** |

_update 04.04.22_
