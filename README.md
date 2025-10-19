
<div style="flex: 5; text-align: right;" align="right">
    <img height="100" src="assets/img/kanade.jpeg" alt="kanade" /><br />
    <img height="100" src="assets/img/mafuyu.jpeg" alt="mafuyu" /><br />
    <img height="100" src="assets/img/miku.jpeg" alt="miku" /><br />
    <img height="100" src="assets/img/mizuki.jpeg" alt="mizuki" /><br />
    <img height="100" src="assets/img/ena.jpeg" alt="ena" />
</div>

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
