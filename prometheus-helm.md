## requirment
* Minikube cluster installed

### Recap Prometheus architecture

### How to deploy all parts into k8s cluster - 3 options
* Best practice to use prometheus is helm

### Setup with Prometheus Operator using Helm
* kubectl get pod
* helm install prometheus stable/prometheus-operator   ## helm Installation; name => prometheus; official-helm-repo => stable; chart-name => prometheus-operator

* kubectl get pod
* kubectl get all

https://github.com/helm/charts/tree/master/stable/prometheus-operator

### Understanding what components were created and what they do?

### What's inside Prometheus Operator?



https://github.com/operator-framework/awesome-operators

* kubectl get pod
* helm install prometheus stable/prometheus-operator       ## where name => prometheus, official helm repository => stable, chart name => prometheus-operator
* kubectl get pod
* kubectl get all
* kubectl get configmap
* kubectl get secret      # helm makes it easy to get secrets for Grafana, prometheus, Operator. Certificates; username & passwords for diff UI

* kubectl get statefulset

* kubectl describe statefulset "prometheus-statefulsetResult" > prom.yaml .....          ......  ....Replace "prometheus statef"
* kubectl describe statefulset "alert-statefulsetresult" > alert.yaml    ..........      .....    ...Replace "alert statefulset"

* kubectl get deployment

* kubectl describe deployment "prometheus-statefulsetResult" > oper.yaml

### Access Grafana UI
* kubectl get service
* kubectl get pod
* kubectl logs prometheus-grafana-### -##
* kubectl port-forward deployment/prometheus-grafana 3000
* 
### Access Prometheus UI

![image](https://user-images.githubusercontent.com/58276505/180428307-6201fc43-0f3d-4688-9a7d-6dcaf1de1b69.png)

![image](https://user-images.githubusercontent.com/58276505/180431287-f703a740-7175-4973-9d3c-43df0daf6bc4.png)

![image](https://user-images.githubusercontent.com/58276505/180431534-eec908a4-0f6f-4796-816a-e831bdd79315.png)





# Prometheus with 3rd-party application (e.g mongoDB)

![image](https://user-images.githubusercontent.com/58276505/180456215-220c57ac-e983-4472-9835-c5a4022527a2.png)

![image](https://user-images.githubusercontent.com/58276505/180462787-36708007-0629-44a3-a692-15feef034001.png)

* Minikube cluster installed
* kubectl get pod
* kubectl get svc
* kubectl port-forward service/prometheus-kube-prometheus-prometheus 9090
* kubectl get servicemonitor
* kubectl get servicemonitor prometheus-kube-prometheus-grafana -oyaml
* kubectl get crd

### Use of exporter to expose the metrics at endpoints

![image](https://user-images.githubusercontent.com/58276505/180468774-5e31b4f6-f6f9-431f-b032-2f7bf09b4666.png)

![image](https://user-images.githubusercontent.com/58276505/180498211-a101b7dd-7179-46bf-9cf8-93374d57ea00.png)

* Either declare a yaml file of the 3 component to install or using helm chart will install a complete setup but with default values /parameters
* Default parameters can be modified using => 
* helm show values [chart name] > values.yaml
* and then open using the editor vsc


