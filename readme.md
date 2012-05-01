# Irregular
*The Alternate Python Regular Expression Wrapper*

Currently a very barebones wrapper around the Python re standr lib,
more functionality to be added as needed.

## Usage
```python
>>> from irregular import re
>>> regex = re(r'(\w+), (\w+), (\w+)').match('one, two, three')
>>> regex[0]
'one, two, three'
>>> regex[1]
'one'
```