Post - mortem…..

Issue Summary 

Duration: 1 hour and 30 minutes (12:00 PM - 1:30 PM UTC 18-08-24) 

Impact: A significant portion of our user base experienced slow loading times and also failed to load images on our platform.
Approximately 70% of users were affected.

Root Cause: A surge in traffic combined with inefficient image processing and caching led to overwhelming our image server.


Timeline
12:00 PM UTC: Initial user complaints started pouring in through our support channels regarding slow image loading.
12:15 PM UTC: Monitoring alerted us to a spike in image server CPU and memory utilization.
12:30 PM UTC: The engineering team was mobilized to investigate the issue. Initial assumptions pointed to a database or network problem.
12:45 PM UTC: After ruling out database and network issues, the focus shifted to the image server.
1:15 PM UTC: The root cause was identified: inefficient image processing and caching leading to server overload.
1:30 PM UTC: A temporary solution was implemented to reduce image processing load, and the system began to stabilize.Root Cause and Resolution
The root cause of the issue was an inefficient image processing pipeline. As traffic surged, the image server struggled to handle the increased load, resulting in slow response times and failures.

