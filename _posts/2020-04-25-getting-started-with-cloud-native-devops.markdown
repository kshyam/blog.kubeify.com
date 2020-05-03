---
layout: post
title:  Getting Started with Coud Native DevOps
date:   2020-04-25 15:01:35 +0300
image:  /blog/cloud-native-devops.png
tags:   CloudNative DevOps Kubernetes Docker CICD
---

## What is Cloud Native DevOps?

Based on the name, Cloud Native DevOps may seem to running containerized application in the cloud, But it's more then that.

### Cloud Native DevOps = Cloud Native apps + DevOps.

Cloud Native DevOps is a method to structure your teams to take advantage of Automation and Scalability that Cloud Native technologies like containers and Kubernetes offer.

Cloud Native technologies are designed to be:

1. **Resilient.** Embracing failures instead of trying to prevent them, taking advantage of the dynamic nature of running on a platform.
2. **Agile.** Allowing for fast deployments and quick iterations.
3. **Operable.** Adding control of application life cycles from inside the application instead of relying on external processes and monitors.
4. **Observable.** Providing information to answer questions about the application state.

#### We can define Cloud Native DevOps as a set of practices that involves continuous improvement, automation, cross-functional teams, better alignment with business needs.

These principles apply to people, tools, culture, and process, not on the actual application env cloud or on-prem, apps can be on public cloud, private cloud or on-prem, end gole to achieve scalable, reliable and high available system by construction.

![]({{ site.baseurl }}/images/blog/devops-journey.png)


### How to implement Cloud Native DevOps?

1. Adopt Microservices Patterns
2. Using Containerization
3. Adopt Container Orchestration - Kubernetes
4. Write 12-factor Apps
5. Increase Automation in CI/CD pipelines
6. Exposing health check
7. Collecting telemetry data

### What are advantages of Cloud Native DevOps?

1. Lowering the cloud costs
2. Faster deployments
3. Better control over IT resources
4. Achieving true DevOps
5. Speedy innovation and Scalability

### what are Cloud Native DevOps Process & tools?

1. Source Code Management (SCM)
2. Container Registry
3. Orchestration and Schedulers
4. Continuous Integration / Continuous Deployment(CI/CD)
5. Observability and Analysis - Monitoring 
6. Observability and Analysis - Logging
7. Provisioning - Security & Compliance
8. Storage/Volume Management
9. Networking
10. Service Discovery
11. Orchestration & Management - Service Mesh
12. Provisioning - Automation & Configuration 
13. Builds and Management

### 1. Source Code Management (SCM)
SCM tool selection is the first step in Cloud Native DevOps or any DevOps Process. My Suggestion will be go with the GIT based SCM system. these days GIT based system are very populer. You have follow option as persent in the marker.

* Github
* Gitlab
* Bitbucket
* AWS CodeCommit
* PreForce
* Visual Studio Team Foundation Server (VSTFS)
* Mercurial 
* Subversion (SVN)
* CVS


![]({{ site.baseurl }}/images/blog/source-code-management.png)

Above source code management systems can be used as
* Hosted system like Github, Gitlab or bitbucket
* Self Hosted systems like Gitlab etc.


### 2. Container Registry
You have develped your application as microservices so you need any container tool like Docker to deliver your application, while using Docker you will create Docker Images, So you will need Container Registry system to store you images.

You can assume container registry system same like your source code management tools where you can host you source code, in simmiler manner you can store you docker images on following Container Registry. 

* Docker Registry/DockerHub form Docker
* Harbor - open source - Cloud Native Computing Foundation (CNCF)
* Quay form Red Hat
* Gitlab Container Registry
* JFrog Artifactory form JFrog
* Portus form SUSE Linux
* Amazon Elastic Container Registry (ECR) form Amazon Web Services
* Google Container Registry form Google
* Azure Registry form Microsoft
* IBM Cloud Container Registry form IBM
* DigitalOcean Container Registry
* Alibaba Cloud Container Registry
* Dragonfly form Cloud Native Computing Foundation (CNCF)
* Codefresh Registry form Codefresh
* Kraken form Uber

![]({{ site.baseurl }}/images/blog/container-registry.png)

More tools can be found at <a href="https://landscape.cncf.io/category=container-registry&format=card-mode&grouping=category" target="_blank">https://landscape.cncf.io/</a>


### 3. Orchestration and Schedulers
Kubernetes is one of the most used and populer tool to adopt as orchestration system form Google and now managed by Cloud Native Computing Foundation (CNCF). There are few more tools you can find below in the image like 
* Docker Swarm form Docker
* Open Shift form Redhat
* Marathon
* Diego form Pivotal Cloud Foundry
* Apache Mesos form Apache Software Foundation
* Rancher
* Nomad form HashiCorp
* Amazon Elastic Container Service (ECS) and AWS Kubernetes Engine
* Azure Service Fabric and Azure Container Services form Microsoft
* Google Kubernetes Engine
* Nebula Container Orchestration - built for IoT 


![]({{ site.baseurl }}/images/blog/orchestration-and-schedulers.png)

{% include cta.html %}

### 4. Continuous Integration / Continuous Deployment(CI/CD)

Continuous Integration / Continuous Deployment is the core process of DevOps, The tools who provide unlimited capability in pipeline automation, speed of continuous integration system and super fast continuous deployment to the staging/production systems are very critical. These CI/CD systems plays a vital role while adopting and getting team success in  Cloud Native DevOps.

* <a href="https://razorops.com/" target="_blank">RazorOps</a> - a fast growing Container Native CI/CD platform.
* jenkins X
* GoCD
* CircleCI
* GitlabCI
* Codefresh
* Drone
* TeamCity
* CodeShip
* Wercker
* Spinnaker
* Bamboo
* TravisCI
* Buddy
* argo
* Google Cloud Build
* Semaphore

![]({{site.baseurl}}/images/blog/continuous-integration-continuous-deployment.png)

More tools can be found at <a href="https://landscape.cncf.io/category=continuous-integration-delivery&format=card-mode&grouping=category" target="_blank">https://landscape.cncf.io/</a>

{% include razorops-cta.html %}

### 5. Observability and Analysis - Monitoring 

* Amazon CloudWatch form Amazon Web Services
* AppDynamics
* Application High Availability Service form Alibaba Cloud
* Applications Manager form ManageEngine
* AppNeta
* AppOptics
* SolarWinds
* Aternity from Riverbed Technology
* Azure Monitor form Microsoft
* Beats form Elastic
* InfluxData 
* Grafana form Grafana Labs 
* Nagios 
* New Relic 
* OpenMetrics by Cloud Native Computing Foundation (CNCF) 
* Prometheus by Cloud Native Computing Foundation (CNCF)  
* Thanos by Cloud Native Computing Foundation (CNCF)
* Weave Cloud form Weaveworks

More tools can be found at <a href="https://landscape.cncf.io/category=monitoring&format=card-mode&grouping=category" target="_blank">https://landscape.cncf.io/</a>


### 6. Observability and Analysis - Logging

* Alibaba Cloud Log Service form Alibaba Cloud
* Elastic
* Fluentd form Cloud Native Computing Foundation (CNCF)
* Grafana Loki form Grafana Labs
* Graylog
* Humio
* LogDNA
* Loggly
* Logiq
* Logstash form Elastic
* Logz.io
* Loom Systems
* Scalyr
* Sematext
* Splunk
* Sumo Logic

More tools can be found at <a href="https://landscape.cncf.io/category=logging&format=card-mode&grouping=category" target="_blank">https://landscape.cncf.io/</a>


### 7. Provisioning - Security & Compliance

* Alcide
* Anchore
* Aqua form Aqua Security
* kube-bench form Aqua Security
* kube-hunter form Aqua Security
* Trivy form Aqua Security
* Black Duck
* Synopsys
* Bloombase
* Capsule8
* Cert-manager form Jetstack
* Check Point form Check Point Software Technologies
* Chef InSpec from Chef Software
* Clair form Red Hat
* Fossa
* Grafeas form Google
* Falco form Cloud Native Computing Foundation (CNCF)
* in-toto form Cloud Native Computing Foundation (CNCF)
* Notary form Cloud Native Computing Foundation (CNCF)
* Pen Policy Agent (OPA) form Cloud Native Computing Foundation (CNCF)
* The Update Framework (TUF) form Cloud Native Computing Foundation (CNCF)
* NeuVector
* OpenSCAP form Red Hat
* Prisma Cloud Security Suite form Palo Alto Networks
* Sonatype Nexus
* Sonobuoy form VMware

More tools can be found at <a href="https://landscape.cncf.io/category=security-compliance&format=card-mode&grouping=category" target="_blank">https://landscape.cncf.io/</a>



### 8. Storage/Volume Management

* Alluxio
* Amazon Elastic Block Store (EBS) form Amazon Web Services
* Arrikto
* Azure Disk Storage form Microsoft
* Ceph from Ceph Foundation
* ChubaoFS form Cloud Native Computing Foundation (CNCF)
* Container Storage Interface (CSI) form Google
* Datera
* Dell EMC
* Diamanti
* DriveScale
* Elastifile
* Gluster form Red Hat
* Google Persistent Disk form Google
* Hedvig
* Hitachi
* HPE Storage form Hewlett Packard Enterprise
* IBM Storage form IBM
* INFINIDAT
* Kasten
* Longhorn form Cloud Native Computing Foundation (CNCF)
* MayaData
* MinIO
* MooseFS form Tuxera
* NetApp
* Nutanix Objects form Nutanix
* OpenEBS form Cloud Native Computing Foundation (CNCF)
* OpenIO
* OpenSDS
* Portworx
* Pure Storage
* Quobyte
* Reduxio
* Robin form Robin Systems
* Rook form Cloud Native Computing Foundation (CNCF)
* Sandstone
* Scality RING
* StorageOS
* Swift form OpenStack
* Triton Object Storage form Joyent
* Velero form VMware
* XSKY form XSKY Data Technology


### 9. Networking

* Antrea form VMware
* Aporeto 
* Aviatrix form Aviatrix Systems
* Big Switch Networks
* Cilium form Isovalent
* Container Network Interface (CNI) form Cloud Native Computing Foundation (CNCF)
* Contiv form Cisco
* Cumulus form Cumulus Networks
* DANM form Nokia
* FD.io form LF Networking
* Flannel form Red Hat
* Guardicore Centra form Guardicore
* Kube-OVN form Alauda
* Kube-router form Cloud Native Labs
* Ligato form Cisco
* Multus form Intel
* Network Service Mesh form Cloud Native Computing Foundation (CNCF)
* Nuage Networks
* Open vSwitch
* Project Calico form Tigera
* Tungsten Fabric form LF Networking
* VMware NSX form VMware
* Weave Net form Weaveworks

### 10. Service Discovery
* Apache Zookeeper form Apache Software Foundation
* CoreDNS form Cloud Native Computing Foundation (CNCF)
* etcd form Cloud Native Computing Foundation (CNCF)
* Nacos form Alibaba Cloud
* Netflix Eureka form Netflix


### 11. Orchestration & Management - Service Mesh
* Consul form HashiCorp
* Grey Matter form Decipher Technology Studios
* Istio form Google
* Kuma form Kong
* Linkerd form Cloud Native Computing Foundation (CNCF)
* Maesh form Containous
* Netflix Zuul form Netflix
* Service Mesh Interface (SMI) form Cloud Native Computing Foundation (CNCF)
* SuperGloo
* Solo.io
* Vamp.io

### 12. Provisioning - Automation & Configuration 
* Airship from OpenStack
* Ansible from Red Hat
* Apollo form Ctrip
* AWS CloudFormation form Amazon Web Services
* BOSH form Cloud Foundry Foundation
* Cadence Workflow form Uber
* CFEngine
* Chef Infra form Chef Software
* Cloudify
* Digital Rebar from RackN
* Foreman
* Juju form Canonical
* KubeEdge form Cloud Native Computing Foundation (CNCF)
* Kubicorn
* LinuxKit form Docker
* MAAS form Canonical
* ManageIQ
* OpenStack
* Pulumi
* Puppet
* Rundeck
* SaltStack
* StackStorm
* Terraform form HashiCorp
* VMware vSphere form VMware


### 13. Builds and Management

* Bitnami Stacksmith form VMware
* Buildpacks form Cloud Native Computing Foundation (CNCF)
* Chef Habitat form Chef Software
* DeployHub
* DevSpace
* Docker Compose form Docker
* Helm form Cloud Native Computing Foundation (CNCF)
* kaniko form Google
* KubeVirt form Cloud Native Computing Foundation (CNCF)
* KUDO from D2iQ
* Kui form IBM
* Lagoon form amazee.io
* Mirantis Virtlet form Mirantis
* Octant from VMware
* Okteto
* On-Prem
* Open Service Broker API
* Cloud Foundry Foundation
* OpenAPI from Open API Initiative
* Operator Framework form Red Hat
* Packer form HashiCorp
* Podman from Red HatServiceComb from Apache Software FoundationShip from Replicated
* Skaffold form Google
* Squash
* Telepresence form Cloud Native Computing Foundation (CNCF)
* Tilt from Windmill Engineering

{% include cta.html %}








