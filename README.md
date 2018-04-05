dutyscheduler
============= 
Scheduler algorithm for secondary duty


------------------------------------------
## 8:02 AM 05/04/2018

**issue is as follows:**
* 10 members in shop
* each should take the secondary duty on for 1 week in a cycle (ie once every 10 weeks)</LI>

**Constraints include:**
1. overlapping leave periods
2. members on extended deployments
3. members on training
4. conflicting duties (too many secondary duties that may be double booked)

**This scheduler must:**
1. rotate members through annual schedule as evenly as possible
2. take into account time away from shop (extended deployments/training count as duty served)
3. accept manual changes and still maintain equal duty load on all members.

