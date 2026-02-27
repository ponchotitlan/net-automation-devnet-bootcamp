# CCNAAUTO 200-901 — Automating Networks Using Cisco Platforms  
## DevNet Resource Mapping (Official Blueprint Aligned)

This repository maps **official CCNAAUTO (200-901)** exam objectives to **hands-on Cisco DevNet resources**:

- Learning Labs
- Sandboxes
- Code Exchange repositories

The structure follows the **official Cisco exam blueprint domains**.

---

### 1. Software Development and Design (15%)

| Subtopic | Blueprint Overview | Resource Type | Resource | Link |
|---|---|---|---|---|
| Software development methodologies | Compare waterfall vs agile development approaches | Learning Module | Programming Fundamentals | TBD |
| Version control concepts | Describe version control and collaboration workflows | Learning Lab | Git Fundamentals | Not working! https://developer.cisco.com/learning/modules/git-intro |
| Git operations | Clone, commit, push, pull concepts | Learning Lab | Git Hands-on Labs | Not working! https://developer.cisco.com/learning/modules/git-intro |
| Data formats | Compare JSON, XML, YAML | Learning Module | Data Formats Overview | TBD |
| Parsing structured data | Interpret structured data into program objects | Learning Lab | Python Parsing JSON | TBD |
| Design patterns awareness | Recognize modular software design principles | Learning Track | DevNet Associate Track | TBD |

---

### 2. Understanding and Using APIs (20%)

| Subtopic | Blueprint Overview | Resource Type | Resource | Link |
|---|---|---|---|---|
| API concepts | Describe APIs and their role in automation | Learning Module | Intro to APIs | https://developer.cisco.com/learning/modules/dntd-intro-python-and-api/ |
| REST architecture | Explain REST constraints and communication model | Learning Lab | REST API Fundamentals | https://developer.cisco.com/learning/modules/dntd-intro-python-and-api/ |
| HTTP methods | Interpret GET, POST, PUT, PATCH, DELETE | Learning Lab | REST Methods Practice | https://developer.cisco.com/learning/modules/dntd-intro-python-and-api/ |
| API authentication | Recognize API authentication mechanisms | Learning Module | API Authentication Basics | https://developer.cisco.com/learning/modules/dntd-intro-python-and-api/ |
| Tokens & OAuth | Describe token-based authentication workflows | Learning Lab | OAuth Concepts | TBD |
| API troubleshooting | Interpret HTTP status codes and responses | Learning Lab | API Troubleshooting | https://developer.cisco.com/learning/modules/dntd-intro-python-and-api/ |
| API testing tools | Use tools to send API requests | Learning Lab | Same source but using cURL and Postman instead of python | https://developer.cisco.com/learning/labs/dnac-advanced-0-orientation/introduction/ |

---

### 3. Cisco Platforms and Development (15%)

| Subtopic | Blueprint Overview | Resource Type | Resource | Link |
|---|---|---|---|---|
| Cisco DNA Center APIs | Describe controller-based programmability | Learning Lab | DNA Center APIs | https://developer.cisco.com/learning/labs/dnac-advanced-0-orientation/introduction/ |
| Meraki APIs | Recognize cloud-managed network APIs | Learning Lab | Meraki Dashboard API | https://developer.cisco.com/meraki/api-v1/ - https://developer.cisco.com/learning/labs/meraki-callbacks-learning-lab/objectives/ |
| Webex APIs | Describe collaboration platform automation | Learning Lab | Webex for Developers | Request Sandbox - https://developer.webex.com/admin/docs/developer-sandbox-guide |
| IOS XE programmability | Identify programmable device interfaces | Sandbox | IOS XE Always-On | https://devnetsandbox.cisco.com/ + IOS XE on Cat8kv |

---

### 4. Application Deployment and Security (15%)

| Subtopic | Blueprint Overview | Resource Type | Resource | Link |
|---|---|---|---|---|
| Application deployment models | Compare cloud vs on-prem deployment | Learning Module | Cloud Fundamentals | TBD |
| Containers | Describe container concepts and benefits | Learning Lab | Docker Fundamentals | TBD |
| CI/CD concepts | Recognize continuous integration and deployment workflows | Learning Module | CI/CD Overview | https://github.com/ponchotitlan/month-of-smart-connections-lab/tree/main/week-02-automation-patterns |
| Application security | Identify secure coding and API security practices | Learning Module | Security Fundamentals | https://developer.cisco.com/learning/tracks/devnet-express-security/ - Not working |
| Secrets handling | Recognize credential protection mechanisms | Learning Lab | Secure API Usage | TBD |

---

### 5. Infrastructure and Automation (20%)

| Subtopic | Blueprint Overview | Resource Type | Resource | Link |
|---|---|---|---|---|
| Infrastructure as Code | Describe automated infrastructure provisioning | Learning Module | Network Automation Basics | https://github.com/ponchotitlan/network_automation_journey_101 |
| Configuration management | Recognize automation tools (Ansible) | Learning Module | Ansible for IOS XE | https://developer.cisco.com/learning/modules/ansible-iosxe/ |
| Model-driven programmability | Describe YANG-based configuration | Learning Lab | NETCONF Introduction | https://github.com/ponchotitlan/network_automation_journey_101 |
| NETCONF / RESTCONF | Identify model-driven protocols | Sandbox | IOS XE Programmability | https://github.com/ponchotitlan/network_automation_journey_101 |
| Telemetry concepts | Describe streaming telemetry | Code Repository | IOS XE MDT Repo | https://developer.cisco.com/codeexchange/github/repo/jeremycohoe/cisco-ios-xe-mdt/ |

---

### 6. Network Fundamentals (15%)

| Subtopic | Blueprint Overview | Resource Type | Resource | Link |
|---|---|---|---|---|
| Networking basics for developers | Describe IP networking fundamentals | Learning Module | Networking Basics | https://developer.cisco.com/learning/modules/networking-basics |
| HTTP networking | Explain HTTP request/response model | Learning Lab | REST API Fundamentals | https://developer.cisco.com/learning/modules/rest-api-fundamentals |
| DNS concepts | Recognize DNS operation | Learning Module | Internet Fundamentals | https://developer.cisco.com/learning/modules/networking-basics |
| TCP vs UDP | Compare transport protocols | Learning Module | Networking Basics | https://developer.cisco.com/learning/modules/networking-basics |
| Troubleshooting connectivity | Interpret connectivity testing tools | Sandbox | IOS XE Sandbox | https://developer.cisco.com/iosxe/ |

---

# Alternative roadmaps
## Network Automation 101
Repository - https://github.com/ponchotitlan/network_automation_journey_101

- Python scripting for CLI with `netmiko`
- YANG Modelling Language
- NETCONF protocol and Python scripting for NETCONF with `ncclient`
- RESTCONF protocol and Python scripting for RESTCONF with `requests` + cURL + Postman (Pending)
- gNMI protocol and Python scripting for gNMI with `pygnmi` and open-source YANG models with OpenConfig (Pending)

## Cisco pyATS framework
Repository - https://github.com/ponchotitlan/network_automation_journey_101

- pyATS 101
- Genie parsers
- Config diffs
- Testing

## NetDevOps 101
Repository - https://github.com/ponchotitlan/nso_loves_netdevops

- Pipeline design for NetDevOps
- Network simulation using CML and ContainerD
- Testing with Robot Framework
- GitHub Actions
