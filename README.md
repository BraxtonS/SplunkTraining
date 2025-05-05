# SplunkTraining
Learning Splunk from the ground up and simulating real workplace functionality. 


<h2>Description</h2>
Being a cybersecurity professional comes with a steadily evolving toolset as time passes. In order to be proficient in this field, you always stay up to date and knowledgable on as many tools as you can. This has lead me to take up learning Splunk, which is an industry leading SIEM tool that delivers comprehensive visibility, empowers accurate detection, and fuels operational efficiency. I have learned my fair share of SIEM tools over the years wether it be during graduate school or at my current role for the state government, so it is only right to learn one of the most well known tools. In this part of the project I go through installing and configuring Splunk along with the Universal Forwarder, testing searches, grabbing sample data and plugging it into Splunk, and finally making my own test data to ingest and search using Splunk.  
<br />


<h2>Lab Screenshots</h2>

<p align="left">
Donwloaded both Splunk Enterprise and the Universal Forwarder in order to send data to Splunk when testing.: <br/> <br />
<img src="https://i.imgur.com/j6VWly2.png" height="80%" width="80%" alt="Lab Screenshots"/>
  <br />
<img src="https://i.imgur.com/XwwhDr9.png" height="80%" width="80%" alt="Lab Screenshots"/>
<br />
<br />
<p align="center">
The Universal Forwarder required a slight configuration in Splunk Enterprise in order to locate where we would be recieving the data (port 9997). So here is the result in the 'Forwarding and Receiving' settings on Splunk Enterprise.: <br/> <br />
<img src="https://i.imgur.com/pyFJjZN.png" height="80%" width="80%" alt="Lab Screenshots"/>
<br />
<br />
<p align="center">
In order to further confirm that everything is working, I checked that my hostname appeared in the 'Data Summary' section under 'Search and Reporting'. I added a photo of my hostname in the command prompt for clarity.: <br/> <br />
<img src="https://i.imgur.com/SAVnwKQ.png" height="80%" width="80%" alt="Lab Screenshots"/>
  <br />
<img src="https://i.imgur.com/3tksbk6.png" height="80%" width="80%" alt="Lab Screenshots"/>
<br />
<br />
<p align="center">
After configuring and confirming everything was working, I started with a simple search for all data from my hostname. I made sure to set the results to 'verbose' mode which will return all event and field data.: <br/> <br />
<img src="https://i.imgur.com/QTRUOLv.png" height="80%" width="80%" alt="Lab Screenshots"/>
<br />
<br />
<p align="center">
So my next task was finding a sample dataset and getting it into Splunk. So I managed to find a sample dataset with plenty of sourcetypes on Github called Boss of the SOC (BOTS) Dataset Version 3. After following the listed instructions I managed to get the dataset into Splunk, with confirmation.: <br/> <br />
<img src="https://i.imgur.com/UyG5r7t.png" height="80%" width="80%" alt="Lab Screenshots"/>
<br />
<br />
