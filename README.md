# Asynchronous Python EnOcean #

A Python library for reading and controlling synchronously [EnOcean](http://www.enocean.com/) devices using USB serial enOcean keys.

The goal of this repository is to provide a library that could be used by Home Assistant enOcean integration.

> [!WARNING]
> Work In Progress

Feel free tu submit merge request to help me in this work.

# Intended Architecture #

Enocean library (forked from kipe/enocean) is handling communication with the gateway and EEP thanks to EEP.xml definitions.
An overlay is converting all EEP data to Home Assistant data model thanks to mapping.yaml. This code is based on mak-gitdev/HA_enoceanMQTT.

# Intended API #

TBD
