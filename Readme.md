## Inspiration

&emsp;&emsp;Azure functions helps organization and developers to automate the tasks and work function easier which lets user/customer access application without downtime and friendly.

&emsp;&emsp;In this project we are addressing problems associated with businesses and events organization how azure function helps users to register form for events and share it to event manager in a timely manner using automation time rule.

## What it does

&emsp;&emsp;Raptorz Event register android application - helps user/customer to fill form with their relevant data which is stored in cosmodb via azure function post service feature and time trigger configured which lets event manger about event registration details in timely manner via sendgrid gateway.

###More in detail about application,

<li>**Httptrigger:-**</li>
 &emsp;&emsp; which used to save event data in cosmodb.

<li>**Automation rule:-**</li>
 &emsp;&emsp;Automation rule created which let event manager about the feedback data at a particular time period in our project we have set morning 9 am rule which send reminder notification.

<li>**Timetrigger:-**</li>
 &emsp;&emsp;which send mail communication to Event admin about user in a timely manner.

<li>**Azure cosmodb(Backend source):-**</li>
&emsp;&emsp;User Data stored in cosmodb.

<li>**Sendgrid :-**</li>
&emsp;&emsp;Mail communication sent to Event admin in a timely manner by Azure function time trigger.

## How we built it

###Involves 4 steps:-

<li>**Azure Functions-**</li>
&emsp;&emsp;Azure post function store the user data into cosmodb a serverless feature.

<li>**Automation rule:-**</li>
&emsp;&emsp;Pre built features enabled  helps to notify event organizers about the event participants data.

<li>**Github:-**</li>
&emsp;&emsp;Web view site built using html, css and Java query in which form source link is embedded-[WebviewLink](https://raptortcc.github.io/).

<li>**Andriod apk:-**</li>
&emsp;&emsp;Web view application built using Java in which the form source linked embedded-[Andriod APK](https://drive.google.com/drive/folders/1--AeenguzpUb3qVRcZczHWneqcaZfCQf?usp=sharing).

## Accomplishments that we're proud of

&emsp;&emsp;Learnt Aabout azure functions and its automation feature and cosmodb serverless db.

##  What's next 

&emsp;&emsp;Need to explore and learn about functions integration to other applications in depth.
