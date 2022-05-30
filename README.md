# Prometheus--Grafana
* What is Prometheus?
* Prometheus is a free software application used for event monitoring and alerting. It records real-time metrics in a time series database built using a HTTP pull model, with flexible queries and real-time alerting.



![image](https://user-images.githubusercontent.com/58276505/171038326-1d464802-9ee6-424e-9969-11a13f5868c4.png)

## Installation
Use DigitalOcean droplet
![image](https://user-images.githubusercontent.com/58276505/171038904-40ec7283-ed27-4a5f-b217-1330b15945df.png)
![image](https://user-images.githubusercontent.com/58276505/171039065-765eeeea-c8e5-4adb-8d94-9f034c791934.png)

* launch a server Ubuntu (18.04)
* set security group to allow ip_address
* login with ssh key or private key send to you.
* clone github repository
* cd prometheus-course && ls scripts
![image](https://user-images.githubusercontent.com/58276505/171040897-4b5252f1-12d4-4420-83d7-3137fa67b022.png)
* scripts/1-install prometheus
* ps uax | grep grafana
![image](https://user-images.githubusercontent.com/58276505/171041160-5f2781f7-5155-4b1c-ad4a-343005891ae1.png)
![image](https://user-images.githubusercontent.com/58276505/171041350-690e3ed6-0ce4-4f0f-92a0-7d49960f67ed.png)
![image](https://user-images.githubusercontent.com/58276505/171041542-71202633-4b4f-41e4-9054-b59640395098.png)
![image](https://user-images.githubusercontent.com/58276505/171041607-347458fc-bb46-4547-874b-3f359d0283cd.png)
![image](https://user-images.githubusercontent.com/58276505/171041892-e767c858-55cf-4e89-be1e-00c4ae38365b.png)
## Because PROMETHEUS DASHBOARD IS TOO PRIMITIVE,
* INSTALL GRAFANA THAT HAS A BETTER DASHBOARD AND GRAPHICAL INTERFACE
* scripts/3-install grafana
* ps uax | grep grafana
## Check if grafana is working
![image](https://user-images.githubusercontent.com/58276505/171042764-0b2db045-10ed-4754-9b41-48d1a5605b9c.png)

* grafana run by default on port {3000} ; user: {admin} & password: {admin} 
![image](https://user-images.githubusercontent.com/58276505/171042980-2961cb04-ce8a-4b66-8829-1c5bb91ccc15.png)
![image](https://user-images.githubusercontent.com/58276505/171043221-beb6bb51-3390-4c35-9755-53b13de7c7d9.png)

![image](https://user-images.githubusercontent.com/58276505/171043580-99f2d36f-b1c9-42a9-b482-bf1ad1ca28fa.png)
![image](https://user-images.githubusercontent.com/58276505/171043386-725cf233-e741-4216-82f1-cf57c96b8cea.png)

