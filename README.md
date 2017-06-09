# pycopa
A dead simple python module to parse command line arguments

```py
from pycopa import parse
parse("/say This is a test number:one done:true")

# result
{ "command": "say",
  "arg": "This is a test",
  "number": "one", "done": "true" }
```