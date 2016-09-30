# mdns-lookup
Python mDNS lookup

This is based on the Stackoverflow answer http://stackoverflow.com/a/35853322/185510.

## Install

Latest stable release:

    pip install https://github.com/AndreMiras/mdns-lookup/archive/master.zip

Development branch:

    pip install https://github.com/AndreMiras/mdns-lookup/archive/develop.zip

## Usage
    mdnslookup.py raspberrypi.local hprinter.local
    raspberrypi.local 192.168.1.24
    hprinter.local 192.168.1.42

## Tests

Using Python unit testing framework:

    python -m unittest discover

Using Tox:

    tox
