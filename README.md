https://github.com/lowlighter/metrics/blob/examples/metrics.plugin.isocalendar.fullyear.svg
```python
from personality_types import slacker
from universities.russia import PlekhanovUniversity
from technologies import *

class Aklto(Lazybones):
    def __init__(self):
        self.about = {
            'name': 'Vitalii Novokshonov',
            'study': PlekhanovUniversity
        }

        self.tech = [
            'NLP'
            'DataScience',
            'Python',
            'C',
            'Rust',
            'LaTeX',
            'Redis'
            'postgreSQL',
            'Git',
            'Unix',
            'Json',
        ]

if __name__ == '__main__':
    aklto = Aklto()
    print(aklto.about)
    print(aklto.tech)
```
