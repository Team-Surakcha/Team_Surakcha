# Team_Surakcha
Goal : To perform Penetration Testing to find different possible vulnerabilities in various web applications/apps/web services to prepare a finished report for the
same as per the observation, and eventually, we will be performing mapping and layer creation using the navigator tool.

# The below mentioned steps should be followed to step up an environment for using different penetration testing tools:

1. The VMware workstation for the creation of virtual environment should be downloaded and installed from the link:
https://docs.vmware.com/en/VMware-Workstation-Pro/16.2.4/rn/vmware-workstation-1624-pro-release-notes/index.html

2. The Kali linux as the OS should be configured inside the VMware workstation with the help of kali linux iso file which can be downloaded from the link:
https://www.kali.org/get-kali/#kali-virtual-machines

Or;

A prebuilt virtual machine with installed kali linux inside VMware workstation as OS can be downloaded from the link:

https://www.kali.org/get-kali/#kali-virtual-machines

3. The below mentioned commands for respective tool should be executed in a terminal to gather an information related to a particular website.

(i) Uniscan: 

sudo su ------> to enter a root directory

uniscan-gui -------> to open the front end of uniscan scanner where we can mention the url of the respective web site

Uniscan also saves each scan as an HTML file under /usr/share/uniscan/report/ if scan results are needed at a later time.

(ii) Nikto

sudo su ------> to enter a root directory

nikto -h 139.59.5.86 -p 80----->139.59.5.86 is an ip address of the respective web site which is to be scanned

(iii) Burp Suite: 
With the help of different sub tools present in the GUI, the vulnerabilities should be gathered.


(iv) Nmap:

nmap ip ------> ip address of a web site which is to be scanned

Note: All the findings via different tools have been mentioned in detail in the attached project report along with the screenshots.

4. Eventually, all those gathered information should be analysed together to prepared a finished report.

Note: The prepared finished report has been illustrated inside the attached project report.

5. From the prepared, finished report the possible techniques under a tactic for an attack should be traced out.

6. The mapping should be done using ATT&CK navigator tool.

Note: For the proposed solution , the json and excel file of done mapping have been attached for the reference.

Note: The below mentioned steps should be followed to run an attached json file:

(i) Open the url: https://mitre-attack.github.io/attack-navigator/

(ii) Click on open existing layer option

(ii) select the attached json file and open it.

(7) The defensive approaches should be recommended.


Note: For the proposed solution, all the above listed steps and approaches are illustrated in detail in the attached project report. Also, using the mentioned tools,
different attacks were performed which are illustrated in an attached demo video. In an attached demo video, the usage of different mentioned tools are also being
demonstrated in detail.

