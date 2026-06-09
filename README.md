# OpenStack Private Cloud Project

## Overview

This repository contains the academic project carried out as part of the **Cloud Computing** course at the **Institut Africain d'Informatique (IAI - Gabon)** during the 2025-2026 academic year.

The project focuses on the design, deployment, administration and documentation of a **Private Cloud Infrastructure using OpenStack**. The implementation demonstrates the three main cloud service models:

* **IaaS (Infrastructure as a Service)**
* **PaaS (Platform as a Service)**
* **SaaS (Software as a Service)**

---

## Project Title

**Implementation of a Private Cloud Infrastructure Using OpenStack**

---

## Authors

Academic project developed as part of the Cloud Computing course at IAI Gabon (2025-2026).

### Institution

Institut Africain d'Informatique (IAI - Gabon)

### Academic Year

2025 - 2026

---

## Project Objectives

### General Objective

Design, deploy and document a complete private cloud infrastructure based on OpenStack.

### Specific Objectives

* Deploy OpenStack in a laboratory environment.
* Configure cloud networking using Neutron.
* Manage users, projects and quotas through Keystone.
* Deploy and manage virtual machines.
* Configure persistent storage using Cinder.
* Implement secure access using Security Groups and SSH Keys.
* Deploy a PaaS environment using Coolify.
* Deploy SaaS applications using WordPress.
* Demonstrate the integration of IaaS, PaaS and SaaS models.

---

## Cloud Architecture

The implemented architecture is based on OpenStack services and follows a multi-service cloud model.

### Main Components

| Service  | Role                           |
| -------- | ------------------------------ |
| Keystone | Identity and Access Management |
| Nova     | Compute Service                |
| Neutron  | Networking Service             |
| Glance   | Image Management               |
| Cinder   | Block Storage                  |
| Horizon  | Web Dashboard                  |
| RabbitMQ | Messaging Service              |
| MariaDB  | Database Backend               |

---

## Technologies Used

### Operating System

* Ubuntu Server 22.04 LTS

### Cloud Platform

* OpenStack (MicroStack)

### Virtualization

* KVM
* QEMU
* Libvirt

### Networking

* Open vSwitch
* Neutron

### Storage

* Cinder
* Swift

### Containers

* Docker

### PaaS

* Coolify

### SaaS

* WordPress Multisite

---

## Project Implementation

### Phase 1 - OpenStack Deployment

* System preparation
* Installation of MicroStack
* OpenStack initialization
* Horizon dashboard configuration

### Phase 2 - Administration

* User management
* Project creation
* Role assignment
* Resource quota management

### Phase 3 - IaaS Services

* Virtual network creation
* Subnet configuration
* Router deployment
* Security groups configuration
* SSH key pair creation
* Volume management
* Virtual machine deployment

### Phase 4 - PaaS Services

* Docker installation
* Coolify deployment
* Application hosting platform configuration

### Phase 5 - SaaS Services

* WordPress deployment
* MariaDB configuration
* WordPress Multisite implementation
* User website creation

---

## Demonstrated Cloud Models

### IaaS (Infrastructure as a Service)

OpenStack provides:

* Virtual Machines
* Virtual Networks
* Block Storage
* Security Policies
* Resource Management

### PaaS (Platform as a Service)

Coolify provides:

* Application deployment
* Docker container orchestration
* Database provisioning
* Environment management

### SaaS (Software as a Service)

WordPress provides:

* Web applications accessible through browsers
* Multi-user platform
* Website management services

---

## Repository Structure

```text
private-cloud-openstack/
│
├── README.md
├── documentation/
│   └── Groupe_6_Cloud.pdf
│
├── screenshots/
│
└── resources/
    └── references.md
```

---

## Key Achievements

* Successful deployment of OpenStack.
* Creation and administration of cloud projects.
* Deployment of virtual machines.
* Network isolation using Neutron.
* Storage management using Cinder.
* Deployment of Coolify as a PaaS solution.
* Deployment of WordPress as a SaaS platform.
* Complete documentation of the cloud infrastructure.

---

## Documentation

The complete project report is available in the repository documentation folder:

```text
documentation/Groupe_6_Cloud.pdf
```

---

## Learning Outcomes

This project provided practical experience in:

* Cloud Computing
* OpenStack Administration
* Virtualization Technologies
* Network Management
* Storage Management
* Docker Containers
* Platform Engineering
* System Administration
* Technical Documentation

---

## References

* OpenStack Documentation
* Ubuntu Server Documentation
* Kubernetes Documentation
* NIST Cloud Computing Definition
* OpenStack Architecture Design Guide

---

## License

This repository is published for academic and educational purposes.
