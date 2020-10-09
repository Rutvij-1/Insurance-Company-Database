# Insurance Company Database

### Authors
- [Rutvij Menavlikar](https://github.com/Rutvij-1)
- [Tejas Chaudhari](https://github.com/tejas-1111)
- [Naman Verma]()

---

This is a simple CLI interface database application for a simplified database for an insurance company implemented in python. This CLI supports functions like adding/deleting/updating an employee, customer, policy, customer dependant, employee dependent, Third Party Administrators (TPA), and also functions to get information about all dependents of a customer, finding employee/customer with name seach using partial match, etc.

---

- Steps to install docker can be found [here](https://docs.docker.com/engine/install/)
- Steps to install mysql can be found at:
    - [ubuntu users](https://www.digitalocean.com/community/tutorials/how-to-install-mysql-on-ubuntu-20-04)
    - [mac users](https://flaviocopes.com/mysql-how-to-install/)
- `python3, pymysql` are required.
    - To install `pymysql` using pip3, do `pip3 install pymysql`
---

## Steps to run:

- `Insurance_Company.sql` creates the database, the necessary tables and also populates the database with some data.

- `Insurance_Company.py` is the actual python implemented CLI code.

- use `mysql -h <local host> -u <username> --port=<port> -p < Insurance_Company.sql` to load the database. Then type the password of the user loading the database.

- use `python3 Insurance_Company.py` to start the CLI application.

- Follow the instructions on the screen.
