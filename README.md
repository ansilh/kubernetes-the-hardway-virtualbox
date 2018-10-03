# kubernetes-the-hardway-virtualbox
Setup a kubernetes cluster in VirtualBox

This guide will give an overall idea on how each components works in kubernetes.

#### Cluster overview
![Overview](https://raw.githubusercontent.com/ansilh/kubernetes-the-hardway-virtualbox/master/images/overview.PNG)

###### Disclaimer: This is a derivative work of [kubernetes-the-hard-way](https://github.com/kelseyhightower/kubernetes-the-hard-way) by Kelsey Hightower and all licencing will apply as same as original document

Part 1 - [Prerequisites](01.Prerequisites-VM-Configuration.md)

Part 2 - [A Virtual LoadBalancer for Highly available API server](02.Prerequisites-HA-LB-Configuration.md)

Part 3 - [Install Client Tools](03.Install-Client-Tools.md)

Part 4 - [Certificate Authotiry and Certificates](04.Certificate-Authority.md)

Part 5 - [Kubernetes Configuration Files](05.Kubernetes-configuration-files.md)

Part 6 - [Generating the Data Encryption Config and Key](06.Data-encryption-keys.md)

Part 7 - [Bootstrapping the etcd Cluster](07.Bootstrapping-etcd.md)

Part 8 - [Bootstrapping the Kubernetes Control Plane](08.Bootstrapping-kubernetes-controllers.md)

Part 9 - [Bootstrapping the Kubernetes Worker Nodes](09.Bootstrapping-kubernetes-workers.md)

Part 10 - [Configuring kubectl for Remote Access](10.Configuring-kubectl.md)

Part 11 - [Provisioning Pod Network Routes](11.Pod-Network-Routes.md)

Part 12 - [Deploying the DNS Cluster Add-on](12.DNS-Add-On.md)

Part 13 - [Bare Metal Load Balancer Configuration](13.Load-Balancer.md)

Part 14 - [Test LoadBalancer](14.Test-Loadbalancer-type.md)

Part 15 - [Deploy Metric Server](15.Deploy-Metric-Server.md)

Part 16 - [Deploy Dashboard](16.Dash-Board.md)

Part 17 - [Dynamic iSCSI Volume Provisioniner](17.Dynamic-iSCSI-Volume-Provisioner.md)

Note: Until unless specified , all command should be executed from `lb-01`
