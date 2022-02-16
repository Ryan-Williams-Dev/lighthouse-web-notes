# Lecture Notes - Week 2 - Day 3
 
 ---

## Network
* 

## TCP

* TCP requires a connection, 
  * Three way handshake D1: hi D2: yes hi D3: ok good lets go
  * cares if things arrive properly
  * can reorder the packets or requests the ones it misses
  * no lost data

* UDP
  * connectionless protocol
  * sending it regardless of connection
  * Low latency, but can drop info, like a stream

### Packets 
* chop up data into little peices

## IP
* IPv4 and IPv6
  *  only your router has the IP address
    * IPv6 for device
* Ports
  * precise
  * we have 65,535 ports to choose from per IP

## node net functions
* [options in docs mean options]
* when you see listener think callback
* leading underscore means protected e.g. `_handle` means leave me alone

listen for events, see event names from documentation

sockmon dtaa 
set encode utf 8

## HTTP
* HTTP requites requets. nothing happens unbidden
* sits on top of TCP
* GET & POST
* path tell it what we want it to do.
* one responser per request
* response can contain data - but it MUST contain a status code
  * 2xx - looks good
  * 4xx - something is wrong with your request example 404
  * 3xx normally redirects
  * 1xx routing codes
  * 5xx something has gone teribbly wrong, with the server.