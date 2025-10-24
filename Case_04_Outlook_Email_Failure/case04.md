
#  Case 04: Outlook Not Sending Emails

## Issue Description
User reports that emails stay in Outbox and do not send.

## Root Cause
No internet connection while sending emails.

## Troubleshooting Steps
1. Disconnected Wi-Fi to simulate outage.  
2. Sent a test email:
3. Email stuck in Outbox, “Cannot connect to server.”  
4. Reconnected Wi-Fi and clicked **Send/Receive, Send All**.  
5. Email sent successfully.

 **Before:**  
![Outlook send error](https://github.com/Binali2142/Windows-Troubleshooting-Lab/blob/main/Case_04_Outlook_Email_Failure/01_Outlook_error.png)

 **After:**  
![Mail sent successfully](https://github.com/Binali2142/Windows-Troubleshooting-Lab/blob/main/Case_04_Outlook_Email_Failure/02_mail_sent.png)

##  Resolution
Restoring internet connection allowed Outlook to send queued mail.

##  Lessons Learned
Network connectivity directly affects Outlook’s ability to send/receive mail.
