# Network Automation Foundations - Crash course
## Blueprint proposal

The purpose of this crash course is to `introduce the attendees to 101 Network Automation through a series of concepts, tools, live demos and assignments.`

Although some of the tooling will be proper of Cisco, the concepts will be vendor-agnostic.

All contents will be showcased through network automation examples.

A weekly challenge will be suggested after every session. Rewards will be given to those who complete the challenges on time.

---

Intended audience: 
- `Beginners`
- `Telecom, Data Networks, DevOps engineers/students with no previous experience with programming or automation`

---

- Intended kick-off: `April 2026`
- Amount of sessions: `4`
- Frequency: `Weekly`
- Duration of each session: `1hr 30mins`

---

## Session 1: Foundations & Data Handling
| Subtopic | Overview | Network Automation Example | Hands-on Exercise |
|---|---|---|---|
| Version control concepts | Git basics, branching, collaboration workflows | Store network configuration scripts in Git | Parse mock device configs and commit to Git |
| Data formats | JSON, XML, YAML, YANG | Represent device configs and API responses | Convert JSON/YAML configs to Python objects |
| Parsing structured data | Transform structured data into program objects | Extract interface or VLAN info from device API | Print interface summary from parsed configs |
| Design patterns awareness | Modular code, reusable functions, code quality good practices | Separate modules for device connection, config retrieval | Refactor script into reusable modules. Add docstrings, type hinting, naming conventions |

## Session 2: APIs & Network Interaction
| Subtopic | Overview | Network Automation Example | Hands-on Exercise |
|---|---|---|---|
| API concepts | What APIs are and their role in automation | Cisco DevNet sandbox device management | Explore device list via API |
| REST architecture & HTTP methods | GET, POST, PUT, PATCH, DELETE, stateless design | GET interface status, POST VLAN changes | Filter devices by status or hostname |
| API authentication | Basic auth, token-based auth, OAuth workflows | Authenticate to DevNet sandbox APIs | Connect to API using token and retrieve device info |
| API testing tools | Postman, Python `requests` | Test API requests before automating | Send GET request and parse JSON response |

## Session 3: Infrastructure & Automation – Part 1
| Subtopic | Overview | Network Automation Example | Hands-on Exercise |
|---|---|---|---|
| Infrastructure as Code (IaC) | Principles of automated infrastructure provisioning | Use IaC to deploy network topologies | Build mock device configs and deploy via Ansible |
| Configuration management | Ansible, Terraform, NSO overview | Push VLAN or interface configs to multiple devices | Create an Ansible playbook for multiple devices |
| Model-driven programmability | YANG models, abstract device configurations | Automate interface creation using YANG-based models | Define device configs using YANG structure |

## Session 4: Infrastructure & Automation – Part 2
| Subtopic | Overview | Network Automation Example | Hands-on Exercise |
|---|---|---|---|
| NETCONF / RESTCONF protocols | Model-driven device interaction protocols | Configure devices or query state using RESTCONF | Push interface config using RESTCONF |
| Telemetry concepts | Streaming telemetry, observability | Monitor interface traffic and errors | Python script to fetch telemetry stats |
| Integrating automation with monitoring | Combining config automation and monitoring | Validate configs and monitor device health | Playbook/script: push config + retrieve telemetry |

---
