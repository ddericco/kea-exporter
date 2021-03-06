# kea-exporter
Prometheus exporter for the ISC Kea DHCP Server, written in Python, forked from [kea-exporter](https://github.com/mweinelt/kea-exporter/)

## Features
* DHCP4 and DHCP6 metrics
* Querying via RESTful API (allows the exporter to be run remotely)

## Requirements
This exporter has ONLY been tested on Kea 1.4, though any version of Kea that implements the RESTful API should work (> 1.2).

## Installation
```
git clone git@github.com:ddericco/kea-exporter.git
cd kea-exporter
pip install -r requirements.txt
```
