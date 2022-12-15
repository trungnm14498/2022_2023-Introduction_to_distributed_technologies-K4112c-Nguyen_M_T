# 2022_2023-Introduction_to_distributed_technologies-K4112c-Nguyen_M_T

Exam question:

## 1. Что такое kubernetes? Архитектура, работа служебных сервисов, методы организации развертывания контейнеров.

- What is kubernetes? Architecture, work of utility services, methods of organizing the deployment of containers.

  **_Answer:_**

Kubernetes, or k8s, is an open source platform that automates the management, scaling, and deployment of containerized applications known as the Container orchestration engine.
![Alt text](https://topdev.vn/blog/wp-content/uploads/2019/05/Kubernetes-Architecture.png)
Kubernetes follows a client-server architecture. It’s possible to have a multi-master setup (for high availability), but by default there is a single master server which acts as a controlling node and point of contact. The master server consists of various components including a kube-apiserver, an etcd storage, a kube-controller-manager, a cloud-controller-manager, a kube-scheduler, and a DNS server for Kubernetes services. Node components include kubelet and kube-proxy on top of Docker.

Kubernetes can solve the following problems:

- The docker host batch management
- Container Scheduling
- Rolling update
- Scaling/Auto Scaling
- Monitor the life and death status of the container.
- Self-hearing in case something goes wrong. (Ability to detect and correct errors)
- Service discovery
- Load balancing
- Data management, work nodes, logs
- Infrastructure as Code
- Linkage and extension with other systems

## 2. Оссновные недостатки блокчейн-сетей на примерах различных платформ

- Common types of vulnerabilities and attacks on blockchain networks.

**_Answer:_**

• The main disadvantage of the Blockchain is the high energy consumption: The signature verification is the challenge of the Blockchain, because each transaction must be signed with cryptographic scheme, the big computing power is necessary for the calculation process to the sign. It is the one of the reasons to the high energy consumption.

• The next problem of the Blockchain is the opportunity to split the chain. The nodes, which are operating to the old software, won’t accept the transactions in the new chain. This chain is creating with the same history as the chain, which is based on the old software. It is named the fork. There are two fork’s kinds – the soft fork and the hard fork.

• Another problem of the Blockchain is the balance between the nodes’ quantity and the favorable costs for users. Now there are the nodes are lacked for the Blockchain correctly and powerful work. In this case, the costs are higher, because the nodes received higher rewards; but the transactions completed more slowly, because the nodes do not work intensive.

• The high costs are a big disadvantage of the Blockchain. The average cost of the transaction is between 75 and 160 dollars and most of it covers by the energy consumption . One of the reasons of this situation has been described above. The second reason is the high initial capital costs of the Blockchain.
