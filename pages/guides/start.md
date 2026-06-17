---
title: A Quick Guide to getting started with SCINet
description: A Quick Guide to getting started with SCINet
permalink: /guides/start
redirect_from: 
  - /guide/quickstart/
layout: guides
layout_type: guides

#alerts:
#  - alert:
#    title: Currently in Development
#    type: info
#    text: "If you have feedback on the organization of the User Guides sections, or notice broken links or missing images, please email us at <a href='mailto:moe.richert@usda.gov?subject=SCINet Website Feedback'>moe.richert@usda.gov.</a>"

guidegroup:
    section: subnav
#  - category: Resources
#  - getpage: /guides/access/mfa
#  - category: Access
#  - getpage: /guides/data/storage
#  - getpage: /guides/data/transfer
#  - category: Software
#  - category: Use

subnav:
  - title: What is SCINet?
    url: '#what-is-scinet'
  - title: User Guides
    url: '#user-guides'
  - title: SCINet HPC Resources
    url: /guides/resources/
    internal: true
  - title: Logging In
    url: /guides/access/
    internal: true
    shows_list: subnav
  - title: Storage Locations
    url: /guides/data/storage
    internal: true
    shows_list: subnav
  - title: File Transfer Methods
    url: /guides/data/transfer/
    internal: true
  - title: Software
    url: /guides/software/
    internal: true
    shows_list: true
    categories: [Software]
  - title: Open OnDemand Interface
    url: /guides/use/open-ondemand
    internal: true

sidenav_append:
  - title: SEARCH
    url: /search
    class: "sidenav-search"
---

[No account? Signup here.]({{ site.baseurl }}/about/signup){: .usa-button .usa-button-big }

## What is SCINet?

SCINet is USDA-ARS's initiative for scientific computing. SCINet provides:

1. High-performance computing (HPC) resources for scientific computing. SCINet currently offers all ARS researchers access to two supercomputers (also known as "HPC clusters"): "Ceres", located in Ames, IA, and "Atlas", located in Starkville, MS. SCINet also offers AWS cloud computing for certain use cases. See [SCINet HPC Systems]({{ site.baseurl }}/about/compute) for more details.
1. Network improvements across ARS to support high-speed transfer of large datasets.
1. Robust data storage and management tools.
1. Technical support for computing through the Virtual Research Support Core (VRSC). See [VRSC Support]({{ site.baseurl }}/about/vrsc) for more details.
1. Scientific computing research support through the SCINet Office that includes funding opportunities, capacity building, and consulting.
1. Training and workshop opportunities in multiple areas of scientific computing. See [our event calendar]({{ site.baseurl }}/events) for more information.

{% comment %}Users who are new to HPC might benefit from the [SCINet/Ceres onboarding video](https://www.youtube.com/watch?v=d7oKSL4aitw) which covers most of the material contained in this guide. Note that /KEEP storage discussed in the video at 16:20 is no longer available. Instead data that cannot be easily reproduced should be manually backed up to [Juno]({{ site.baseurl }}/guides/data/storage#juno-permanent-storage). The instructional video at [https://www.youtube.com/watch?v=I3lnsCAfx3Q](https://www.youtube.com/watch?v=I3lnsCAfx3Q) demonstrates how to transfer files between local computer, Ceres, Atlas and Juno using Globus.{% endcomment %}

## User Guides

**Use the navigation options or select one of the guides below to get started with SCINet.**
