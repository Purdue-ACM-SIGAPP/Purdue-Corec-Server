# Purdue-Corec-Server

### Idea dump from Oct 11 meeting:

* Endpoints:
  * /floors
    * get all headcount data for each location on each floor
  * /stats/{zone_id}/{location_id}
    * zone_id: floor
    * location_id: location id
    * combines weekly and monthly data

* Potential Libraries:
  * Python 3.7.0
  * Flask
  * Redis-Py
