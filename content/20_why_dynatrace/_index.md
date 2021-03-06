---
title: "Why Dynatrace"
chapter: true
weight: 20
---

![image](/images/pravin.png)

Hi, Pravin here again. Now that you are up and going with easyTravel, let me take minute to share our approach to migrating to AWS and why we choose Dynatrace as strategic partner for this journey.

## AWS migration framework

At Mythical Mysfits, we have embraced the proven guidance and resources found at the [AWS Cloud Migration portal](https://aws.amazon.com/cloud-migration/). This portal provides us with the best practices, documentation, and tools that cloud architects, IT professionals, and business decision makers need to successfully achieve short-term and long-term objectives. 

The AWS migration framework presented on the AWS Cloud Migration portal frames this guidance into the [phases](https://aws.amazon.com/cloud-migration/how-to-migrate/) shown below.

<i class='fa fa-check-square'></i>
 **Assess phase** - Before we move, we need to ensure our return on investment by understanding current cost and savings. In addition, we need to validate our organization’s readiness to move to cloud from 6 different perspectives of Cloud Adoption framework- Governance, people, business, platform, security and operations.

<i class='fa fa-check-square'></i> 
**Mobilize phase** - We need to perform a detailed application and infrastructure discovery and put a plan in place. We need to identify and put in place the right tools to help iron out the challenges of portfolio analysis, right sizing, application prioritization and application grouping.

<i class='fa fa-check-square'></i>
**Migrate & modernize phases** - It is critical that we accelerate our move to the cloud and application transformations to achieve the benefits, but we must also validate our architecture decisions and our performance and scalability benchmarks.

<i class='fa fa-check-square'></i>
**Operate & optimize phase** - Once migrated, it will start to get interesting with usage of all modern services, modern architectures using Fargate, ECS, EKS, Lambda, Amazon Aurora Serverless and much more.  We know we need to adopt modern ways of operations by automating monitoring tasks, remediation tasks and ITSM tasks.  We must also continue to expand and optimize our costs and performance.

![image](/images/cloud-framework-blank.png)

## Why Dynatrace

Let me explain the ways [Dynatrace](https://www.dynatrace.com) helps us in each phase of our migration journey.

![image](/images/cloud-framework-new.png)

### #1: Understanding the Legacy Application

With Dynatrace OneAgent and Smartscape technologies, it is now fast and easy to answer these questions about the our existing applications:

&nbsp;&nbsp;&nbsp;<i class="fas fa-question-circle"></i> Which technologies are in use and where do they run?

&nbsp;&nbsp;&nbsp;<i class="fas fa-question-circle"></i> How can I aggregate multiple services to have a big picture of the legacy app?

&nbsp;&nbsp;&nbsp;<i class="fas fa-question-circle"></i> Who is responsible and needs to be included in the discussion?

&nbsp;&nbsp;&nbsp;<i class="fas fa-question-circle"></i> How can I make sense of all the Spaghetti codes in the legacy app?

Data collection is completely automated and requires no manual effort to setup in particular with the Dynatrace OneAgent that makes it super easy to capture high fidelity data across your full stack of technology.

Automatic visibility, problem detection and smart alerting across end-user traffic, services, infrastructure, network, logs and containers. 

![dt-how-works](/images/dt-agent.png)

Dynatrace automatically detects and collects a rich set of context metadata to create a real-time topology map called Smartscape. It captures the relationships and dependencies for all system components, both vertically up and down the stack and horizontally between services, processes, and hosts. Within large enterprise systems, there are billions of ever-changing dependencies, and Smartscape keeps track of them all.

The topology map enables Dynatrace to understand the actual connection between all captured metrics, traces, logs, and user experience data. Other than mere time-based correlation topology mapping reveals the actual causal dependencies between captured data. This is the basis for Dynatrace’s radically different AI engine, Davis.

![dt-capabilities](/images/dt-smartscape-words.png)

### Understanding application usage patterns

Dynatrace automatically generate a blueprint of existing infrastructure, services and the application landscape thanks to Dynatrace Smartscape Technology. Dynatrace baselines existing on-premise applications, automatically detects all dependencies (internal as well as external) and calculates current resource consumption.  

Dynatrace has out-the-box dashboards for each tier in the stack. 

![dt-how-works](/images/dt-usage-dashboard.png)

Incoming and outgoing connection to processes running monitored hosts is another view created automatically.

![dt-how-works](/images/dt-network-flow.png)

Instead of gathering this data from multiple tools, all teams can look to one source to help answer questions such as:

&nbsp;&nbsp;&nbsp;<i class="fas fa-question-circle"></i> What will it cost to run in the cloud? 

&nbsp;&nbsp;&nbsp;<i class="fas fa-question-circle"></i> What network traffic will there be between the services we migrate and those that have to stay in the current data center?

&nbsp;&nbsp;&nbsp;<i class="fas fa-question-circle"></i> How can I make sense of all the Spaghetti codes in the legacy app?

![dt-how-works](/images/dt-move-server.png)

### Making decision for the application migration strategy 

Dynatrace provides immediate feedback on decisions & transformation. By monitoring the progress of shifting workloads to the cloud, it helps us make better decisions on what to move when based on how tightly coupled services are and on the automatic baseline comparison between pre-migration and in-migration.  One feature for this is the service flow, where dependencies and usage can be analyzed. 

![dt-how-works](/images/dt-flow.png)

This automatically built view along with other views such as the Smartscape view allows for "virtual" monolith to microservice migration planning without code changes. This enables us to make smarter re-architecture and re-platforming decisions based on the existing on-premise workload and to validate other non-functional requirements such as scale, failover, costs.

![dt-how-works](/images/dt-scale.png)

### Benchmarking performance and ensuring service levels

At high level, we know we must first establish system benchmarks and then, during and post migration.  With the AI-supported baselining on the migrated services, Dynatrace allows for validating the success of the migration project from a performance, resource and cost perspective. 

![dt-how-works](/images/dt-b4-after.png)

With the build-in "hot-spot" analysis and performance analysis capabilities, Dynatrace can help pinpoint when issues show up. Here is one example where a problem has identified to be within the code execution area.  From there, one can drill into method level hot spots to see what might have changed and is impacting service levels.

![dt-how-works](/images/dt-review.png)

Migration often means moving to new technologies such as Kubernetes.  Dynatrace monitors native Kubernetes and managed Kubernetes service like AWS EKS. Dynatrace auto-discovers any environment and provides full observability without any configuration or code changes. No matter your cloud platform, container runtime or service mesh layer, Dynatrace makes monitoring applications and clusters simple. 

![dt-how-works](/images/dt-k8.png)

By providing a single view into hybrid cloud environments and support for new technologies like Kubernetes, validating business outcomes is simplified.

### Increased complexity for operations

Adopting modern architectures and cloud services means automating monitoring tasks, remediation tasks and ITSM tasks. 

Traditional observability solutions offer little information beyond dashboard visualizations. At the end, it remains to human experts to analyze the data in time-consuming war rooms. Despite all efforts, too many user complaints stay unresolved. Dynatrace is the only software intelligence platform that reliably takes that burden off human operators. Davis, the Dynatrace causation-based AI engine, automates anomaly root-cause analysis and is custom built for highly dynamic microservice environments.

Dynatrace’s purpose-built AI engine, Davis, sits at the core of Dynatrace and delivers AI-powered insights, detects problems, which are opened when Dynatrace detects anomalies with your applications (impacting end users), services (impacting service levels) or infrastructure (unhealthy system components) for hybrid cloud environments.

![dt-how-works](/images/dt-how-works.png)

&nbsp;&nbsp;&nbsp;<i class="fas fa-thumbs-up"></i> Built at the core of the Dynatrace platform Davis processes all observability data across the full technology stack, independent of origin.

&nbsp;&nbsp;&nbsp;<i class="fas fa-thumbs-up"></i> Precise technical root-cause analysis. Davis pinpoints malfunctioning components by probing billions of dependencies in milliseconds.

&nbsp;&nbsp;&nbsp;<i class="fas fa-thumbs-up"></i> Identification of bad deployments. Davis knows exactly what deployment or config change has introduced the anomaly in the first place.

&nbsp;&nbsp;&nbsp;<i class="fas fa-thumbs-up"></i> Discovery of unknown unknowns. Davis does not rely on predefined anomaly thresholds but automatically detects any unusual "change points" in the data.

&nbsp;&nbsp;&nbsp;<i class="fas fa-thumbs-up"></i> Automatic hypothesis testing by systematically working through the complete fault tree.

&nbsp;&nbsp;&nbsp;<i class="fas fa-thumbs-up"></i> No repetitive model learning or guessing. Unlike machine learning approaches, Davis’ causation-based AI relies on a topology map, which is updated in real-time.

You gain advanced observability across cloud and hybrid environments, from microservices to mainframe. Automatic full-stack instrumentation, dependency mapping and AI-assisted answers detailing the precise root-cause of anomalies, eliminating redundant manual work, and letting you focus on what matters, delivering instant answers across the full stack.

As a result, you gain advanced observability across cloud and hybrid environments, from microservices to mainframe. Automatic full-stack instrumentation, dependency mapping and AI-assisted answers detailing the precise root-cause of anomalies, eliminating redundant manual work, and letting you focus on what matters, delivering instant answers across the full stack.

![dt-problem](/images/dt-problem-view.png)

## Enabling modern operations

In order to do more with less and scale, Operations team must transcend IT silos, foster collaboration and improve productivity. Automation is key component of this, but it takes platforms that can integrate into the enterprise eco-system and delivery pipelines. Using the Dynatrace data, AI enabled problems, events, Smartscape and APIs use cases such these are achievable today:

* Eliminate the QA analysis bottleneck and deliver better software faster
* Solve problems faster with AI-driven closed loop ITSM integration
* Automate Problem Remediation

The Dynatrace Software Intelligence Platform established a smart cloud ecosystem that enables modern operations that can:

* Ingest more data to fill blind spots
* Pull in data from Cloud Platforms
* Trigger orchestration
* Integrate with your Delivery Tools
* Exchange data with your business systems

![dt-problem](/images/dt-intregration.png)

## Let’s Start!

The workshop environment with the easyTravel application using your AWS account and Dynatrace instance should now be ready, so proceed now to the [Mobilize](/30_mobilize.html) section to get started.

