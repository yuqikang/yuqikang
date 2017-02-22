##Use Case 1
###Title: <br>
  Create New Policies or Update Policies <br>
###Primary Actor: <br> 
  Manager<br>
###Goal in context: <br>
  Manager creates new policies or updates policies upon the policy retrieving from policy database.<br>
###Stakeholders: <br>
  Manager: To be able to retrieve policy for vulnerabilities and licenses from database and create or update the policy.<br>
###Preconditions<br>
  o	Manager sends the proper query. <br>
  o	Relevant policies for vulnerabilities and licenses are in the database<br>
###Main Success Scenario: <br>
  Manager successfully creates new policies or edits policies. <br>
###Failed End Condition: <br>
  Manager cannot create new policies or edit policies, or manager create or update inaccurate policies. <br>
###Trigger: <br>
  Manager requests to create new policies or edit policies for licenses and vulnerabilities.<br>
##Use case 2
###Title: <br>
  Determine the License and Vulnerability Information<br>
###Primary Actor:<br> 
  Manager<br>
###Goal in context: <br>
  The manager of company is able to determine the licenses and vulnerabilities information from software package.<br>
###Stakeholders: <br>
  o	Manager: To receive clear and relevant software license and vulnerability information<br>
  o	Developer: To provide the relevant file/software package information<br>
###Precondition: <br>
  o	Relevant file/license and vulnerability information is in the database. <br>
  o	Proper software information has been provided.<br>
  o	Proper query has been asked.<br>
###Main Success Scenario: <br>
  Manager receives accurate license and vulnerability information for the requested software packages.<br>
###Failed End Conditions: <br>
  Manager receives inaccurate or invalid license and vulnerability information for the requested software packages <br>
###Trigger:<br> 
  Manager wants to determine the license and vulnerability information of software. <br>
##Use Case 3
###Title:<br> 
  Upload file for checking License and vulnerability<br>
###Primary Actor: <br>
  Developer<br>
###Goal in context: <br>
  To be able to upload software package and scan the package to get accurate vulnerability and license results.<br>
###Stakeholders: <br>
  o	Developer: To provide software package and receive the license and vulnerability results<br>
  o	Manager: To oversee the process of checking the software package.<br>
###Precondition:<br>
  o	Developer upload the correct software package.<br>
  o	OSS Management accept the software package.<br>
  o	Fossology scan the software package and give the license results<br>
  o	The software package name is checked in the NIST Vulnerability database and provide vulnerability results.<br>
###Main Success Scenario: <br>
  Developer uploads the software package successfully and receive the accurate results of licenses and vulnerabilities.<br>
###Failed End Conditions: <br>
  Developer cannot upload the software package or cannot get the accurate licenses and vulnerabilities results.<br>
###Trigger: <br>
  The software package need to be checked and developer uploads the proper software package.<br>
