## I Leared A Thing Today

# Python String Translations - 7/8/2020

Create a translation using a dictionary. Indicate what to search for and what character should replace it. For example, to eliminate ( ) or , use the following translation

```python
from typing import Dict

data: str = "(this) is a test, Dennis"
translation: Dict[int, str] = str.maketrans({"(": "", ")": "", ",": ""})
result: str = data.translate(translation)
print(result)
```
