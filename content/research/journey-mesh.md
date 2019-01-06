---
docType: "talk"
title: "A journey to the mesh : microservices-based sync and share using gRPC and Protobuf"
date: 2019-01-01T00:00:00+00:00
location: "Rome, Italy"
authors: ["H.G Labrador"]
publisher: "CS3 2019"

---

CERNBox is a multipetabyte-scale sync and share platform at CERN, storing close to 7 PB of data for more than 16K users. Over time we have identified different improvement points to increase development agility and maintenance costs for running the service. Last year we have evolved the architecture of the service from a monolithic stack to a decentralised model based on micro-services. This mesh is the core of the new system and relies on latest technologies (gRPC and Protobuf) for efficient inter-component communication and controlled API evolution. In this talk we present the process we followed and our observations during this journey, which led to the creation of the public consumable CS3 APIs for a distributed sync and share platform.
