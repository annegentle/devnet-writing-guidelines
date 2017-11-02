Not reinventing the excellent work that has already been put forth by the Python development community, nor seeking create our own style for Python code, we adopt the community developed [PEP 8 - Style Guide for Python Code](https://www.python.org/dev/peps/pep-0008/).

The guidance contained herein is provided to bring consistency to our processes, tools and practices when creating Python code for learning and use case development.


# Version

While specific instances and use cases may require the use of Python v2, and therefore should certainly do so, all other uses and all new development should default to using **Python v3** (testing against the latest releases is recommended).


# Style & Linting

We follow the [PEP8](https://www.python.org/dev/peps/pep-0008/) style guide, and the following points are to be highlighted and considered mandatory _(like we could make you do anything...)_:

* Indentation - 4 spaces
* Comments & Documentation Strings
  * See the [examples](https://www.python.org/dev/peps/pep-0008/#comments)
  * When describing what a script, module, function, class and etc. does - use Python's built-in Documentation Strings rather than block or inline comments.
* [Naming Conventions](https://www.python.org/dev/peps/pep-0008/#naming-conventions)

_"Beautiful is better than ugly."_

These practices (and the rest of the PEP8 style recommendations) net-out in an improved user experience for all those who read, modify and troubleshoot the code we publish.

## Linting

To make writing PEP8-clean code easier, we recommend that you use an IDE or editor that provides real-time Python linting.  It is easier to write clean code as you are writing it rather than having to come back and clean up linting errors later.

**Recommended Linter:**  `flake8`

Many IDEs can leverage a user supplied linter, in these cases we recommend and use [flake8](http://flake8.pycqa.org/en/latest/).  You can also use it as a command line tool to check your code before posting.

**Installation:**
``` bash
$ pip install flake8
$ flake8 <your-script-or-code-directory>
```


# Early Learning Tools

| Need | Tool |
| --- | --- |
| Python Interpreter | [CPython](https://www.python.org/) |
| Editor / IDE | [IDLE](https://docs.python.org/3/library/idle.html) |
| Environment / Package Management | [virtualenv](https://virtualenv.pypa.io/en/stable/) |
| Shell / Script Execution | BASH |
| Debugging | Python Stack Traces, print() Statements, Interactive Interpreter |
