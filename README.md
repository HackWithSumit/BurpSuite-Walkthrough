<B><h2>BurpSuite Walkthrough</b></h2>
<br>
Burp Suite walkthrough typically refers to a step-by-step guide on how to use Burp Suite, a popular tool for web application security testing. The walkthrough usually covers the basics, such as setting up Burp Suite, configuring it with a browser, and performing various security tests, like intercepting traffic, scanning for vulnerabilities, and exploiting them.

<b><h2>Setting Up Burp Suite</b></h2>

⚪Download and Install: Install Burp Suite from the official PortSwigger website.
<br>
⚪Launch Burp Suite: Open Burp Suite, and you'll be greeted by the main dashboard.
<br>
⚪Configure the Browser: Set up your browser to use Burp as a proxy. 
<br>
⚪This usually involves setting the proxy settings in your browser to point to 127.0.0.1:8080.
<br>

<b><h2>Dashboard</b></h2>

The first tab that should be open is the Dashboard tab, but keep in mind that you can drag these tabs around so the order of your tabs may not match mine. I recommend putting them in an order that fits your workflow.



![image](https://github.com/user-attachments/assets/d000cfcd-06c0-4a17-95b7-e0851a75c8f4)


The Tasks section is where you can keep track of ongoing scans and processes

![image](https://github.com/user-attachments/assets/a4b4c7a0-47d2-4c8e-8fcd-de1f8b568791)

The Issue activity section is where you can see the findings from your scans.

Finding confidence is shown by how filled in the circle around the “!” is, a tentative finding that may be a false positive will be an outline, while certain findings are filled in completely. Finding severity is shown by color, with the highest severity being red.

![image](https://github.com/user-attachments/assets/cd33dc4f-1517-4d7c-8503-b152f92ebede)

The Advisory section provides detailed information about each security finding. It covers vulnerabilities, their impact, and even includes links for further exploration. You can also switch between tabs to see the triggering request and response, as well as find the issue’s location in the site’s source code.

![image](https://github.com/user-attachments/assets/268065f9-24ed-43bb-b765-df6308510748)

The event log shows basic activity information about things like scans and other processes.

<b><h2>Target</b></h2>

The Target tag allows you to view the site map of the target site, as well as what requests you’ve made and what findings you have found for each endpoint.

![image](https://github.com/user-attachments/assets/50162d3b-78c9-43c7-918b-ae8dde754b71)

Site Map: On the left, you’ll find the site map. It lists all the endpoints of the target website. Here’s what each icon represents:

📁 Folder icons: Directories
<br>
📄 Document icon: Files
<br>
⚙️ Gear icon: Parameterized requests
<br>
  
If a URL in the sitemap is greyed out, it means it might have been mentioned in the site’s responses or found during a scan but hasn’t been visited yet.

![image](https://github.com/user-attachments/assets/4480d94f-1eaa-47d3-9443-2f14f1cc494d)

The contents section shows the requests you have made to the selected URL. In the lower section, you can view the request and response in detail.

![image](https://github.com/user-attachments/assets/27c4c4c0-70c7-4b2a-aa62-40df5de7fc77)

The Inspector tab here can be clicked on to unfold a section that allows you to view the headers and attributes of the request and response.

![image](https://github.com/user-attachments/assets/f0b34738-b68e-4483-b696-b8c337fea98c)

If you select some text in the request or response, the inspector also allows you to view the length of the selected text as well as decode the selected text.




















