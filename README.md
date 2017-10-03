# com.castsoftware.uc.cwe

# 1.1	Description
The Extension should be used to avoid the existence of hard-coded credentials typically create a significant hole that allows an attacker to bypass the authentication that has been configured by the software administrator. 
The commitment came from internal customer Italy Auditor. The customer BU is manly team involved to analyze all customer applications to verify the violations about hard-coded credentials. 
Then the process can be extended to Quality Department also.

IMPORTANT!!! Please keep in mind that this Extension is implemented specifically for this  customer. An implementation in others environments requires customization about languages involved by Extension. 
The Extension implements customer metrics using CAST Universal Analyzer.
# 1.2	Version
 The table below indicates the current version of the Extension and history of versions.
 
![]( https://github.com/CAST-Extend/com.castsoftware.uc.cwe/blob/master/Image1.PNG?raw=true)

# 1.3	Use cases
The Extension is covering the following use cases: 
•	Check the hard coded credentials coded manually USERNAME and PASSWORD

![]( https://github.com/CAST-Extend/com.castsoftware.uc.cwe/blob/master/Image2.PNG?raw=true)

# 1.4	CAST AIP compatibility
The following table gives the list of CAST AIP configurations where the Extension has been implemented: 

![]( https://github.com/CAST-Extend/com.castsoftware.uc.cwe/blob/master/Image3.PNG?raw=true)


# 1.5	Supported DBMS servers
This extension is compatible with the following DBMS servers:

![]( https://github.com/CAST-Extend/com.castsoftware.uc.cwe/blob/master/Image4.PNG?raw=true)

# 1.6	Outputs example
## 1.6.1	The Dashboard shows the violation of new custom rule

![]( https://github.com/CAST-Extend/com.castsoftware.uc.cwe/blob/master/Image5.PNG?raw=true)

## 1.6.2	Hardcoded_ReferenceFinder In the Enlighten 
In this case, Enlighten  shows the object with violation using Reference Patterns Hardcoded_ReferenceFinder  for user USRW123 showing the object in Object Browser View.

![]( https://github.com/CAST-Extend/com.castsoftware.uc.cwe/blob/master/Image6.PNG?raw=true)

## 1.6.3	Hardcoded_ReferenceFinder In the Enlighten 

In this case, Enlighten  shows the object with false violation using Reference Patterns FalsePositiveHardcodedUserId for user USRW123 showing the obejcts in Object Browser View.
This RF has been coded to avoid FalsePositive violation for USER into source code.

![]( https://github.com/CAST-Extend/com.castsoftware.uc.cwe/blob/master/Image7.PNG?raw=true)
