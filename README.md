### Hi there 👋
### Here's A little about me👽
```python
from dataclasses import dataclass
from typing import Sequence


@dataclass(frozen=True)
class Portfolio:
    name: str = 'Anki Romeo'
    location: str = 'Switzerland'
    profile: str = 'Python-Django Developer, Linux User'
    experience: str = '3+ years'
    hobbies: Sequence[str] = 'TVs', 'Coffee', 'open source', 'clean code'
    
    
@dataclass(frozen=True)
class Skills:
    languages: Sequence[str] = 'python', 'shell', 'JavaScript',
    operation_systems: Sequence[str] = 'linux', 'Unix'
    test_frameworks: Sequence[str] = 'pytest', 'pyats', 'unittests', 'doctest', 'selenium', 'celery'
    web_frameworks: Sequence[str] = 'flask', 'django','django rest-framework', 'vue.js'
    code_quality: Sequence[str] = 'flake8', 'mypy', 'pylint', 'black', 'pydocstyle'
    devops: Sequence[str] = 'jenkins', 'docker'
    version_control: Sequence[str] = 'git'
    approaches: Sequence[str] = 'object oriented', 'asyncio'
    ongoing: Sequence[str] = 'vue.js'
    
    
@dataclass(frozen=True)
class Social:
    github: str = 'https://www.github.com/sakuira'
    twitter: str = 'https://twitter.com/anki2romeo'
    portfolio: str = 'https://sakuira.github.io'
    email: str = 'anki2romeo@gmail.com' 
  
 ````

