# Create a Python application that sets up a phone and an end user via Soap and AXL
Use Python and the Zeep library to create an AXL application to add a new phone, directory number (line), end user, and then associate the user with the phone and line.

## Objectives
    1- Set up Python with Zeep
    2- Create a SOAP client with Python and Zeep
    3- Set up a plugin for troubleshooting
    4- Use the client session to add a new line (directory number)
    5- Use the client session to add a new phone with this line
    6- Use the client session to add a new end-user
    7- Use the client session to associate the end user with the phone and the line
    8- Learn a Zeep quirk and how to handle it
    9- Review the complete script

## Prerequisites
    1-A client operating system like Windows, Mac or Linux
    2-A CUCM server with an administrator account.
     You can use your own, or you can reserve a test server via the DevNet sandbox
    3-The Cisco AXL Toolkit
    4-Python
    5-The Python package manager, or pip (The command pip may be pip3 on Mac and Linux)
    6-Install OpenSSL if not already installed
    7-Install the zeep library, which will install automatically all its dependencies
    8-On Linux, zeep will attempt to install lxml automatically,
     but lxml requires libxml2 and libxslt, so you will need to install the libxml2-dev and libxslt-dev packages.

## Installation
Use the package manager [pip](https://pip.pypa.io/en/stable/) to install zeep.
```bash
$ pip install zeep
```
```bash
$ sudo apt-get install libxml2-dev libxslt-dev
```
```bash
$ sudo apt install libxml2-dev libxslt-dev
```

## Reference
[Cisco DevNet, Learning Labs Center ](https://www.cisco.com/)
