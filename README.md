# Building Python Packages

## What is  a Python package?
A **module** can contain multiple objects, such as classes, functions, etc.
A **package** can contain one or more relevant modules.

A package is a directory of Python modules that contains an additional __init__.py file, which distinguishes a package
from a directory that is supposed to contain multiple Python scripts. 

### Benefits of Python Packages
Python provides some of the advantages of using python packages:

- Naming conflicts can be solved easily.
- We can identify our components uniquely.
- Improves the Modularity of the application.
- The readability of the application will be improved.
- Maintainability of the application will be improved.

###Structure
- **Step 1**: Create an app folder
- **Step 2**: Inside `app`, create `__init__.py` empty file - to initialise our package
- **Step 3**: create `fizzbuzz.py` - add our functionality
- **Step 4**: Create `program.py` on dir level - to us as our run file
- **Step 5**: Create `setup.py` on dir level - to describe our module details such a version, author and contact detail

```
building_python_packages
--- app
--- __init_.py
--- fizzbuzz.py
program.py
setup.py
```
  