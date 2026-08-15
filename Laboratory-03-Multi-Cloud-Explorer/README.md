# Laboratory 03 – Mission 3: Become a Multi-Cloud Explorer

## Mission Overview

This laboratory activity focuses on exploring and comparing three major cloud computing platforms: Amazon Web Services (AWS), Microsoft Azure, and Google Cloud Platform (GCP).

For this mission, I researched the basic features, infrastructure, management consoles, and services of each provider. I also compared their services and used different business situations to determine which cloud platform would be the most suitable.

## Objectives

The objectives of this laboratory activity are to:

* Explore AWS, Microsoft Azure, and Google Cloud.
* Identify important services offered by each provider.
* Compare the major cloud platforms.
* Match equivalent services between providers.
* Analyze different business requirements.
* Recommend a cloud provider based on a client's needs.
* Continue using GitHub to document laboratory activities.
* Relate a Linux environment to cloud virtual machine services.

## Activities Performed

During this mission, I researched AWS, Azure, and Google Cloud using their official websites and documentation. I looked at their global infrastructure, management consoles, core services, advantages, and common enterprise uses.

I also created a comparison of the three providers and matched similar services such as virtual machines, object storage, identity management, SQL databases, and Kubernetes.

For the recommendation challenge, I analyzed four different clients and selected a cloud provider based on their requirements. Finally, I used KillerCoda again to investigate a Linux environment and identified cloud services that could be used to host a similar Linux server.

## Linux Investigation

The Linux investigation was performed using the KillerCoda Playground. The operating system, CPU, memory, and disk information were collected using Linux commands.

The results of this investigation are included in this folder together with the screenshots used as evidence.

## Files in This Laboratory

* `aws-research.md` – AWS research
* `azure-research.md` – Azure research
* `gcp-research.md` – Google Cloud research
* `cloud-platform-comparison.md` – Cloud provider comparison and service matching
* `client-recommendations.md` – Client recommendations and decision matrix
* `reflection.md` – Mission reflection
* `screenshots/` – Evidence from the research and Linux investigation

## Conclusion

This laboratory helped me understand that choosing a cloud provider is not simply about choosing the most popular platform. The correct choice depends on the company's requirements, existing technologies, budget, workload, and future plans.

## Checkpoint 7 – Linux Investigation

For this checkpoint, I used the KillerCoda Ubuntu 24.04 Playground to investigate the Linux environment. I used Linux commands to check the operating system, CPU, memory, and available disk space.

### System Information

| Information          | Result                                                 |
| -------------------- | ------------------------------------------------------ |
| Operating System     | Ubuntu 24.04                                           |
| CPU                  | Intel Xeon E312xx (Sandy Bridge, IBRS update), 2.0 GHz |
| Total Memory         | 1.9 GiB                                                |
| Available Memory     | 1.4 GiB                                                |
| Disk Size            | 19G                                                    |
| Disk Used            | 5.4G                                                   |
| Available Disk Space | 13G                                                    |
| Disk Usage           | 30%                                                    |

### Linux Commands Used

```bash
grep PRETTY_NAME /etc/os-release
lscpu | grep "Model name"
free -h
df -h /
```

### Cloud Services That Could Host This Linux Server

If this Linux server were migrated to the cloud, it could be hosted using the virtual machine services of the three major cloud providers.

* **AWS – Amazon EC2:** EC2 can provide a virtual machine where a Linux operating system can run applications and services.
* **Microsoft Azure – Azure Virtual Machines:** Azure Virtual Machines can host Linux servers in the Azure cloud.
* **Google Cloud – Compute Engine:** Compute Engine can provide a virtual machine for running a Linux server and its applications.

All three options can host a Linux server, so the final choice would depend on factors such as cost, performance, available features, existing company systems, and the location of users.
