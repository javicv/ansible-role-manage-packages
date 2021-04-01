Role Name: **manage_packages**
=========

Install or Remove system packages

Role Vars
-------
* **pakages**: A list of packages to be installed/removed

Each package has the following items:
* **name**: Package name to install/remove
* **status**: One of the following values
    * *latest* (default): The latest package version will be installed
    * *present*: Checks the package is installed or install it
    * *absent*: Remove the package

License
-------

MIT
