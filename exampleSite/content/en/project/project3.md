---
date: 2024-03-29T11:13:32-04:00
description: "Infrastructure Services and Operations - Alternative 2: A Storage Environment"
featured_image: "/images/openstack_infra.png"
tags: ["Project"]
title: "Project III: Infrastructure Services and Operations - Alternative 2: A Storage Environment"
---

# Infrastructure Services and Operations - Alternative 2: A Storage Environment

The project focuses on implementing infrastructure as code using configuration management tools, specifically Ansible and Terraform. The project aims to provision a storage environment efficiently while ensuring all necessary components are installed and configured correctly.

## Key Components of the Project

### 1. Workflow Management
- The team utilized a Kanban board to visually represent tasks, promoting transparency and collaboration. Tasks were organized into four sections, allowing team members to track progress and manage workloads effectively.

### 2. Project Workflow
- The project began with executing an Ansible playbook (project1 backbone.yml), which orchestrated the provisioning of six virtual machines using a Terraform manifest (main.tf). This playbook also included tasks for installing essential software packages like PHP, Apache2, and GlusterFS, as well as managing user accounts.

### 3. Technical Documentation
- The documentation was designed for junior sysadmins, assuming familiarity with Terraform and Ansible. It provided step-by-step instructions for accessing the master server and executing deployment tasks.

### 4. Execution and Testing
- The project involved multiple execution tests, with the duration of the provisioning process recorded. The first workflow test completed in 244 seconds, while subsequent tests showed slight variations in execution time (246 seconds and 257 seconds). A warning was noted regarding user group assignments for the user 'janet', which was expected based on project requirements.

### 5. Critical Reflection
- The team reflected on the advantages of using Ansible over Puppet for this project. Ansible's push-based model eliminated the need for agent certificate management, simplifying the deployment process. The average execution time for the Ansible solution was approximately 249 seconds.

### 6. Results and Conclusion
- The junior sysadmin successfully followed the technical documentation, completing the deployment in about 248 seconds. The project concluded that using Ansible for infrastructure as code is more straightforward and less time-consuming compared to Puppet, making it a preferred choice for similar future projects.

Overall, the project demonstrated effective collaboration, thorough documentation, and successful implementation of infrastructure as code principles, leading to a well-functioning storage environment.

{{< figure src="/images/openstack_infra.png" title="" >}}
