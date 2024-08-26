---
date:   2019-05-21 12:15:05 +0000
heading: A Standard Interface for Service Meshes
title: A Standard Interface for Service Meshes
author_contributor: Lee Calcote
categories:
  - specification
  - multi-mesh
# layout: post
featured-image: /assets/images/posts/2019-05-21-a-standard-interface-for-service-meshes/smi-logo.png
# permalink: /blog/a-standard-interface-for-service-meshes
---
<div class="row" style="width:220px;float:right;padding:20px;text-align:center;">
<a href="https://smi-spec.io" rel="nofollow"></a><img src="{{site.baseurl}}/assets/images/posts/2019-05-21-a-standard-interface-for-service-meshes/smi-logo.png" alt="" width="70%">
</div>Most began their cloud native journey with their first step being use of containers, and taking a second step, moved into container orchestration as their workloads grew. Now, waves and waves of organizations are considering service meshes as their third significant step in their cloud native journey. As they invest into service meshes as their next layer of key infrastructure, users will continue to look for the same assurances sought from other commonly accepted (standard) interfaces for container runtimes (e.g. CRI), container storage (e.g. CSI), container networking (e.g. CNI) and they will look for a commonly accepted service mesh interface.

As a prominent supporter of management software for multiple service meshes, KhulnaSoft is pleased to partner with Microsoft in support of the [Service Mesh Interface](https://smi-spec.io) (SMI). The Service Mesh Interface is a specification for service meshes that run on Kubernetes. As such, SMI defines a common standard that can be implemented by a variety of service mesh projects and vendors.

Like standards before SMI, consistent APIs inspire confidence in infrastructure stability, community-managed APIs assuage technology and vendor lock-in concerns, and steward the resounding of core use cases, resulting in streamlining the smaller, but critical-to-users, subset of capabilities offered across the [service mesh landscape](https://khulnasoft.com/landscape). 

Meshplay and SMI are aligned on common goals of getting users started quickly, understanding that users want service mesh technology, but have questions as to which service mesh use, how, and when to get started through a common interface. Meshplay’s playground capabilities quick provision a variety of service meshes and reduce time to value and time to understanding for those adopting a service mesh.

As a cloud native manager, Meshplay, understands that each service mesh has it own strengths. SMI intends to allow for differentiation by service mesh providers, at the same time providing interoperability between service meshes and their surrounding tooling. As a management plane, Meshplay enhances networking intelligence in a multi-mesh way, encouraging users to expect more from their infrastructure. Meshplay exposes each service mesh’s differentiated capabilities. 

SMI’s aim for consistent APIs facilitates Meshplay’s same goals, allowing for users and tools to flourish. As SMI unveils today, so does Meshplay’s compatibility. Try out [Meshplay and SMI](https://khulnasoft.com/meshplay) today!
