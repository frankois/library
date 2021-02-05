# Library

This repository is used as a template to structure python libraries for my projects.

The initial structure is as follow:

```bash
library/
├── README.md
├── data
│   ├── pkg1
│   └── pkg2
├── docs
│   ├── pkg1.md
│   └── pkg2.md
├── library
│   ├── __init__.py
│   ├── pkg1
│   │   ├── __init__.py
│   │   ├── pkg1_mod1.py
│   │   └── pkg1_mod2.py
│   └── pkg2
│       ├── __init__.py
│       ├── pkg2_mod1.py
│       └── pkg2_mod2.py
└── tests
    ├── pkg1
    │   └── pkg1_test.py
    └── pkg2
        └── pkg2_test.py
```

`data/` folder can be set to stay private by commenting out the corresponding line in `.gitignore`.

As source of inspiration, I used my personal experiences and the following links:
- https://docs.python-guide.org/writing/structure/
- https://packaging.python.org/tutorials/packaging-projects/
- https://dev.to/codemouse92/dead-simple-python-project-structure-and-imports-38c6
- https://realpython.com/python-application-layouts/
- https://realpython.com/python-modules-packages/
- https://realpython.com/lessons/scripts-modules-packages-and-libraries/