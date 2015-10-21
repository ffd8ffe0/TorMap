# TorMap


TorMap is a project that will map the geographic locations of Tor relays. 
----

## Required Data
* IP Address
* Nickname
* Lat Coord
* Long Coord
* ASN Number
* Country Code
* City
* Fingerprint
	
## MySQL Table

	| Id | Fingerprint | Nickname | Ip Address | ASN | Lat | Long | CC | City |

## TODO
* Implement code required to gather the relay data
  * Implementation [%75]
  * Testing[%0]

* Implement code required to gather the geographic data
 * Implementation [%75]
 * Testing[%0]

* Implement code required to insert the gather data into the database [%0]
 * Implementation [%0]
 * Testing[%0]

* Build web interface that will visualize the data [%0]
 * Implementation [%0]
 * Testing[%0]
