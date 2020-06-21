---
published: false
---
## Monitoring

![alt text](https://media-exp1.licdn.com/dms/image/C5612AQGwQQIN4BFt6w/article-cover_image-shrink_423_752/0?e=1598486400&v=beta&t=66y0ToHqkhzEHaetx-nUtXfSAZfHW4NN2krF-xgMAW0)

Monitoring can further be classified into various subtasks that we want to accomplish using it. Monitoring in simple terms can simply be defined as _**" Collecting data about the system and analysing it based on needs for alerting / performance and other needs"**_.




### So sub categories of monitoring can be :

1. **Alerting** - This category mainly focuses on defining certain criteria where you want to be notified if certain things go wrong and is usually the main motive for monitoring.


2. **Debugging** - This category helps in finding the issues and errors with the system, as when alerted about faulty state of a system you might want to identify the issue with it, so this category helps with identifying the root causes for issues.


3. **Pattern Analysis** - This category is helpful if you want to analyse certain patterns with system like trends as with above two you would only look into in case of trouble but you might also want to know the trends that your system follows.


![alt text](https://media-exp1.licdn.com/dms/image/C5612AQGxsfIpwo7Rcg/article-inline_image-shrink_1000_1488/0?e=1598486400&v=beta&t=1Pu1tHnR970wRpzyAHq-6qrghdrgdzVfdp_FzRvpPzs)


**White Box Monitoring**

This type of monitoring mainly refers to the monitoring the internal states of the applications running on your system. Mainly this type of monitoring involves exposing metrics that are specific to your application like total number of http requests received / latency etc.

**Black Box Monitoring**

This type of monitoring mainly refers to the monitoring state of services in the system. Using this type of monitoring we ensure things like status of the application being alive or dead , cpu / disk usage etc.


In a traditional approach black box monitoring was used where sys admins were responsible in maintaining the application status , disk / cpu usage on the systems but with the new era of containers and DevOps the application developers prefer moving towards the white box monitoring to take ownership of the application, to ensure the application works without any issues or errors as expected.


Using the Black Box Monitoring involves using tools like Nagios , Zabbix which are mainly based on the ideas of running custom checks on the systems to identify status of various applications / services whose response are mainly as 0 or 1 to indicate the status of the service being monitored. This approach mainly focuses on identifying the present status of the application rather then focusing upon the trend or issues with the applications.


Whereas using white box monitoring involves using tools like Prometheus which enables you to export metrics like total number of http requests received by the application , errors logged etc.


**Comparing White Box with Black Box Monitoring**


Lets consider a scenario where we have a system whose disk space is filling up, lets say we have configured alerts using black box monitoring tools to notify us that when capacity is 60% full as low level risk when it rises to 80% and beyond as a high level risk that we want to fix immediately.

![alt text](https://media-exp1.licdn.com/dms/image/C5612AQGZxvDw_NAWqw/article-inline_image-shrink_1500_2232/0?e=1598486400&v=beta&t=aaDKaUbNV25t0etyvvX9u7OS-Q9EaLWzHJwg6vAAS6E)

If the disk space of a system is filling up fast and goes beyond 80% the black box monitoring tools would throw alerts with high risk to be fixed. But the problem arises if we want to fix the alerts then we want to know some metrics about the system like the rate at which disk capacity was increasing on the system , the internal application metrics about disk usage. Knowing these metrics can help us solve the issues in lesser time.


If we have a white box monitoring solution enabled for the same scenario then observing the graphs for rate of disk capacity usage and application disk usage for some specific timelines we can make predictions about trend at which disk capacity was filling up also make our predictions of which app may be behaving faulty at this scenario and knowing these specifics can help us resolve the issues with less time.

![alt text](https://media-exp1.licdn.com/dms/image/C5612AQHn-U7UciRW_w/article-inline_image-shrink_1000_1488/0?e=1598486400&v=beta&t=DtBd0Ro5sD7huc4cjIejTQLJSno8GVhw0QsDc9plPps)