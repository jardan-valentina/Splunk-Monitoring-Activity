<h1>Let's Go Splunking!</h1>

You have just been hired as an SOC analyst by Vandalay Industries, an importing and exporting company.
<ul>
<li>Vandalay Industries uses Splunk for their security monitoring and have been experiencing a variety of security issues against their online systems over the past few months.</li>
<li>You are tasked with developing searches, custom reports, and alerts to monitor Vandalay's security environment in order to protect them from future attacks.</li>
</ul>

<h2>Your Objective</h2>
Utilize your Splunk skills to design a powerful monitoring solution to protect Vandalay from security attacks.

<h2>Topics Covered in This Assignment</h2>
<ul>
    <li>Researching and adding new apps</li>
    <li>Installing new apps</li>
    <li>Uploading files</li>
    <li>Splunk searching</li>
    <li>Using fields</li>
    <li>Custom reports</li>
    <li>Custom alerts</li>
</ul>

<h2>Vandalay Industries Monitoring Activity Instructions</h2>
<h2>Step 1: The Need for Speed</h2>

<b>Background:</b> As the worldwide leader of importing and exporting, Vandalay Industries has been the target of many adversaries attempting to disrupt their online business. Recently, Vandalay has been experiencing DDOS attacks against their web servers.
Not only were Vandalay web servers taken offline by a DDOS attack, but upload and download speed were also significantly impacted after the outage. Your networking team provided results of a network speed run around the time of the latest DDOS attack.

<b>Your Task:</b> Create a report to determine the impact of the DDOS attack on upload and download speed. Create an additional field to calculate the ratio of the upload speed to the download speed. To do so, complete the following steps:
<ul>
<li>Upload the following file containing the system speeds around the time of the attack:</li>
<ul>
  <li> <a href="https://drive.google.com/file/d/1sAIEh_vxhjJJpj3NiPx8Wele_-cfEZTK/view" target="_BLANK">Speed Test File</li> 
</ul>
<li>Using the eval command, create a field called ratio that shows the ratio between the upload and download speeds.</li>

<b>Hint:</b>The format for creating a ratio is: | eval new_field_name = 'fieldA' / 'fieldB'

<li>Create a report using Splunk's table command to display the following fields in a statistics report:</li>
<ul>
   <li> _time </li>
    <li>IP_ADDRESS </li>
   <li> DOWNLOAD_MEGABITS </li>
    <li>UPLOAD_MEGABITS </li>
   <li> ratio </li>
</ul>
<b>Hint:</b>Use the following format for the table command: | table fieldA fieldB fieldC

<li> Answer the following questions in the M19 Submission File:</li>
<ul>
    <li>(1) Based on the report you created, what is the approximate date and time of the attack?</li>
    <li>(2) How long did it take your systems to recover?</li>
</ul>
Make sure to include a screenshot of your report along with the answers to these questions.
</ul>
