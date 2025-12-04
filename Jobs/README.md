## Google Chronicle Alerts Creator Job
This job will sync new SOAR alerts with Chronicle SIEM.
Note: This job is only supported from Chronicle SOAR version 6.2.30 and higher.


**Run Interval In Seconds:** 3600

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Environment|String|True|Default Environment|
|API Root|String|True|ttps://test-backstory.sandbox.googleapis.com|
|Verify SSL|Boolean|False|true|
|User's Service Account|Password|False|*****|
|Workload Identity Email|Password|False|*****|

## Simple Job Example
This is an example of a simple job. It has 2 functions: if a case has a tag "Closed", it will close the case from the job, if a case has a tag "Currency", it will add a comment to the case.


**Run Interval In Seconds:** 3600

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|API Root|String|True|https://api.vatcomply.com|
|Verify SSL|Boolean|False|true|
|Password Field|Password|False|*****|

## Sync Splunk ES Comments
This job will synchronize comments in Splunk ES events and Siemplify cases.


**Run Interval In Seconds:** 3600

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Server Address|String|True|https://lab:8089|
|Username|String|False|admin|
|CA Certificate File|String|False||
|Verify SSL|Boolean|False|true|
|Password|Password|False|*****|
|API Token|Password|False|*****|

## Sync Table Record Comments
This job will synchronize comments in ServiceNow table records and Siemplify cases.


**Run Interval In Seconds:** 18000

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Api Root|String|True|https://googlellcdemo3.service-now.com/api/now/v1/|
|Username|String|True|admin|
|Verify SSL|Boolean|False|false|
|Client ID|String|False||
|Use Oauth Authentication|Boolean|False|false|
|Table Name|String|True|incident|
|Password|Password|True|*****|
|Client Secret|Password|False|*****|
|Refresh Token|Password|False|*****|


adding a readme add on