
Orchid Laundry Contingency Plan
==========================
![Network Diagram](https://raw.githubusercontent.com/darren-synergix/OL/master/network.png)

## Info
### ISP Plan
Singtel eLite 30Mbps

### Web Hosting Service
- Dedicated Server
- Intel Xeon E5-2620 v3 (6 core)
- 48GB RAM
- 2x 960GB SSD RAID1

---

## Scenario 1 - ISP Down
Orchid Laundry is currently on single ISP plan.

According to Vincent, "The uptime is very good. No outage that I am aware off".

### Problem
Synergix E1 cannot be accessed.

Jensen cannot retrieve shared files, no transfer of data between Synergix and Jensen.

### Possible Cause
Natural disaster, ISP maintenance, DDoS attack

### Potential Solution
1. Multiple ISP plan for redundancy
2. 4G mobile broadband as backup network

---

## Scenario 2 - Web Hosting Service Down
Orchid Laundry is currently on a dedicated server hosted by Webvisions.

### Problem
Synergix E1 cannot be accessed.

Jensen cannot retrieve shared files, no transfer of data between Synergix and Jensen.

### Possible Cause
Maintenance work, vendor network breakdown 

### Potential Solution
#### 1. Host in-house server
Pros
- Have total control over own server
- Running on LAN

Cons
- Costly
- Own setup
- Own 24/7 maintenance
- No support
- No up-time guarantee
- Require a team of IT personnel
- Reliability is no better than hosting service
- Retail shop, deployed staff, mobile operations cannot access system if server down


#### 2.  Host in-house Backup Server for Master Data Only + Local App
Instead of using web app, OL can request desktop app version of the same module such as RFID Tracking System. OL can also request a desktop app to manually key in order data for Jensen to process.

Daily backup of master data to OL own backup server. There is no need to store transaction data, since Jensen requires the latest one in real time, whatever that is stored is considered outdated to Jensen.

Pros
- Master data still can be retrieved, but it could be outdated 
- Jensen still can work

Cons
- All the cons of hosting in-house server
- Order coming in from retail shop needs to be key in manually again, so that Jensen can process



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
1. Contact Synergix Helpdesk from 9am to 6pm SGT, Mon-Fri, excluding holidays
2. Synergix After hour support package

### Note
1. Orchid requested 365 days technical support 
2. Orchid requested after shift (11pm) deployment

---

## Scenario 4 - Jensen Down
### Problem
Jensen is unable to transport garment and sort, or unable to retrieve file from Synergix due to Jensen system fault.

### Potential Solution
If Jensen server or hardware is down, there is no other option until Jensen resolves it.


---

## Scenario 5 - OL-Owned Hardware or Network Down 
### Problem
If any part of the hardware/network link owned by OL is down, Synergix software that requires that hardware/network cannot be accessed.

### Potential Solution
If any part of the network link owned by OL is down, there is no other option until OL replaces it with a backup or a new device, or fix the network. The link includes but not limited to:

* RFID Gantry, includes Antenna and Reader
* RFID Handheld Reader
* Barcode Scanner
* PC
* Network Router
* Any Physical Cable

Hardware and network stated here includes OL factory, retail outlet, franchise, and mobile operations. 

