University: [ITMO University](https://itmo.ru/ru/)<br>
Faculty: [FICT](https://fict.itmo.ru)<br>
Course: [Introduction to distributed technologies](https://github.com/itmo-ict-faculty/introduction-to-distributed-technologies)<br>
Year: 2022/2023<br>
Group: K4112c<br>
Author: Nguyen Manh Trung<br>
Lab: Lab3<br>
Date of create: 26.09.2022<br>
Date of finished: 05.10.2022<br>
- Create configmap with pair `key:value`: kubectl create -f C:\Users\TrungNM\Desktop\desk\introduction\Lab\lab3\cm.yaml<br>
- Create replicaset and define the environment with value from configmap that we created before: kubectl create -f C:\Users\TrungNM\Desktop\desk\introduction\Lab\lab3\replicaset.yaml<br>
- Create service for replicaset: kubectl create -f C:\Users\TrungNM\Desktop\desk\introduction\Lab\lab3\svc.yaml<br>
- Enable ingress: kubectl create -f C:\Users\TrungNM\Desktop\desk\introduction\Lab\lab3\svc.yaml<br>
- Create secret with certificate and private key: kubectl create secret tls secret-tls --cert=cert.pem --key=key.pem<br>
- Host ini: define the host that we could access via after deploy. Here: lab3.example.com<br>
- Create ingress: kubectl create -f C:\Users\TrungNM\Desktop\desk\introduction\Lab\lab3\ingress.yaml<br>
- Run: minikube tunnel<br>
![Capture](https://user-images.githubusercontent.com/83900905/194126151-c0fdcbff-8547-4608-aee1-c768bd9c0f87.JPG)
Picture 1 - Result after deploy<br>
![Untitled Diagram drawio](https://user-images.githubusercontent.com/83900905/194373638-2115a061-d205-4efb-b634-c5d7d6460673.png)<br>
Scheme 1 - How Ingress works with TLS

