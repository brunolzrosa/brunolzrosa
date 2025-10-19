<img align="right" height="300" src="assets/img/kanade.jpeg"  />
<img align="right" height="300" src="assets/img/mafuyu.jpeg"  />
<img align="right" height="300" src="assets/img/mizuki.jpeg"  />
<img align="right" height="300" src="assets/img/ena.jpeg"  />

```python
class BrunoRosa:
    def __init__(self) -> None:
        self.name: str = 'Bruno Rosa'
        self.age: int = 19
        self.interests: List[str] = [
            'VOCALOID',
            'Programming',
            'Data Science',
        ]
        self.skills: Dict[str, List[str]] = {
            'Languages': [
                'Portuguese',
                'English',
            ],
            'Programming Languages': [
                'Python',
                'JavaScript',
                'TypeScript',
                'C',
                'C++',
            ],
            'Tools': [
                'PostgreSQL (SQL)',
                'Docker',
                'Git',
            ],
        }

```