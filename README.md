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