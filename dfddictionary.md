##Entities:<br> 
  •	Developer. The person who creates the software packages. <br>
  •	Manager. The person who has power to manage the development of software package.<br>
##Processes:<br>
  •	OSS Management. The process than can scan and accept the software package.<br>
  •	FOSSOLOGY. The process that examine software package to determine licenses.<br>
  •	Get license and vulnerability information. The process that gets license and vulnerability information from license and vulnerability database. <br>
  •	Get policy. The process that get specific policy from policy database for licenses and vulnerabilities.<br>
  •	Set new policy or edit policy. The process that set new policy or edit policy.<br>
##Data Flow:<br>
  •	Software package: A file which is created by developer to make software.<br>
  •	License and vulnerability results. The results are from NIST Vulnerability database and Fossology which check the software package’s vulnerability and license.<br>
  •	Software package name. software package name is used to be scanned by NIST vulnerability Database to check vulnerability.<br>
  •	Vulnerability results. The results after the software package name is checked by NIST vulnerability database.<br>
  •	License results. The results after the software package is scanned by Fossology.<br>
  •	License and vulnerability requests. The request to retrieve license and vulnerability information from license and vulnerability database.<br>
  •	License and vulnerability information. A file contains license and vulnerability information sending to requester. <br>
  •	Get policy request. The request to get policy for license and vulnerability from policy database.<br>
  •	Policy results. A file contains policy which is asked by requester. <br>
  •	Update new policy request. The request sent by manager which request to update or edit policy. <br>
  •	Updated new policy. A file contains the new policy which has been updated or edited sending to policy database.<br>
##Data repositories<br>
  •	NIST Vulnerability Database. A repository of vulnerability management to check the if the package name is vulnerable. <br>
  •	License and Vulnerability Database. A repository that store the license and vulnerability results.<br>
  •	Policy for License and Vulnerability Database. A repository that store policies for licenses and vulnerabilities.<br>
