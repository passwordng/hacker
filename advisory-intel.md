---
layout: default
---

## Ransomware In Nigeria – The Lessons We Did Not Learn /Part I

‘No official information yet, but we have seen some leakage of alleged compromise of a certain Nigeria organization as released by a ransomware threat group in the dark web” – This was a statement from a member of the Whitehat.NG telegram platform. This was in the afternoon of April 16th, 2023. 

And further instruction was shared on how those with internet-facing assets should ensure visibility across them, and most importantly validate any form of existing relationship with the current alleged victim of this new incident, to prevent the spread and possible exploitation of third-party relationships as seen in previous ransomware-related incidents. Tips and recommendations that can help were further shared in the course of this writing.
As a group of professionals, those with privileged access started digging for more information as per this release dated April 15th, 2023 from the dark web and other data to ensure the statement issued by the threat group is not just some bluff, as shown below.
![Fig1](https://raw.githubusercontent.com/passwordng/hacker/master/assets/images/fig1.jpg)
Fig 1. Screenshot from ALPHV leak site displaying some part of the stolen data, mostly PIIs.

A little background from what we know before this time….
A week earlier, we got some intel and notification of intrusion on certain facilities which has to do with the usage of Cobalt Strike in its post-exploitation as documented by the CyberPlural’s Team. This introduced a couple of questions as to whether the country is being targeted towards this time as a similar incident had been previously captured by the team in 2022, just a few days after the Bet9ja incident became news. 

Basically in 2022, the following happened;
-	Bet9ja Ransomware Incident 
-	ALPHV / Blackcat was stated to be responsible
-	Cobalt Strike Post-Exploitation Tool observed around certain facilities in Nigeria. 
- Bet9ja was updating stakeholders on their progress throughout the incident, and providing assurance to customers on their progress to restoring.

Cobalt strike is a legitimate and powerful post-exploitation tool known for its abuse by cybercriminals targeting organizations’ networks and always part of the tools used in the MOs for this particular ransomware group that is getting their second public hit in Nigeria (ALPHV / Blackcat). And it will interest you to know that FBI documentation carrying the MOs of this ransomware group captured it as shown below.

![Fig2](https://raw.githubusercontent.com/passwordng/hacker/master/assets/images/fig2.jpg)
Fig 2.  Technical Detail of the BlackCat/ALPHV ransomware as documented by the FBI.

This background reinforces our belief that the publication date of this compromise on the leakage site of ALPHV is not the same as the real incident date, and is very far from the initial date of entry. The ransomware deployment part of the incident might have happened earlier, maybe a week earlier putting it at the first week of April at best. Considering the phases involved in a successful and sophisticated compromise as this which cut across the adversary gaining initial access to the network, the conduct of internal recon of the alleged victim’s networks, finding important data and laterally moving across different connected business segments networks down to exfiltration of the data, confidential business data as we come to find out wouldn’t be just an overnight work. The start of this journey to the end might have taken months before the ransomware deployment.
Back to those working on getting more concrete information regarding what was published on the leak site; we were able to confirm certain sensitive information such as strategy documents, the company’s finances, customers PII and others as shown below. 

![Fig3](https://raw.githubusercontent.com/passwordng/hacker/master/assets/images/fig3.jpg)
Fig 3. Company’s Financials

![Fig4](https://raw.githubusercontent.com/passwordng/hacker/master/assets/images/fig4.jpg)
Fig 4. Passports as used by customers as a means of identity validations for enabling services offered.

![Fig5](https://raw.githubusercontent.com/passwordng/hacker/master/assets/images/fig5.png)
Fig 5. Personally Identifiable Information of Customers.

This data as contained in Fig 3, 4, and 5 above indicated the ALPHV group is not bluffing about what they are currently holding on the alleged victim, thousands of customer’s personal data and business-related data. Information on the leak site indicated that what was currently published is just a part of the stolen data, and if management (of the alleged victim’s company) did not contact soon will warrant the release of others.

Using other available open sources to confirm what we have now, we leverage FalconFeedsio, a known Twitter page that shares intel on activities of malicious threat groups from the dark web, also confirmed we have similar information regarding the leak site on the 16th.

![Fig6](https://raw.githubusercontent.com/passwordng/hacker/master/assets/images/fig6.png)
Fig 6.

On one hand, we are also expecting an official statement on this incident from the alleged victim to be sure that this is real. The statement is also expected to guide customers in ensuring there are protected from secondary attacks such as phishing & social engineering, as well as stakeholders getting to know of the progress the organization is making in restoring and becoming operational. Such a statement has also been seen in the past to have helped protect other businesses and organizations operating in the same space and industry as the alleged victim of such an ugly incident.

After four days of waiting, no official statement from any quarter and we already concluding the ALPHV group might as well start releasing the rest of the data or maybe some transactions might have exchanged hands which might make the alleged victim publication to be removed from their site; any of these two is possible at this time.  Then we come across an interesting story from Business Day Newspaper on April 19th, 2023 as captured below.


## Advisory and Threat Intelligence

_yay_

[back](./)
