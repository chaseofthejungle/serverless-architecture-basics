# Serverless Architecture Basics
**Definition/Overview:** Infrastructure management is a unique DevOps challenge (and necessary goal) for Cloud-based enterprises. *Serverless architecture* helps make meeting that goal happen by assisting DevOps teams with resource provisioning, app testing and execution, building and deployment of apps, service automation and delivery, algorithmic cost-efficiency, and server maintenance and scalability. All of these features are provided via code functions defined by development teams, as well as the provisioning of abstract and dynamic server management controls.
  
#### Table of Contents

1. [Essential Components of Serverless DevOps Workflow](#components)
2. [Characteristics and Examples of Popular Serverless Platforms](#platforms)
3. [Challenges and Solutions](#cands)
4. [Supplemental Resources](#supplemental)
   
<hr />
  
## 1. <a name="components">Essential Components of Serverless DevOps Workflow</a>
  
* CI/CD Pipelines
* Event Sources
* Infrastructure as Code (IaC)
* Logging and Monitoring
  
<hr />
  
## 2. <a name="platforms">Characteristics and Examples of Popular Serverless Platforms</a>

**Characteristics of Serverless Platforms include:**
  
* *Event Handling:* Functions (e.g., API calls, database triggers) handle events.
* *High Scalability:* Load balancing is realized with automated scaling.
* *No Need for Server Management:* Infrastructures are abstracted from users.
* *Usage-based Billing:* Cost are connected to resources used.
  
**Examples of Popular Serverless Platforms include:**
  
* AWS Amplify Hosting, AWS Fargate, and AWS Lamba
* Google Cloud Functions
* IBM Bluemix OpenWhisk
* Microsoft Azure Functions
  
<hr />
  
## 3. <a name="cands">Challenges and Solutions</a>
  
* **Cold Start Delays**
  + If idle functions take a while to start back up after being invoked, *employ trigger schedules* and otherwise keep code optimal.
* **Monitoring**
  + Enhance visibiity of internal function mechanisms by utilizing appropriate tools (e.g., AWS X-Ray, Datadog, New Relic).
* **Security**
  + Employ granular access control mechanisms, encrypt data, and *fix permissions and event trigger misconfigurations* by using appropriate tools (e.g., AWS IAM).
* **Testing**
  + Simplify testing of local serverless functionality by using appropriate *tools/utilities* (e.g., AWS SAM CLI, LocalStack, Serverless Framework).
* **Vendor Lock-In**
  + Increase portability/compatibility of serverless platforms through code modifications and *migrating to open-source/multi-cloud alternatives*.

<hr />
  
## 4. <a name="supplemental">Supplemental Resources</a>

* *[AWS Serverless Computing](https://aws.amazon.com/serverless/)*
* *[Intro to CI/CD Pipelines Overview Guide](https://github.com/chaseofthejungle/intro-to-ci-cd-pipelines)*
* *[Serverless on Azure](https://azure.microsoft.com/en-us/solutions/serverless)*
