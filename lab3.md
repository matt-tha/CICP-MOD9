####Instructions

If you have completed exercise 2 you must first undo the Internet Explorer proxy settings before beginning exercise 3. Launch Internet Explorer, click the gear in the top right corner, select Internet Options, from the Connections tab click LAN Settings and uncheck “Use a proxy server for your LAN”.

1. We’ll begin by identifying the site we’d like to exploit and manually adding it to Impact Pro. Type “ core-xss.tha “ into the Internet Explorer address bar and press enter. 
2. Click the first list item, “XSS Injection case #1 (tag-level body GET)”. This is our target, copy the URL to your clipboard and return to Impact Pro. 
3. Create a new scenario by right clicking the scenarios folder and selecting New Scenario. Name the scenario “ XSS Test 1 “  and click OK. 
4. Click on the XSS Test 1 scenario to display the empty URLs list. 
5. Right click and select New Web Page. Confirm the target is XSS Test 1, if it is not change the target by clicking the ellipsis to the right of the field. Paste the URL from Internet Explorer into the URL field and click OK. Verify the URL has been added to the scenario.
6. Launch RPT number 2, WebApps Attack and Penetration. Specify scenario XSS Test 1 as the target and de-select all risk types other than A3 – Cross Site Scripting (XSS). All other settings may be left as default. 
7. Once the RPT has completed verify that a XSS Agent has been created and is listed under the URL. If no agent has been created launch RPT number 2 again and verify your settings. 

You have successfully exploited a Web Application using Cross Site Scripting. 

