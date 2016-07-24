# hex_scrape 

This project is so the 6 of us (hence, hex) can get a chance to work together
on something fun.

## Purposes:

1) Have a small first project for team to work on together

2) Scrape websites for potential moon-lighting work

3) Develop web application to interface scrapers and RDBMS

4) Develop web application to display this information.


## Tasks

### Client
* access website, make json/html requests
* parse json/html
* determine database schema/data format
* serialize data into common format
* send data to server application

### Server

* TCP/IP HTTP RESTful API
* Manage API keys so only certain clients can write
* RDBMS integration
  * read & write

### Requirements

* Initial development should be in python 3.5.2, the current most up to date version.
* All packages used should be pip installable and immediately added to `requirements.txt` in the proper format, like `requests==2.10.0`.
* Follow the [PEP 8](https://www.python.org/dev/peps/pep-0008/) as best as possible

