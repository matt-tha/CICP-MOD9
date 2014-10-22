####Instructions

1. Switch to the Web view by clicking the web tab located in the top center of the screen. 
2. Launch RPT number 1, WebApps Information Gathering.
3. Provide a scenario name of your choosing and click Next. 
4. Select Crawl a known web application and click Next.
5. On the Crawling mode selection screen select Interactive web crawling and click Next. 
6. Processed through the wizard using default settings. 
7. Launch Internet Explorer from the Windows Start Menu.
8. Open the Internet Options screen by clicking the gear in the top right corner and selecting Internet Options. 
9. From the Connections Tab click LAN Settings
10. For Impact Pro to properly log our web browsing we must configure it as the proxy server. Under the Proxy Server heading check " Use a proxy server for your LAN" and specify 127.0.0.1 port 8080 as the proxy. Click OK
11. Click OK to close Internet Options. Impact Pro should now be able to log every site we visit. 
12. To access the suite of OWASP demonstration sites type "  secure.doubleshield.org  " into the address bar and press Enter. It may take a couple of minutes to load the site. 
13. From the Training Applications group select " Damn Vulnerable Web Application " (DVWA).
14. Log into DVWA using username " admin " and password " admin ".
15. DVWA contains several useful tools for practicing web exploitation. For this exercise we're going to use " SQL Injection " found in the left menu. 
16. Once the SQL Injection page loads enter any string into the User ID field and click submit. Make note of the URL and switch back to Impact Pro. 
17. If you have selected your scenario you will now see a list of the URLs you've crawled. If you have not selected your scenario, select it now. 
18. Before proceeding with an attack we need to stop any running modules. Within Executed Modules, right click on WebApps Information Gathering and select Stop. 
19. Within Impact Pro locate the SQL Injection URL that contains the User ID data you’ve submitted. Drag RPT number 2, WebApps Attack and Penetration onto this URL. This tells Impact Pro to select this URL as the target. 
20. Proceed through the wizard. Once you reach the Risk Types screen de-select all options leaving only A1 - Injection and its two sub options. 
21. On the next screen de-select these options as well and click Next. 
22. De-select the remaining risks types and click next. We do this because we're only interested in testing Injection based exploits. 
23. Set “depth of SQL Injection tests to be applied to web pages’ input” to Full and click Finish. 
24. Once the RPT has finished there will be two SQL Agents deployed. If you do not see the SQL Agents launch WebApps Attack and Penetration again and verify you’ve selected the correct settings. 

You have successfully exploited a web application via SQL Injection. 

This concludes lab exercise 2, continue to exercise 3. 
