Orchid Laundry Contingency Plan
==========================
![sss](https://github.com/darren-synergix/OL/blob/master/network.png)


## Scenario 1 - Network Down
Orchid Laundry is currently on single ISP plan, Singtel eLite 30Mbps.
According to Vincent, "The uptime is very good. No outage that I am aware off".

### Problem
Synergix E1 cannot be accessed
Jensen cannot retrieve shared files, no transfer of data between Synergix and Jensen.

### Possible Cause
Natural disaster, ISP maintenance, DDoS attack

### Potential Solution
1. Multiple ISP plan for redundancy
2. 4G mobile broadband as backup

---

## Scenario 2 - Web Hosting Service Down
Orchid Laundry is currently on a dedicated server hosted by Webvisions.

### Problem
Synergix E1 cannot be accessed
Jensen cannot retrieve shared files, no transfer of data between Synergix and Jensen.

### Possible Cause
Maintenance work, vendor network breakdown 

### Potential Solution
???

---

## Scenario 3 - Synergix E1 Problem
The only time when the entire Synergix E1 cannot be accessed is when web hosting service is down.

Otherwise, the only foreseeable potential issue is that some of the module cannot be accessed due to bug, deployment issue, maintenance setup problem (role master, permission, module config, etc.).

### Problem
User cannot access or has problem with certain module, such as Sales Order and RFID Gantry. This will stop user from doing order entry, scan RFID linen, etc.

### Possible Cause
1. Bug
2. Deployment issue
3. User did not setup correctly
4. Config is not turned on/off

### Potential Solution
???

### Note
Orchid requested 365 days technical support 
Orchid requested after shift (11pm) deployment


---

## Scenario 4 - Jensen Down
### Problem
Jensen system not working, unable to transport garment and sort, or unable to retrieve file from Synergix.

### Potential Solution
If Jensen server or hardware is down, there is no other option until Jensen resolves it.


---

## Scenario 5 - Factory Hardware Down
If any part of the network link owned by OL is down, there is no other option until OL replaces it with a backup or a new device. The link includes but not limited to:

* RFID Gantry, includes Antenna and Reader
* RFID Handheld Reader
* Barcode Scanner
* PC
* Network Router
* Any Physical Cable

## Info
### ISP Plan
Singtel eLite 30Mbps

### Network Diagram
Internet -> Fortigate 100D WAN -> TPLink Gigabit Switch

### Jensen

### Web Hosting Service
Dedicated Server
Intel Xeon E5-2620 v3 (6 core)
48GB RAM
2x 960GB SSD RAID1
