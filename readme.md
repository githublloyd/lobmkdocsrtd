# Version 1 Innovations - Database Migration - DB4C

The intention of this repository is to hold the content for the DB migration innovation.

Documentation is written in **[markdown](https://en.wikipedia.org/wiki/Markdown)** and built with **[mkdocs](http://www.mkdocs.org/)** 

The theme is **['Material for MkDocs'](https://squidfunk.github.io/mkdocs-material/)** customised for Version 1, it is configured in the yml file.

Want to contribute to this site or use it?

    1 - Clone the site using 
        $ git clone https://<git repository name>
    2 - Run local copy of the site - You will need 'mkdocs'.
        $ cd v1-db-migration
        $ mkdocs serve

To run mkdocs on Windows:

    1 - Download and install Python 3.6 from https://www.python.org/downloads/
    2 - Open a CMD window
    3 - python --version
    4 - python -m pip install mkdocs
    5 - mkdocs --version
    6 - pip install pymdown-extensions
    7 - git clone https://<git repository name>
    8 - cd v1-db-migration
    9 - python -m mkdocs serve

| Name | Description |
| ---- | ----------- |
| docs | All documentation for this service |
| site | a copy of the site after a 'mkdocs build' - Not always there|
| .gitignore | lists files that should not be part of this repository e.g. build files |
| mkdocs.yml | The documentation is this repository is managed with the [mkdocs](http://www.mkdocs.org/)  utility. This is the configuration file for mkdocs |
| readme.md | The file you are reading now |
