![Metrics](https://metrics.lecoq.io/https://github.com/lowlighter/metrics/blob/master/source/plugins/isocalendar/?template=classic&languages=1&isocalendar=1&base=header%2C%20activity%2C%20community%2C%20repositories%2C%20metadata&base.indepth=false&base.hireable=false&base.skip=false&isocalendar=false&isocalendar.duration=half-year&languages=false&languages.limit=8&languages.threshold=0%25&languages.other=false&languages.colors=github&languages.sections=most-used&languages.indepth=false&languages.analysis.timeout=15&languages.analysis.timeout.repositories=7.5&languages.categories=markup%2C%20programming&languages.recent.categories=markup%2C%20programming&languages.recent.load=300&languages.recent.days=14&config.timezone=Asia%2FYerevan)
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
