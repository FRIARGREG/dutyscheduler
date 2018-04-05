dutyscheduler
=============
##scheduler algorithm for secondary duty
------------------------------------------
### 8:02 AM 05/04/2018

issue is as follows:
*10 members in shop
*each should take the secondary duty on for 1 week in a cycle (ie once every 10 weeks)</LI>

constraints include:
*overlapping leave periods
*members on extended deployments
*members on training
*conflicting duties (too many secondary duties that may be double booked)

this scheduler must:
*rotate members through annual schedule as evenly as possible
*take into account time away from shop (extended deployments/training count as duty served)
*accept manual changes and still maintain equal duty load on all members.

