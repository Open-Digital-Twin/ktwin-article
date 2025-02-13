# KTWIN: A Serverless Kubernetes-based Digital Twin Platform

## What is KTWIN?

KTWIN is a Digital Twin platform built on top of Kubernetes and powered by Knative Serverless workloads. KTWIN uses Custom Resource Definitions (CRDs) to extend Digital Twin Definition Language (DTDL), providing more control and flexibility over the underlying container-based services that compose the the DT landscape and reduction of operational costs by automating manual operations.

## Repositories

- [Installation Steps](https://github.com/Open-Digital-Twin/ktwin-operator/tree/main/docs)
- [KTWIN Operator](https://github.com/Open-Digital-Twin/ktwin-operator)
- [Twin Services](https://github.com/Open-Digital-Twin/ktwin-smart-cities-services)
- [MQTT Devices](https://github.com/Open-Digital-Twin/ktwin-smart-cities-devices)
- [KTWIN Dispatchers](https://github.com/Open-Digital-Twin/ktwin-dispatchers)
- [Event Store](https://github.com/Open-Digital-Twin/ktwin-event-store)
- [Graph Cache](https://github.com/Open-Digital-Twin/ktwin-graph-cache)
- [KTWIN Smart Cities CRDs](https://github.com/Open-Digital-Twin/ktwin-smart-cities-devices)
- [Original DTDL Spec Files](https://github.com/Open-Digital-Twin/ktwin-opendigitaltwins-smartcities)

## Referencing and Citation

For academic work referencing and citation please read our [paper](https://doi.org/10.1016/j.comnet.2025.111095) "KTWIN: A serverless Kubernetes-based Digital Twin platform" published at Computer Networks, Volume 259, 2025, ISSN 1389-1286. https://doi.org/10.1016/j.comnet.2025.111095

### Abstract

Digital Twins (DTs) systems are virtual representations of physical assets allowing organizations to gain insights and improve existing processes. In practice, DTs require proper modeling, coherent development and seamless deployment along cloud and edge landscapes relying on established patterns to reduce operational costs. However, existing platforms do not allow the definition of technical application aspects that compose the deployment of a Digital Twin, such as the number of allocated CPU, memory, and auto-scaling settings. Moreover, the existing platforms are not vendor-agnostic preventing solutions from being deployed to different Cloud providers, causing the vendor lock-in problem. In this work, we propose KTWIN, a Kubernetes-based Serverless Platform for Digital Twins. KTWIN was developed using the state-of-the-art open-source Cloud Native tools, allowing DT operators to easily define models through open standards and configure details of the underlying services and infrastructure. The experiments carried out with the developed prototype show KTWIN can provide a higher level of abstraction to model and deploy a Digital Twin use case without compromising the scalability of the solution. The tests performed also show cost savings ranging between 60% and 80% compared to over-provisioned scenarios.

## Credits

- **Author:** Alexandre Gustavo Wermann - http://www.inf.ufrgs.br/~agwermann
- **Advisor:** Juliano Araujo Wickboldt - http://www.inf.ufrgs.br/~jwickboldt
