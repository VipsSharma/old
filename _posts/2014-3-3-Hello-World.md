---
layout: post
title: ZABBIX “ The Journey to Distributed System Monitoring ”
published: true
---

## Exploring Zabbix
The new world of distributed systems present a great sense of reliability and features that require every component of an enterprise to be maintained in a Highly Available ( HA ) Cluster so that the minimum downtime can be ensured. This Architecture of maintaining all components in HA cluster presents a difficult task to track down all components physical as well as software level so that any issues can be tracked down before any mishappening occurs.


![alt text](https://media-exp1.licdn.com/dms/image/C5112AQGGboM_IDMSmQ/article-inline_image-shrink_1000_1488/0?e=1598486400&v=beta&t=82R1VIW7p6xv631i7pW8rhz8YuPMsjpGNNLoSuOQgRs)


![alt text](https://media-exp1.licdn.com/dms/image/C5112AQEJRwaQgGaqmA/article-inline_image-shrink_1000_1488/0?e=1598486400&v=beta&t=cNiFX3thejuhUsD8-NQ0pVafTnLaMdaWNvs2toe4sA0)




One such solution to track down the components in such an environment might be ZABBIX. It is an enterprise-class open source distributed monitoring solution that helps to monitor various parameters of network health as well as the performance of servers. Also one can configure various alerts using ZABBIX these alerts can be SMS or might be E-Mail based alerts. It also provides a Dashboard where one can track down the status of network as well as the health of servers. Whereas it also provides data visualisation based on the stored data.



![alt text](https://media-exp1.licdn.com/dms/image/C5112AQE1lm6q0oEE_w/article-inline_image-shrink_1000_1488/0?e=1598486400&v=beta&t=Z_NNLsJx4D2gWECDLJ4_d2nWwYe22ieyPK_9w2vxoBQ)



It supports both polling and trapping. In polling it simply polls the data out of the resources like switch and informs whenever any such failure occurs while this activity is being performed whereas in trapping it picks up any SNMP signal that is being sent to it and will inform about any such failure of the specified resource.


![alt text](https://media-exp1.licdn.com/dms/image/C5112AQFA9T8pm9FIRg/article-inline_image-shrink_1000_1488/0?e=1598486400&v=beta&t=RvdULs-W2KnXk0LXE7KuyqJNrMRksMARkyJ8L0E3xW4)



Various Servers as well as Network components can be configured and monitored using ZABBIX. It also provides log level monitoring and also has default templates for monitoring specific services like MYSQL etc. Using such a centralized monitoring system one ensure that your components work fine all day long and also provide with real time Graphs and Visualisations to identify appropriate failures in the system whenever required.


![alt text](https://media-exp1.licdn.com/dms/image/C5112AQH5EDSjSfIQzw/article-inline_image-shrink_1000_1488/0?e=1598486400&v=beta&t=4QbONfUeI7LiWV3Pt_rSK68U9wjiZNfzSNvZFYXcKnM)



ZABBIX also provides with an API endpoint that can furthur be explored and get various different tasks automated. Like an API endpoint of Zabbix can be configured to let you know about all such servers and network components that failed to comunicate with the ZABBIX server in the past time.



![alt text](https://media-exp1.licdn.com/dms/image/C5112AQF1BdrIl7Askw/article-inline_image-shrink_1000_1488/0?e=1598486400&v=beta&t=KZXW3wIOrkFAUYSsyNwj5MrelfdLfLPSQY5gASZGVy4)




Using ZABBIX one can achieve various results like Data Gathering, threshold values can be defined for various components like API response time and network response time etc and triggers can be set which provides flexible alert system for these components. Visualisation for data can be done in forms of graphs and charts. It also provides a web interface ( dashboard ) to monitor all such activities. It works using binary daemons written in C. So, It does not affect the performance of the system and is easily portable.

_Zabbix “ The Open Source Tool ” that opens door to various possibilities and features that you can use to ensure your system works with minimum downtime and also get visualisations of your performance matrices of the system._


