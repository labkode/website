---
docType: "talk"
title: "Testing data and metadata backends with ClawIO"
date: 2016-01-01T00:00:00+00:00
location: "Zürich, Switzerland"
authors: ["H.G Labrador"]
publisher: "CS3: Cloud Storage Services for Novel Applications and Workflows"
links:
  - type : "pdf"
    href: "https://zenodo.org/record/44783#.VxaJypN95sM"
    type: "video"
    href: "https://www.video.ethz.ch/events/2016/cs3/day1/07b554d8-d188-451a-a95d-f0de938aa8b0.html?autoplay=true"
---

Open Source Cloud Sync and Share software provides synchronisation layer on top of a variety of backend storages such as local filesystems and object storage. In case of some software stacks, such as ownCloud, a SQL database is used to support the synchronisation requirements.
We tested how different technology stacks impact the ownCloud HTTP-based Synchronisation Protocol. Efficiency and scalability analysis was performed based on benchmarking results. The results have been produced using the ClawIO framework prototype.

ClawIO  is a Cloud Synchronisation Benchmarking Framework. The software provides a base
architecture to stress different storage solutions against different cloud synchronisation protocols.
Such architecture is based on the IETF Storage Sync draft specification and CERN EOS.
The synchronisation logic is divided into control and data servers. 
This separation is done by the use of highly-decoupled micro services connected to each other using high performance communication protocols such a gRPC and HTTP/2. 
