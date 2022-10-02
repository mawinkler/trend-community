# Awesome Trend Community

<div align="center">
  <a href="https://github.com/mawinkler/trend-community/">
    <img width="400" src="images/trend-laurel-wreath.400x400.png" alt="Awesome Trend Community">
  </a>
  <br>
  <a href="https://github.com/mawinkler/trend-community/"><strong>https://github.com/mawinkler/trend-community/</strong></a>
</div>

Trend Micro offers multiple solutions helping to secure IT within different aspects of DevOps, Cloud Transition and Compliance challenges. Many of the solutions are providing the possibility to get automated by the use of APIs.

Awesome Trend Community is a curated list of awesome
[Trend Micro](https://www.trendmicro.com) Solution focused scripts, tools and other resources, mainly developed and
maintained by the power of the worldwide community of Trenders.

The list is divided into categories. The links in those categories do not have
pre-established order; the order is for contribution. If you want to contribute,
please read the [guide](https://github.com/mawinkler/trend-community/blob/master/CONTRIBUTING.md).

## Contents

- [Awesome Trend Community](#awesome-trend-community)
  - [Contents](#contents)
  - [How to use](#how-to-use)
  - [Cloud One](#cloud-one)
  - [Vision One (XDR)](#vision-one-xdr)
  - [In case you need help](#in-case-you-need-help)
    - [Create an Issue](#create-an-issue)
    - [Official Channels](#official-channels)
  - [Learning](#learning)
  - [Cloud](#cloud)
  - [Cloud One Workload Security](#cloud-one-workload-security)
  - [Cloud One Application Security](#cloud-one-application-security)
  - [Cloud One Container Security](#cloud-one-container-security)
  - [Vision One](#vision-one)
  - [References](#references)
  - [Uncategorized](#uncategorized)
  - [Contributing](#contributing)
  - [Trademark Legal Notice](#trademark-legal-notice)
  - [License](#license)

## How to use

Awesome Trend Community is a fantastic list for people trying to get the best
out of Trend Solutions.

You can navigate through the list by:

- Simply press <kbd>command/ctrl</kbd> + <kbd>F</kbd> to search for a keyword
- Go through our [_Contents list_](#contents)

## Cloud One

Trend Micro Cloud One is a security services platform for cloud builders, designed to meet your cloud security needs today, and in the future. No matter where you are in your cloud journey, Trend Micro Cloud One has you covered with the broadest and deepest solutions.  From cloud migration projects to cloud native application delivery or cloud center of excellence driven objectives, you can rely on our automated, flexible, and all-in-one security.

Cloud One currently _combines_ the following services into one solution:

- [Workload Security](https://www.trendmicro.com/en_us/business/products/hybrid-cloud/cloud-one-workload-security.html) - Runtime protection for workloads (virtual, physical, cloud, and containers).
- [Container Security](https://www.trendmicro.com/en_us/business/products/hybrid-cloud/cloud-one-container-image-security.html) - Image scanning in your build pipeline.
- [File Storage Security](https://www.trendmicro.com/en_us/business/products/hybrid-cloud/cloud-one-file-storage-security.html) - Security for cloud file and object storage services.
- [Application Security](https://www.trendmicro.com/en_us/business/products/hybrid-cloud/cloud-one-application-security.html) - Security for serverless functions, APIs, and applications.
- [Network Security](https://www.trendmicro.com/en_us/business/products/hybrid-cloud/cloud-one-network-security.html) - Cloud network layer IPS security.
- [Conformity](https://www.trendmicro.com/en_us/business/products/hybrid-cloud/cloud-one-conformity.html) - Cloud security and compliance posture management.
- [Open Source Security by Snyk](https://www.trendmicro.com/en_us/business/products/hybrid-cloud/cloud-one-open-source-security-by-snyk.html) - Visibility and monitoring of open source vulnerabilities for SecOps.

## Vision One (XDR)

The Trend Micro Vision One platform includes advanced XDR capabilities that collect and correlate deep activity data across multiple vectors – email, endpoints, servers, cloud workloads, and networks - enabling a level of detection and investigation that is difficult or impossible to achieve with SIEM, EDR, or other individual point solutions.

With a combined context, events that seem benign on their own suddenly become meaningful indicators of compromise, and you can quickly contain the impact, minimizing the severity and scope.

- [Vision One (XDR)](https://www.trendmicro.com/en_us/business/products/detection-response/xdr.html) - Extended detection and response

## In case you need help

_There are various ways to get in touch with the Trend community.
It doesn't matter if you have a question, need help, want to request a feature,
or just say ‘Hi’._

### Create an Issue

To create an issue click [here](https://github.com/mawinkler/trend-community/issues/new).

### Official Channels

- [Trend Micro](https://www.trendmicro.com/) - Trend Micro's official web site.
- [GitHub Trend Micro](https://github.com/trendmicro/) - Official GitHub by Trend Micro.
- [GitHub Trend Micro Deep Security](https://github.com/deep-security/) - Official GitHub for Deep-Security driven by Trend Micro.

## Learning

_Environments for learning, self-study and demoing._

- [C1-Playground](https://github.com/mawinkler/c1-playground) - Ultra fast and slim kubernetes playground with Cloud One integrations (plus some goodies). Does create a local cluster but can also be used on EKS, AKS & GKE. Designed to be a great learning, testing and demo environment.
- [API-Collector](https://github.com/mawinkler/api-collector) - Generic API-Collector implemented as a Custom Collector for Prometheus with Grafana. It supports pluggable collectors using code injection and updates at runtime! It's a good template for the use of different APIs. Integrated Solutions: WS, CS, AS, FSS, DSSC.

## Cloud

_Simplify your life in the clouds._

- [Multi Cloud Shell](https://github.com/mawinkler/mcs) - My way to go for dealing with AWS, Azure and GCP simultaneuosly. Provides a containerized working environment with persistence and ssh access. Start the container on any host and ssh into it.

## Cloud One Workload Security

_Integrations developed with Orchestration Solutions._

- [Ansible Playbooks](https://github.com/mawinkler/c1-ws-ansible) - Demo Ansible playbooks for C1WS.
- [Terraform Deploy Agents](https://github.com/mawinkler/c1-ws-terraform) - Deploy C1WS agents on Azure or AWS with Terraform.
- [Custom Fact for Agents](https://github.com/mawinkler/c1-ws-facter-ansible) - Custom facts for C1WS Agents for Ansible.

_Dealing with Vulnerabilities and Virtual Patching._

- [Vulnerability Management](https://github.com/mawinkler/c1-ws-vulnerability-management) - Various scripts to help with vulnerabilities. Proof of concepts for vulnerability scanner integrations for Workload Securty, IPS rule assignments and Smart Check reporting.
- [DS-Powershell](https://github.com/taralatech/DS-Powershell) - Powershell Scripts to report on and administer Deep Security Managers.

_Reporting and Event Management._

- [AM & IPS Reports](https://github.com/mawinkler/c1-ws-reporting) - Reporting of AM events in C1WS, assigned IPS roles and rule inventory.
- [Host Protection Report](https://github.com/mawinkler/ds-host-protection-report) - Custom host protection module reporter for DSM.
- [Event Digger](https://github.com/mawinkler/event-digger) - Example REACT app to quickly search through C1WS events. Uses an Elasticserch engine to get instant results.

_Policy Management._

- [Anti Malware Scan Configuration Manager](https://github.com/mawinkler/c1-ws-am-policymgr) - Anti Malware Scan Configuration Manager.

## Cloud One Application Security

_Demo applications showing the simplicity and value of adding Application Security to your apps._

- [Serverless App](https://github.com/JustinDPerkins/vulnerable-serverless-application-python) - Sample vulnerable AWS serverless application in Python.
- [Azure Function](https://github.com/mawinkler/c1-app-sec-azure-function) - This is a sample, vulnerable-on-purpose, Azure Function.
- [Djangonv](https://github.com/mawinkler/c1-app-sec-djangonv) - This is a sample, vulnerable-on-purpose, Django application in Python.
- [dotNET](https://github.com/mawinkler/c1-app-sec-dotnet) - This is a sample integration with dotNET.
- [dotNET-Vulnerable](https://github.com/mawinkler/c1-app-sec-dotnet-vulnerable) - This is a sample, vulnerable-on-purpose, dotNET application.
- [Java Goof](https://github.com/andresark/java-goof-trend) - Intentionally vulnerable containerized Java/Maven To-Do List app, forked from [Snyk's Goof app](https://github.com/snyk-labs/java-goof).
- [AWS Lambda](https://github.com/mawinkler/c1-app-sec-insekurestore) - This is a sample, vulnerable-on-purpose, Lambda driven web application.
- [log4shell-vulnerable-app-c1as](https://github.com/andresark/log4shell-vulnerable-app-c1as) - Intentionally vulnerable app to demonstrate protections against [log4shell](https://success.trendmicro.com/solution/000289940).
- [MoneyX](https://github.com/mawinkler/c1-app-sec-moneyx) - This is a sample, vulnerable-on-purpose, Java application.
- [Node Express](https://github.com/mawinkler/c1-app-sec-node-express) - This is a sample, vulnerable-on-purpose, Node Express app.
- [Petclinic](https://github.com/mawinkler/c1-app-sec-spring-petclinic) - This is a sample integration with Java Spring.
- [Tomcat](https://github.com/mawinkler/c1-app-sec-tomcat) - This is a sample, vulnerable-on-purpose, Tomcat application.
- [Uploader](https://github.com/mawinkler/c1-app-sec-uploader) - This is a sample, vulnerable-on-purpose, Apache PHP application.

## Cloud One Container Security

_Various tools and integrations for Container Security._

- [Event Query](https://github.com/mawinkler/c1-cs-event-query) - Query evaluation events from C1CS to tune your policy easily.
- [Smart Check Scan Queue Cleaner](https://github.com/mawinkler/c1-cs-clean-queue) - Cleans pending scan tasks from Smart Check. Works well even with a high number of pending tasks.
- [Smart Check on OpenShift](https://github.com/mawinkler/c1-cs-smartcheck-on-openshift) - How to get Smart Check up and running on OpenShift clusters (not finetuned).
- [Smart Check Scan-Report](https://github.com/mawinkler/c1-cs-scan-report) - Create scan report as PDF.
- [Slack Dispatcher](https://github.com/mawinkler/c1-cs-smartcheck-slack-dispatcher) - Dispatch Smart Check webhook events to Slack.
- [Export Scan Results](https://github.com/cvdabbeele/smartCheckSecurityPosture) - Export critical scan findings from Smart Check to csv file.
- [Vulnerability Remediation](https://github.com/mpkondrashin/vulrem) - Auto tune Deep/Workload Security policy according to Smart Check findings.

## Vision One

_Using Vision One like a Pro._

- [Search Queries by examples](https://github.com/girdav01/TMHunting/blob/main/hunting-recipies.md) - Trend Micro XDR/Vision One Hunting Recipes.
- [Detection Model Counter](https://github.com/OmarEzzat145/V1-Model-Counter) - Trend Micro Vision One Detection Model Counter.

## References

_Links to API documentations._

- [Workload Security API](https://cloudone.trendmicro.com/docs/workload-security/api-reference/) - RESTful API of Workload Security.
- [File Storage Security API](https://cloudone.trendmicro.com/docs/file-storage-security/api-reference/) - RESTful API of File Storage Security.
- [Conformity API](https://cloudone.trendmicro.com/docs/conformity/api-reference/) - RESTful API of Conformity.
- [Container Security API](https://cloudone.trendmicro.com/docs/container-security/api-reference/) - RESTful API of Container Security.
- [Smart Check API](https://deep-security.github.io/smartcheck-docs/api/index.html) - Deep Security Smart Check API documentation.
- [Application Security API](https://cloudone.trendmicro.com/docs/application-security/api-reference/) - RESTful API of Application Security.
- [Network Security API](https://cloudone.trendmicro.com/docs/network-security/api-reference/) - RESTful API of Network Security.
- [Automation Landing Page](https://automation.deepsecurity.trendmicro.com/) - Automate and Integrate using the Deep Security API.

## Uncategorized

_Valuable links, that don't fit in any of the above categories (yet!)._

- [YAML Specification](https://yaml.org/spec/1.2/spec.html) - YAML Ain’t Markup Language (YAML™) Version 1.2.
- [JSON Specification](https://www.ecma-international.org/publications-and-standards/standards/ecma-404/) - The JSON data interchange syntax, 2nd edition.

## Contributing

This awesome list is an active open-source project and is always open to
people who want to contribute to it. We have set up a separate document
containing our [Contribution Guidelines](https://github.com/mawinkler/trend-community/blob/master/CONTRIBUTING.md).

Contributing is pretty easy, all you need is an GitHub account.

[Just click this link to edit the list, right from your browser](https://github.com/mawinkler/trend-community/edit/master/README.md)

For a full list of all authors and contributors, check the
[contributor's page](https://github.com/mawinkler/trend-community/graphs/contributors).

Thank you for being involved! 😍

## Trademark Legal Notice

This Awesome list is not created, developed, affiliated, supported, maintained or endorsed by the Trend Micro organization.

All product names, logos, brands, trademarks and registered trademarks are property of their respective owners. All company, product, and service names used in this list are for identification purposes only.

Use of these names, logos, trademarks, and brands does not imply endorsement.

## License

Distributed under the Creative Commons Legal Code license.
See [LICENSE](https://github.com/mawinkler/trend-community/blob/master/LICENSE.md) for
the complete license.
