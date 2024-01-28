# Nessus-Basic-Scan

Nessus is a vulnerability scanning platform, used by people in multiple cyber security fields, including security analysts. The Nessus tool is used mostly to scan vulnerabilities. It is important to note that Nessus Professional is only accessible for 1 installation, for 7 days.
Nessus prevents network attacks by identifying vulnerabilities and other issues that may be used by hackers to penetrate a network or infrastructure.

In this task, I will configure Nessus so that I can scan the network.

After completing this exercise, you will be able to demonstrate my capabilities to:

Perform a Basic Scan
Save Reports

## Equipment, 2 virtual machines:  Windows Server 2019 - Domain Server and Windows 10 - Domain Member Workstation

Once installed, Nessus can be configured to suit your needs. The tool can be configured to suit a wide array of needs, and Nessus provides templates for a user to use as a baseline. These three are known as the discovery, compliance and vulnerability templates and can be further configured if needed.

In Windows 10 Open firefox and type: https://localhost:8834
On the Warning: Potential Security Risk Ahead page, click Advanced.
![image](https://github.com/kalejcamto/Nessus-Basic-Scan/assets/101201140/d644f395-d222-45f1-9867-00e0e98be49f)

Then, scroll down and click Accept the Risk and Continue.

![image](https://github.com/kalejcamto/Nessus-Basic-Scan/assets/101201140/52f414d5-2680-4f07-8d8d-830cc02d9bd8)


![image](https://github.com/kalejcamto/Nessus-Basic-Scan/assets/101201140/52fa546d-092e-4394-a769-57c1c6418804)

![image](https://github.com/kalejcamto/Nessus-Basic-Scan/assets/101201140/d0150a28-fff8-4866-9362-a19cb74a2bbf)

![image](https://github.com/kalejcamto/Nessus-Basic-Scan/assets/101201140/0ab901d7-622d-4ebb-90fb-28bb21cf6ad7) 

By default, the first page that is displayed is the My Scans page. Notice that there is a scan that is already defined for you. 
Actions: Select the scan named My Host Discovery Scan, click the More drop-down, and then select Launch.

![image](https://github.com/kalejcamto/Nessus-Basic-Scan/assets/101201140/e5333b30-76f3-40db-b2c9-cff083a5a91f)


![image](https://github.com/kalejcamto/Nessus-Basic-Scan/assets/101201140/634c8e1a-db7a-45d9-b984-7832b6c751c0)

The scan starts. The scanning process may take a while to complete. I had to close and re open on an incognito mode browser. 
![image](https://github.com/kalejcamto/Nessus-Basic-Scan/assets/101201140/a0beffe1-0fda-4364-bfa8-c96ebea189e7)

Finally launching worked:  After the scan completes running, notice that there is a checkmark before the time stamp. I Clicked on My Host Discovery Scan.
![image](https://github.com/kalejcamto/Nessus-Basic-Scan/assets/101201140/cd2ed5c3-117b-4493-9e30-a1c189b56b87)

![image](https://github.com/kalejcamto/Nessus-Basic-Scan/assets/101201140/4cbedacf-67f8-4f10-86da-e3d8430517c1)

![image](https://github.com/kalejcamto/Nessus-Basic-Scan/assets/101201140/55ad4854-5cdd-4cda-b1b9-bd614fafc0e8)

I clicked the Vulnerabilities tab. I Noticed that two vulnerabilities are marked as INFO. I Clicked Ping, the remote host.

![image](https://github.com/kalejcamto/Nessus-Basic-Scan/assets/101201140/baed814b-44da-44e8-b7f6-fc8d20546045)

It displays the ping results to the hosts that have been scanned for vulnerabilities.

Click the History tab, which displays the history of scans that have been completed.

![image](https://github.com/kalejcamto/Nessus-Basic-Scan/assets/101201140/00f8d0d8-cab6-4b20-94ed-fe0bcebdaede)

From My Scans page, click the New Scan button. This button is located in the upper right corner, and therefore, you will have to scroll to the right.

![image](https://github.com/kalejcamto/Nessus-Basic-Scan/assets/101201140/efba100e-5e70-48f4-b4b3-0da8807656ae)

Advanced Scan template.
![image](https://github.com/kalejcamto/Nessus-Basic-Scan/assets/101201140/b33cb85d-0477-49b0-b32b-a646f97f97ae)

![image](https://github.com/kalejcamto/Nessus-Basic-Scan/assets/101201140/03fb23de-8fc0-40fa-846a-05ce7e845f42)

![image](https://github.com/kalejcamto/Nessus-Basic-Scan/assets/101201140/40238309-1968-45ab-a1cb-8f691a45d85a)

On the Credentials tab, ensure Host is selected in the CATEGORIES drop-down and then click Windows.
![image](https://github.com/kalejcamto/Nessus-Basic-Scan/assets/101201140/91b1f879-791d-48d6-91b8-4b706d428840)

![image](https://github.com/kalejcamto/Nessus-Basic-Scan/assets/101201140/2973a693-0792-4cad-b6b6-0f0ac9bc2937)

Back on the My Scans page, select PLAB and then click More and select Launch.

![image](https://github.com/kalejcamto/Nessus-Basic-Scan/assets/101201140/9e45547f-b89f-4373-ab71-9c1218b0e341)


Successfully ran scan: This is an advanced scan, and you are scanning a range of IP addresses. Therefore, this scan is likely to take a while to complete.
![image](https://github.com/kalejcamto/Nessus-Basic-Scan/assets/101201140/ee609703-d22b-4ea6-8aec-1fc8941fd0a5)


 Click on the PLAB scan.

 ![image](https://github.com/kalejcamto/Nessus-Basic-Scan/assets/101201140/f3606b6a-b8d9-4b1b-bac1-9eff51b20d68)

The details related to IP Forwarding is displayed.
![image](https://github.com/kalejcamto/Nessus-Basic-Scan/assets/101201140/1b6d55cd-c9bb-4b19-83e1-f38d1eac8b89)


After a scan is created, its report is displayed by opening the scan. If a scan has not run, the results page will display the No history is available for this scan. message. Scan results display data based on the scan’s template and configured actions.
![image](https://github.com/kalejcamto/Nessus-Basic-Scan/assets/101201140/0c3a3dd9-1f91-49be-b46c-7d20400ca2f6)


## I learned to run basic scanning and I am pretty sure, it is going to be more complex scans at a corporation but at least I try with what I have available to test and get hands on practice. 





