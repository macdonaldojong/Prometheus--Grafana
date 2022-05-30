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
![image](https://user-images.githubusercontent.com/58276505/171043930-4677d2fe-f843-41a1-b4c3-7f5b98888ff0.png)
* scripts/3-install grafana
* ps uax | grep grafana
## Check if grafana is working
![image](https://user-images.githubusercontent.com/58276505/171042764-0b2db045-10ed-4754-9b41-48d1a5605b9c.png)

* grafana run by default on port {3000} ; user: {admin} & password: {admin} 
![image](https://user-images.githubusercontent.com/58276505/171042980-2961cb04-ce8a-4b66-8829-1c5bb91ccc15.png)
![image](https://user-images.githubusercontent.com/58276505/171043221-beb6bb51-3390-4c35-9755-53b13de7c7d9.png)

![image](https://user-images.githubusercontent.com/58276505/171043386-725cf233-e741-4216-82f1-cf57c96b8cea.png)
![image](https://user-images.githubusercontent.com/58276505/171043580-99f2d36f-b1c9-42a9-b482-bf1ad1ca28fa.png)

## Basic concepts of prometheus:
![image](https://user-images.githubusercontent.com/58276505/171044494-73c2d23c-a52a-403a-8300-7fd0f142c2a1.png)
![image](https://user-images.githubusercontent.com/58276505/171044729-b851ffd7-ee49-4a0c-8f99-74e9757cb7ef.png)
![image](https://user-images.githubusercontent.com/58276505/171044920-d06bb256-fc27-4df9-a18e-af1f7290681a.png)

## PrometheusConfiguration
![image](https://user-images.githubusercontent.com/58276505/171045034-da7dcf26-f69c-4d01-a030-9b8ba360ffbc.png)
![image](https://user-images.githubusercontent.com/58276505/171045177-8df303ac-d13a-4e74-bceb-24176deb077d.png)

## Scrape metrics

![image](https://user-images.githubusercontent.com/58276505/171047157-918dcad6-98f8-44b9-8f09-3c38f04b8eb2.png)
![image](https://user-images.githubusercontent.com/58276505/171048250-df9b4b1c-4d22-4d6e-8e35-c614edccc80b.png)

![image](https://user-images.githubusercontent.com/58276505/171048301-a0e42e98-730c-43fe-9503-058ee35608da.png)

## Node exporter
* install a node exporter:
![image](https://user-images.githubusercontent.com/58276505/171048918-b33c98cf-26f3-4a1e-8042-e8ab328afd93.png)
![image](https://user-images.githubusercontent.com/58276505/171048980-f1c2f94b-9965-4832-89f5-c5b045f56991.png)
![image](https://user-images.githubusercontent.com/58276505/171049114-4194df97-ad91-4b00-92c1-9bc1d52a6a44.png)










