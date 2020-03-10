# health-monitoring-sysytem
To know the health conditions of a patient at your fingertips using IOT.

Step 1:- First of all, user needs to Create a Account on ThingSpeak.com, then Sign In and click on Get Started.


Step 2:-  Now go to the ‘Channels’ menu and click on New Channel option on the same page for further process.


Step 3:- Now you will see a form for creating the channel, fill in the Name and Description as per your choice. Then fill ‘Pulse Rate’, ‘Temperature’ and ‘Panic’ in Field 1, Field 2 and Field 3 labels, tick the checkboxes for the Fields. Also tick the check box for ‘Make Public’ option below in the form and finally Save the Channel. Now your new channel has been created.


Step 4:- You will see three charts as shown below. Note the Write API key, we will use this key in our code.


Step 5:- Now, we will use ThingHTTP app of the server to trigger the IFTTT applet for data entry to Google sheets and send email/sms. ThingHTTP enables communication among devices, websites, and web services without having to implement the protocol on the device level. You can specify actions in ThingHTTP, which you want to trigger using other ThingSpeak apps such as React.

To make New ThingHTTP, we will need URL for triggering which we will get from IFTTT.


