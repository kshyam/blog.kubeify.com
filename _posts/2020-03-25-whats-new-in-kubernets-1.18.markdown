---
layout: post
title:  What's new in Kubernetes 1.18
date:   2020-03-25 15:01:35 +0300
image:  /blog/kubernetes.gif
tags:   Kubernetes News Release
---
We’re pleased to share news about Kubernetes 1.18, this is first release of 2020! 

Kubernetes 1.18 consists of 38 enhancements 15 enhancements are moving to stable, 11 enhancements in beta, and 12 enhancements in alpha!

## 1. Kubernetes Topology Manager Moves to Beta
A beta feature of Kubernetes in release 1.18, the Topology Manager feature enables NUMA alignment of CPU and devices (such as SR-IOV VFs) that will allow your workload to run in an environment optimized for low-latency. Prior to the introduction of the Topology Manager, the CPU and Device Manager would make resource allocation decisions independent of each other. This could result in undesirable allocations on multi-socket systems, causing degraded performance on latency critical applications.

## 2. Serverside Apply Introduces Beta 2
Server-side Apply was promoted to Beta in 1.16, but is now introducing a second Beta in 1.18. This new version will track and manage changes to fields of all new Kubernetes objects, allowing you to know what changed your resources and when.

## 3. Extending Ingress and replacing a deprecated annotation with IngressClass
In Kubernetes 1.18, there are two significant additions to Ingress: A new __pathType__ field and a new __IngressClass__ resource. The pathType field allows specifying how paths should be matched. In addition to the default __ImplementationSpecific__ type, there are new Exact and Prefix path types.

The __IngressClass__ resource is used to describe a type of Ingress within a Kubernetes cluster. Ingresses can specify the class they are associated with by using a new __ingressClassName__ field on Ingresses. This new resource and field replace the deprecated __kubernetes.io/ingress.class__ annotation.

## 4. SIG-CLI introduces kubectl alpha debug
SIG-CLI was debating the need for a debug utility for quite some time already. With the development of ephemeral containers, it became more obvious how we can support developers with tooling built on top of kubectl exec. The addition of the __kubectl alpha debug__ command (it is alpha but your feedback is more than welcome), allows developers to easily debug their Pods inside the cluster. We think this addition is invaluable. This command allows one to create a temporary container which runs next to the Pod one is trying to examine, but also attaches to the console for interactive troubleshooting.

## 5. Introducing Windows CSI support alpha for Kubernetes
The alpha version of CSI Proxy for Windows is being released with Kubernetes 1.18. CSI proxy enables CSI Drivers on Windows by allowing containers in Windows to perform privileged storage operations.


## Major Changes
<ul><li><a href="https://github.com/kubernetes/enhancements/issues/752" target="_blank">EndpointSlice API</a></li><li><a href="https://github.com/kubernetes/enhancements/issues/1020" target="_blank">Moving kubectl package code to staging</a></li><li><a href="https://github.com/kubernetes/enhancements/issues/1513" target="_blank">CertificateSigningRequest API</a></li><li><a href="https://github.com/kubernetes/enhancements/issues/1539" target="_blank">Extending Hugepage Feature</a></li><li><a href="https://github.com/kubernetes/enhancements/issues/1601" target="_blank">client-go signature refactor to standardize options and context handling</a></li></ul>

EndpointSlice API
Moving kubectl package code to staging
CertificateSigningRequest API
Extending Hugepage Feature
client-go signature refactor to standardize options and context handling

## Release Notes
<p>Check out the full details of the Kubernetes 1.18 release in our <a href="https://github.com/kubernetes/kubernetes/blob/master/CHANGELOG/CHANGELOG-1.18.md" target="_blank">release notes</a>.</p>

## Availability
<p>Kubernetes 1.18 is available for download on <a href="https://github.com/kubernetes/kubernetes/releases/tag/v1.18.0" target="_blank">GitHub</a>. To get started with Kubernetes, check out these <a href="https://kubernetes.io/docs/tutorials/" target="_blank">interactive tutorials</a> or run local Kubernetes clusters using Docker container “nodes” with <a href="https://kind.sigs.k8s.io/" target="_blank">kind</a>. You can also easily install 1.18 using <a href="https://kubernetes.io/docs/setup/independent/create-cluster-kubeadm/" target="_blank">kubeadm</a>.</p>

## Release Logo
<img src="/images/blog/kubernetes-release-logo.png" width="50%">

