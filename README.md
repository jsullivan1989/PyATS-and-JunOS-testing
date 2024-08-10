# PyATS and JunOS Testing
Repository for testscripts and testbeds related to the multivendor testing between PyATS and JunOS.  

PyATS is a Python testing framework which was developed internally at Cisco.  Later on, it was made open source and is now used far and wide for network test automation.

Since PyATS was made open source, it features multi-vendor parsing allowing it to parse unstructed data into structured data across multiple different vendors.  This repository focuses on its interoperability with JunOS.  If one is interested in taking a deeper dive into PyATS, I HIGHLY recommend _Cisco pyATS -- Network Test and Automation Solution_ by  Capobianco and Dan Wade in order to understand the details of the Object Oriented Python approach to PyATS.

The first step is to create a virtual environment to house your testbed and testscripts.  Run the command below to create a virtual environment with python3.

`cd /path/`

`python3 -m venv {virtual environment name}` 

Next activate the virtual environment.

`source {virtual environment name}/bin/activate`

Install the pyATS packages 

`pip install pyats[full]`

![](https://i.ytimg.com/vi/4zeUOUo09Hs/maxresdefault.jpg)




