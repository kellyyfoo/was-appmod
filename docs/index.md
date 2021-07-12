# <h1 style="color:green">WebSphere Application Modernization Workshop </h1>

This material is designed to be a single point of access for the Demo/Lab assets for WebSphere Application Modernization. 

**Last updated:** July 2021

![banner](./images/demo-assets.png)


Application modernization is a journey of moving existing applications to a more modern cloud-native infrastructure.

There are several approaches to application modernization and provided are key reference implementations to help you on your modernization journey.

### <h3 style="color:green">Operational Modernization</h3>

- **Repackage** the application to deploy within a container but maintaining a monolith application without changes to the application or runtime. This solution uses Appsody Operator, supported by IBM Cloud Pak for Applications, to deploy and manage the containerized application on Red Hat OpenShift.

### <h3 style="color:green">Runtime Modernization</h3>


- **Update the application runtime to Open Liberty**, a suitable cloud-native framework. Modernize some aspects of the application by taking advantage of MicroProfile specifications, such as Health, Metrics, JWT, Config and OpenAPI. This solution uses Open Liberty Operator, also supported by IBM Cloud Pak for Applications, to deploy and manage the modernized application on Red Hat OpenShift.


### <h3 style="color:green">Application Management</h3>
- **Monitor the applications** easily using various dashboards available as part of IBM Cloud Pak for Applications. Identify potential problems using logging dashboards. Get insights into the performance of your applications using metrics dashboards. Perform Day-2 operations, such as gathering traces and dumps, to debug potential issues easily using Open Liberty Operator. 


### <h3 style="color:green">Devops Management</h3>
- **Continuous Integration and Countinuous Deployment (CI/CD)** of applications is critical for repeatable and reliable deployments. Modern devops technologies such as Tekton and Argo CD are designed for Kubernetes (OSCP) and provide the CI/CD capabilites, and fully integrated and supported in OSCP vis Kuberntes Operators.  


# <h1 style="color:green">Hands-on Workshop</h1>


#### <h4 style="color:green">Reserve lab environments</h4>


Please follow the [setup instructions](common/setup.md) to reserver a lab environemnt, or schedule a workshop. The lab environemtn is configured with the tools you need to be able to complete the labs.


### <h3 style="color:green">Basic Labs</h3>

Basic knowledge about containers and Kubernetes is recommended. Completing the following hands-on labs will help you to easily navigate this workshop:

- Lab 1: [Introduction to Containerization](./basic-labs/HelloContainer/README.md)
- Lab 2: [Introduction to Container Orchestration using OpenShift](./basic-labs/IntroOpenshift/README.md)


### <h3 style="color:green">Appplication Modernization Labs</h3>

The labs should be completed in the order they are listed below. A link is provided at the end of each lab to the next lab.

- Lab 3: [Operational Modernization](./appmod-labs/OperationalModernization/README.md)
- Lab 4: [Runtime Modernization](./appmod-labs/RuntimeModernization/README.md)
- Lab 5: [Application Management](./appmod-labs/ApplicationManagement/README.md)
- Lab 6: [Devops Modernization](./appmod-labs/DevopsModernization/README.md)


