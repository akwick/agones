---
title: "Deploy Kubernetes cluster and install Agones using Terraform"
linkTitle: "Install with Terraform"
weight: 50
description: >
  Install a [Kubernetes](http://kubernetes.io) cluster and Agones declaratively using Terraform.
---

## Prerequisites

- [Terraform](https://www.terraform.io/) v0.12.21
- Access to the the Kubernetes hosting provider you are using (e.g. `gcloud`,
  `awscli`, or `az` utility installed)
- Git

{{% feature expiryVersion="1.10.0" %}}
{{% alert color="info" title="Note" %}}
We recently updated all our Terraform modules and examples to use
a {{% ghlink href="install/terraform/modules/helm3" %}}Helm 3 Module{{% /ghlink %}}.

If you still require the {{% ghlink href="install/terraform/modules/helm" %}}Helm 2{{% /ghlink %}} module, it is still
available, but isn't being actively maintained.
{{% /alert %}}
{{% /feature %}}

{{% feature publishVersion="1.10.0" %}}
{{% alert color="info" title="Note" %}}
All our Terraform modules and examples use a
{{% ghlink href="install/terraform/modules/helm3" %}}Helm 3 Module{{% /ghlink %}}.

The last Agones release to include a Helm 2 module was 
[1.9.0](https://agones.dev/site/blog/2020/09/29/1.9.0-kubernetes-1.16-nuget-and-tcp-udp/).
{{% /alert %}}
{{% /feature %}}
