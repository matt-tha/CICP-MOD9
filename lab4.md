####Instructions

Note: You must complete exercise 3 before attempting exercise 4. 

1. Launch RPT number 4, WebApps Browser Attack and Penetration. 
2. From the Email Target Selection screen click From: to specify the attacking address. Right click in the empty address list and select New Email. Enter helpdesk@doubleshield.org as the address and Helpdesk as the name. Click OK and select the new address. Click OK. 
3. Click To: to specify the recipient address. Right click in the address list and select New Email. Enter dmills@doubleshield.org as the address and Debra Mills as the name. Click OK and select the new address. Click OK. 
4. Click Next. Use the ellipsis to select the XSS Agent from scenario XSS Test 1. Proceed with the default email body template and subject line. Click next. 
5. Specify “ mail.doubleshield.org “ as the SMTP server and click Finish to execute the RPT. 

**Switch to the End User PC virtual machine.**

6. Login with username “ Debra Mills “ and password “ password123 “
7. Launch Outlook Express from the Desktop. 
8. Outlook Express should automatically download any available email, if it has not click the Send and Receive button from the toolbar. If you did not receive the email message return to Impact Pro and verify your RPT settings. 
9. If you have received the email message single click to open it in the reading pane.
10. Click the hyperlink at the bottom of the email message. Internet Explorer will launch however no page will be displayed, this is normal. 

**Switch to the Impact Pro client virtual machine.**

11. Expand the XSS Agent to reveal the exploited browser.  Quick Information will show the browsers details.  

You have successfully exploited a browser using Cross Site Scripting. 

This concludes lab exercise 3, continue to exercise 4.
