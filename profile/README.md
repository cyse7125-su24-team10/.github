# LLaMaCVE

![LLaMA](https://img.shields.io/badge/LLaMA-3.1-blue?style=for-the-badge)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5.svg?style=for-the-badge&logo=Kubernetes&logoColor=white)
![Amazon EKS](https://img.shields.io/badge/Amazon_EKS-FF9900?style=for-the-badge&logo=amazoneks&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-Vector_DB-4B0082?style=for-the-badge)
![Jenkins](https://img.shields.io/badge/Jenkins-CI%2FCD-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-IaC-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689.svg?style=for-the-badge&logo=Helm&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200.svg?style=for-the-badge&logo=Flyway&logoColor=white)
![Kubernetes Operator](https://img.shields.io/badge/Kubernetes-Operator-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)


## How can Large Language Models (LLMs) be leveraged to meet your business needs?

This is the central question our project aims to address. Large Language Models (LLMs) have the potential to revolutionize various aspects of business operations, from customer service to data analysis and decision-making processes. Our project demonstrates a powerful approach to harness this potential: Retrieval Augmented Generation (RAG).

### Key Highlights:
- **LLaMA3.1 Integration**: We utilize the advanced llama3.1 model for superior natural language processing capabilities.
- **Self-Hosted on Kubernetes**: Our solution, along with the llama3.1 8-billion parameter model, is hosted on **Kubernetes**, providing unparalleled control, scalability, and customization options.
### Project Demo
Watch our project demonstration:

[![LLaMaCVE Demo](https://img.youtube.com/vi/WlghN6UE7YA/0.jpg)](https://www.youtube.com/watch?v=WlghN6UE7YA)

RAG combines the vast knowledge of LLMs with the ability to retrieve and incorporate specific, up-to-date information. This makes it particularly valuable for businesses that need to process and analyze large amounts of domain-specific data while leveraging the general capabilities of LLMs.

In our project, we've developed a CVE (Common Vulnerabilities and Exposures) RAG application. This application integrates llama3.1 with Pinecone vectors, which act as a knowledge base containing up-to-date CVE data. Our system is designed to provide the latest information on vulnerabilities and exposures, crucial for cybersecurity and risk management in businesses.

Key features of our application include:
- Integration of LLM with **Pinecone** vector database for efficient information retrieval
- Self-hosted solution on Kubernetes for enhanced control and customization
- Operators running hourly to ensure data freshness
- Ability to query and analyze the latest vulnerability information

Our project, built and deployed on **Amazon EKS**, showcases how this RAG application can be implemented in a robust, scalable environment. We adhere to DevOps best practices, utilizing comprehensive **CI/CD** pipelines with **Jenkins** and Infrastructure as Code **(IaC)** using **Terraform**. This ensures that our solution is not only powerful but also maintainable and adaptable to changing business needs.

We invite you to explore our work and see how self-hosted LLMs, particularly llama3.1, can be practically applied to solve real-world business challenges, especially in the realm of cybersecurity and vulnerability management. If you find our project valuable, please consider leaving a ⭐️!

## Architecture Diagram

![Architecture Diagram](https://github.com/cyse7125-su24-team10/.github/blob/main/WhatsApp%20Image%202024-08-16%20at%2020.12.01.jpeg)

## Repositories

1. [AWS Infrastructure](https://github.com/cyse7125-su24-team10/infra-aws)
2. [LLM CVE](https://github.com/cyse7125-su24-team10/llm-cve)
3. [Jenkins AMI](https://github.com/cyse7125-su24-team10/ami-jenkins)
4. [Kubernetes Operator](https://github.com/cyse7125-su24-team10/cve-operator)
5. [EKS Autoscaler](https://github.com/cyse7125-su24-team10/helm-eks-autoscaler)
6. [Jenkins Infrastructure](https://github.com/cyse7125-su24-team10/infra-jenkins)
7. [CVE Processor](https://github.com/cyse7125-su24-team10/webpp-cve-processor)
8. [CVE Consumer](https://github.com/cyse7125-su24-team10/webapp-cve-consumer)
9. [PineCone Loader](https://github.com/cyse7125-su24-team10/pinecone-loader)
10. [DB CVE Processor](https://github.com/cyse7125-su24-team10/db-cve-processor)
11. [Helm Chart: LLM CVE](https://github.com/cyse7125-su24-team10/helm-llm-cve)
12. [Helm Chart: Kubernetes Operator](https://github.com/cyse7125-su24-team10/helm-k8s-operator)
13. [Helm Chart: CVE Processor](https://github.com/cyse7125-su24-team10/helm-webapp-cve-processor)
14. [Helm Chart: CVE Consumer](https://github.com/cyse7125-su24-team10/helm-webapp-cve-consumer)

## Contributors

- [Vinay Chelpuri](https://github.com/vk-NEU7) [![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github)](https://github.com/vk-NEU7) [![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/vinaychelpuri/)

- [Siddharth Dash](https://github.com/siddharthdash1998) [![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github)](https://github.com/siddharthdash1998) [![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/dash-siddharth/)

## Mentors

- [Tejas Parikh](https://www.linkedin.com/in/tejassunilparikh/) [![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/tejassunilparikh/)

- [Abhilash Gade](https://www.linkedin.com/in/abhilashgade/) [![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/abhilashgade/)

