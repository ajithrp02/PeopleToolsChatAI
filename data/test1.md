---
title: peoplesoft data 1
slug: /peoplesoft
---

#  Peopletools Upgrade
a) A new environment D1 will be built for comparison and retrofitting purposes with 8.60 tools upgraded. b) Two new environments will be built - Dev and UAT - taking copies of T58 and Q58 with 8.59 tools. These will serve as the production path during the course of tools upgrade project. c) New Stat flow will be built for Dev - UATto Prod for migrations. d)Dev- D58, and UAT- Q58, will be in synch all the time. e)Comapre the objects and apply retrofits' to the affected objects in the upgraded D1 environment

f)Once the retorfits are completed, test the functionality of the affected objects in D1 environment to make sure it is working as expected.

g)T58 will be upgraded by Admin team. Once T58 is upgraded manually migrate the retrofitted objects using database migration.

h)Once the objects are migrated to T58, perform system testing for the affected objects to make sure all the changes have been migrated properly.

i)Once system testing is signed off,prepare CSR’s to migrate it to Q58 environment.

j)Plan and place Autosys jobs on ice/on hold before the environment is upgraded.

h)Once the Autosys jobs are placed on hold/on/ice tech arch team will upgrade Q58 environment to the newer tools version and migrate the changes from T58 to Q58.

i)Developers will check if all the changes has been migrated correctly. Business will start UAT testing on all functionality.

J)Once UAT completes,tag the CSR’s to Prod bundle that is scheduled to execute on a particular day.

k)Autosys jobs in P58 will be places on hold/on ice. Tech Arch team will upgrade P58 environment and the retrofits will be migrated toP58.

l) Developers will check if all the changes has been migrated correctly. Business will start prd checkout.If everything is fine,Autosys jobs will be placed off ice/off hold

m)Row count analysis will be done in every environment. Analyze row counts of the tables before and after upgrade to make sure the functional tables are not affected.

n) SYSAUDIT, DDDAUDIT, SWAPAUDIT analysis will be done across all environments to correct the discrepancies shown in the Audit documents.If the objects are delivered,we should not make any changes unless there are any customizations.
