Motorola push to Talk
<br />
<img width="773" height="153" alt="image" src="https://github.com/user-attachments/assets/6d485619-9a35-4292-8b23-387f227dc3c1" />
<br />
<br />
Product web page:<br />
https://www.motorolasolutions.com/en_us/products/command-center-software/broadband-ptt-and-lmr-interoperability/mcptt-deployment.html
<br />

Product name:<br />
Kodiak Broadband Push to Talk (PTT) - MCPTT
<br />

This article will be updated with correct CVE.<br />
Right now its imposible to get any CVE numbers.<br />

For details see attached file.<br />
https://github.com/ProxyStaffy/Motorola-push-to-Talk/blob/main/Motorola_push_to_Talk.pdf

#################
CVE
#################

------------------------------------------
CV2025-xx1 - NoSQL injection
AV:A/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H (8.0)

NoSQL injection vulnerabilities in Motorola Pust to Talk 9.1.1 and earlier, could allow an authenticated attacker to conduct a NoSQL injection attack due to insufficient input validation.
This was fixed in 9.1.1.

------------------------------------------
CV2025-xx2 - Denial of Service in sending message
AV:N/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H  (6,5)
DOS vulnerabilities in Motorola Pust to Talk 9.1.1 and earlier, allow an authenticated attacker to conduct a DOS attack with a malicious text message due to insufficient input validation in send text message API.
This was fixed in 11.0.

------------------------------------------
Couchbase
CV2025-xx3 - Denial of Service in sending message
AV:N/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H  (6,5)
DOS vulnerabilities in Sync Gateway 2.1.2 which are compatible with Couchbase Server 6.6.X and earlier, allowing an authenticated attacker to conduct a DOS attack on the client by sending special crafted request to the database.
This was fixed in Couchbase server 6.6.3.


------------------------------------------
CV2025-xx4 - Impersonating users in sending message
AV:N/AC:L/PR:L/UI:N/S:U/C:N/I:H/A:N (6,5)
Business logic vulnerabilities in Motorola Pust to Talk 9.1.1 and earlier, allowing a signed in user to impersonate user in one to one and talk group communication.
This was fixed in 11.2.

------------------------------------------
CV2025-xx5 - Placing message in the message history timeline
AV:N/AC:L/PR:L/UI:N/S:U/C:N/I:L/A:N  (4,3)

By manipulating the msgCreateTime parameter (unixtime) in sending message API it’s possible to implant a specific message in message history timeline/flow.
This was fixed in 11.0.

------------------------------------------
CV2025-xx6 - IDOR in changing name
AV:N/AC:L/PR:L/UI:N/S:U/C:N/I:H/A:N  (6,5)

IDOR vulnerabilities in Motorola Pust to Talk 9.1.1 and earlier, could allow an authenticated attacker to conduct a name change attack of all users due to insufficient input validation.
This was fixed in 11.0.

------------------------------------------
CV2025-xx7 - Manipulating logs
AV:N/AC:L/PR:L/UI:N/S:U/C:N/I:H/A:N  (6,5)

Business logic vulnerabilities in Motorola Pust to Talk 9.1.1 and earlier, could allow an authenticated Dispatcher attacker to conduct log manipulation.
This was partly fixed in 11.2.

------------------------------------------
CV2025-xx8 - Changing password in dispatcher UI
AV:N/AC:H/PR:L/UI:N/S:U/C:N/I:L/A:N (3,1)

Input validation fault doesn’t validate the old password when changing password in the dispatcher UI.
This was fixed in 10.0.2.

------------------------------------------


#Motorola Push to Talk
<br />
#Motorola PTT
<br />
#Motorola Push to Trust
<br />
#Kodiak Broadband Push to Talk (PTT) - MCPTT
