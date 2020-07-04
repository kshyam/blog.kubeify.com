---
layout: post
title:  Public Cloud Characteristics
description: 
date:   2020-06-10 15:01:35 +0300
image:  /blog/public-cloud-characteristics.jpg
tags:   CloudNative Public Cloud Google GCP Amazon AWS Azure
---


Before we discuss public cloud characteristics let's first have a look at traditional data centers. 

With traditional data centers, You probably own hardware and you manage everything running on it, there's no service provider. In case of any outages you're fully responsible.

So you have to make sure that <b>high availability</b> and disaster recovery mechanisms have been implemented and are brought properly.

Lat's say you are using a public cloud like Azure cloud or AWS or Google cloud where hardware components fully owned and managed by public cloud provider. This means that you don't have to take care anymore of those hardware components and the operations as in traditional data centers.

Typically <b>scalability</b> is for some companies quite challenging because they may be don't have the knowledge and experience or they have to invest a lot of money to buy hardware.

Next to scalability <b>cost management</b> is another topic that cannot be properly measured because it's hard to calculate costs for power, cooling hardware and support among others.

Therefore it's not clear how much a business unit or a department exactly spend. 
Obvious businesses may be only allowed to spend a specific amount of money for high availability and scalability.

<center>
{% highlight ruby %}
  "There is a much better approach."
{% endhighlight %}
</center>

Cloud computing makes it very easy to figure out what's your cost.
You have built in capabilities to calculate costs to some forecasting, you can also identify how much specific server costs and same for scalability.

You can easily increase VM sizes as per you need and load to serve more traffic.

This approach works even better for other solutions based on platform as a service that scale out if demand increases and scale in if not needed anymore. Fully automated high availability is a built in feature and available for all workloads.

Basically for sure we have to make sure that your service runs high available, to do so it may be not only the underlying hardware, there must be a high available application layer.

The public cloud is a another data center where you don't have to take care of the facility or <b>physical security</b> that's covered by the cloud provider.

Since we are talking about public cloud it means that a lot of services are available from the Internet, So this is what typically a cloud provider implements by default and offers appropriate services to their customers to let them make their environment even more secure.

Therefore it's also called a resource or service provider in a cloud context.

The public cloud is a multi tenant environment, It means that the underlying resources like server hardware are consumed by you but also by other customers.

It's a shared infrastructure, For sure there are some services available that you can use as dedicated workloads. But when talking about network infrastructure or storage this is always shared.

When I say share, it means that all processes data that you use are isolated from each other to customers running workloads on the same physical machine or sending data on the same network device. 

This applies to network storage and all or consume workloads will be charged to you on a monthly basis. This is also called pay as you go or the consumption model. If you use auto scaling for some workloads then your monthly bill will be higher or lower depending on consumptions.

> Public Cloud Services Models 

<img src="/images/blog/public-cloud-services.jpg">


{% include cta.html %}
