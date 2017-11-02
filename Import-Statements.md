# Import statements

Within a file it's generally a good idea to organize your import statements. We recommend alphabetical order. It's also good to separate import statements into the following categories and order:

  - Standard library imports
  - Third party imports
  - Your library imports

```Python
# standard library
import os
import re
import sys

# third party library
import pymongo
from sqlalchemy import create_engine, exceptions

# personal or private library
from mymodule import MyCustomException, models, views
```

## Patterns to avoid

Example of how NOT to import packages

```Python
import sys, os           # DO NOT import different modules on the same line
from sqlalchemy import * # DO NOT import *
from .models import util # DO NOT use relative imports (better to use fully qualified names)
```