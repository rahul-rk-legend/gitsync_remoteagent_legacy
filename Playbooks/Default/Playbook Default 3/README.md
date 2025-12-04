# Playbook Default 3




**Enabled:** True

**Version:** 1

**Type:** Playbook

**Priority:** 2

**Playbook Simulator:** False


### Playbook Trigger
**Trigger Type:** All

**Conditions Operator:** And

##### Conditions
|Key|Operator|Value|
|---|--------|-----|
||Equals||


### Involved Steps (Unordered)
|Step Name|Description|Integration|Original Action|
|---------|-----------|-----------|---------------|
|Siemplify_Get Case Details_1|This action will get all the data from a case and return a JSON result.  The result includes comments, entity information, insights, playbooks that ran, alert information and events.|Siemplify|Get Case Details|
|Siemplify_Get Case Alerts_1|Use the "Get Case Alerts" action to retrieve alerts related to the case.|Siemplify|Get Case Alerts|
|Siemplify_Get Similar Cases_1|Search for similar cases and return their Ids|Siemplify|Get Similar Cases|

adding a readme add on