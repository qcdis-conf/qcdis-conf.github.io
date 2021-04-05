## Adaptive infrastructure provisioning

The Co-located and Orchestrated Network Fabric (CONF) component of ARTICONF provides a suite of micro-services that collectively perform the provisioning, monitoring and adaptation of customized virtual infrastructures for federated time and trust critical social media applications. It seamlessly integrates with the cloud edge infrastructure, able to intelligently provision services based on abstract application service requirements, operational conditions at infrastructure level, and time-critical event triggering. Henceforth, we describe the research work related to the concepts and methods of CONF components in the ARTICONF project, as well as the corresponding major opportunities and challenges.

![CONF's architecture](https://raw.githubusercontent.com/qcdis-conf/qcdis-conf.github.io/main/images/conf%20architecture.png "CONF's architecture")


[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/TzsIa5W5nlo/0.jpg)](https://www.youtube.com/watch?v=TzsIa5W5nlo)




### Infrastructure planning
Deploying the same tasks on different types of infrastructure provided by cloud providers can leads to different results; in general, better virtual infrastructures can lead to better performance, but often at a higher cost. Therefore, planning for cloud infrastructure is important, and an infrastructure planner for the Cloud should plan an optimal infrastructure strategy that not only meets the QoS requirements of the application, but also achieves additional objectives such as minimizing monetary cost or power consumption. For this reason, cloud infrastructure planning for time critical applications is often more challenging than scheduling application workflows onto fixed infrastructure. 

CONF tries to plan infrastructures based on social media application requirements and adapt it swiftly in response to changing conditions, ensuring a sustained high QoS and continued satisfaction of requirements. So, the expected output of this section is to develop mechanisms for optimized planning virtual infrastructures for social media applications developed Cloud edge-based environments through the following actions: 1) develop algorithms for planning (federated) virtual infrastructure for a given social media application based on constraints on security, performance, locality and budget, 2) develop an automated planning engine which able to deploy social media applications on a federated Cloud infrastructure efficiently (over multiple cloud provider if necessary), and 3) provide a secure API for the other services to invoke and query the infrastructure planning engine. 


### Provisioning Infrastructure over distributed providers
Most current IaaS (Infrastructure-as-a-Service) clouds provide dedicated virtual infrastructure resources to cloud applications with only limited programmability and controllability, which enlarges the management gap between infrastructures and applications. 

CONF wants to provide different services and resources based on performance and reliability, taking into account locality of data sources to minimize data transfer and delays, while ensuring a smooth operation of the highly distributed application. So, the expected output of this section is to develop a smart agent for optimized provisioning virtual infrastructures for social media applications from the following aspects: 1) design strategies for provisioning (federated) virtual infrastructure for a given social media application based on multi-constraints on security, performance, locality and budget. 2) develop an automated provisioning engine able to deploy social media applications on a federated Cloud infrastructure (over multiple cloud provider if necessary). 3) provide a secure API for the other services to invoke and query the infrastructure provisioning engine.

### Time critical software deployment

Time critical software, as a kind of software with strict time constraints, refers to the applications that must return results for time-sensitive events in time and respond immediately to changes in their operating environment

Given a distributed multi-site social media infrastructure, CONF needs to ensure efficient deployment of application services on resources close to the active infrastructure, specifically to ensure fast recovery in the presence of faults or performance drops. So, the expected output of this section is to develop mechanisms for optimized software deployment for social media applications. More specifically, CONF needs to: 1) develop an automated deployment engine which able to deploy social media applications on a federated Cloud infrastructure (over multiple cloud provider if necessary) and  2) test and validate the developed services using pilot use-cases from four domains: crowd journalism with news verification, car sharing, crowd-collaborative video creation, and smart energy.


### Infrastructure monitoring, diagnosing and adaptation
Due to the dynamic nature of the cloud, continuous monitoring on Quality of Service (QoS) attributes is necessary to optimize cloud infrastructure operation

The infrastructure provisioned by CONF monitors its own state, taking timely adaptation responses to failures, performance losses or other trigger conditions. The expected output of this section is develop the monitoring services need by CONF, allowing systematic collection of information about the runtime status of the deployed social media applications and of their underlying infrastructure and network. More specifically, we need to: 1) provide an API for application integration and monitoring of key quality attributes, 2) develop tools for monitoring the runtime state of the virtual infrastructure hosting an application, and 3) deploy a monitoring database service alongside applications with full SMART integration. For the adaptation part, CONF needs to autonomously adjust the infrastructure in response to threats identified by the monitoring framework. The expected output includes: 1) research of performance models for time and trust-critical federated social media applications, 2) development of a control model for adapting the virtual infrastructure based on the interplay between the requirements and the metrics provided via monitoring, and 3) provision of an agent-based service for autonomous adaptation of the CONF-deployed infrastructure.


