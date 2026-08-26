<h1 align="center">Onkar K. Pawar</h1>

<p align="center">
  <b>Java Backend Developer</b> &nbsp;·&nbsp; Senior Executive @ IDBI Intech &nbsp;·&nbsp; Thane, India
</p>

<p align="center">
  Building secure &amp; scalable microservices with strong foundations in performance and security.
</p>

<p align="center">
  <a href="https://orov2.github.io"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-0A1F44?style=for-the-badge&logo=googlechrome&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/onkar-pawar-software-engineer/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://stackoverflow.com/users/14092691/onkar-pawar"><img alt="Stack Overflow" src="https://img.shields.io/badge/Stack_Overflow-FE7A16?style=for-the-badge&logo=stackoverflow&logoColor=white"></a>
  <a href="mailto:onkarpawar58@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"></a>
</p>

---

## About

Java Backend Developer with **4+ years** designing, developing and maintaining scalable backend
applications and microservices using **Java** and **Spring Boot**. I work on secure, high-availability
enterprise systems — improving application performance through microservices architecture and Spring
Cloud Gateway, and strengthening security via AES encryption, LDAP, and JWT-based authentication and
authorization. Comfortable across Docker, CI/CD pipelines and cross-functional Agile delivery.

> [!NOTE]
> **Most of my engineering work lives in private enterprise repositories.** The public repos on this
> profile are a learning and experimentation space — clones, course code and side projects, mostly in
> JavaScript and Python. They are not representative of what I do professionally. The sections below
> describe the enterprise work at a level I can share publicly.

---

## What I actually build

Enterprise backend platforms — described at a professional level only. No client data, credentials,
endpoints, schemas or proprietary code.

| Where | Role | Period | What I build |
| :--- | :--- | :--- | :--- |
| **IDBI Intech** | Senior Executive | Oct 2024 – Present | A secure microservices platform built from scratch: React.js frontend with LDAP login, Spring Cloud Gateway for centralised auth and call filtering, Eureka service discovery, and end-to-end AES-encrypted communication across 7+ Spring Boot services. |
| **Nexstep Infotech** *(Expenzing)* | Software Engineer | Jan 2022 – Aug 2024 | Procure-to-Pay and Travel &amp; Expense mobile applications — multi-attachment support, OCR on invoices and expense vouchers, map functionality, UI/UX upgrades, plus VAPT remediation across the stack. |
| **Tritorc** | IT Technical Engineer | May 2021 – Sept 2021 | Network and desktop infrastructure across Windows Server and Linux — Active Directory, DNS, DHCP, TCP/IP and VPN for 30+ systems. |

### Measured impact

| | | |
| :--- | :--- | :--- |
| **70%** application performance improvement | **40%** enterprise security compliance increase | **30%** code efficiency improvement |
| **7+** microservices architected &amp; deployed | **20%** reduction in repetitive coding effort | **15%** reduction in system downtime |

---

## Architecture I work with

The secure microservices platform I built at IDBI Intech, at a shareable level:

```mermaid
flowchart TD
    C["React.js client<br/>LDAP login · AES-encrypted payloads"]
    G["Spring Cloud Gateway Server<br/>centralised auth · call filtering"]
    L["LDAP directory<br/>enterprise authentication"]
    E["Eureka Server<br/>discovery · load balancing"]
    S1["Microservice<br/>Spring Boot · Java 17"]
    S2["Microservice<br/>Spring Boot · Java 17"]
    S3["Microservice<br/>7+ services deployed"]
    D[("MySQL / Oracle<br/>Hibernate · token store")]

    C -->|"AES / HTTPS"| G
    G <--> L
    G <--> E
    G -->|"JWT + DB token"| S1
    G -->|"JWT + DB token"| S2
    G -->|"JWT + DB token"| S3
    S1 --> D
    S2 --> D
    S3 --> D
```

<details>
<summary><b>How the security layers fit together</b></summary>

<br/>

| Layer | Mechanism |
| :--- | :--- |
| Client → Gateway | AES encryption with PKCS7 padding on request and response bodies |
| Authentication | LDAP directory login, handled centrally at the gateway |
| Gateway → Services | Multi-level JWT plus database-driven token authentication |
| Service → Service | End-to-end AES-encrypted data exchange |
| Discovery | Eureka for service registration, discovery and load balancing |
| Delivery | Docker images deployed through CI/CD pipelines |

Earlier, at Expenzing, I worked through VAPT findings on the mobile stack — SSL pinning, encrypted
body transmission, session handling, single-response services, multiple-login prevention, broken
authentication prevention and rooted-device blocking.

</details>

---

## Tech stack

**Languages &amp; core**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=databricks&logoColor=white)
![Design Patterns](https://img.shields.io/badge/Design_Patterns-4B5563?style=flat-square)
![SOLID](https://img.shields.io/badge/SOLID_Principles-4B5563?style=flat-square)

**Frameworks**

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Cloud Gateway](https://img.shields.io/badge/Spring_Cloud_Gateway-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-005571?style=flat-square)
![React](https://img.shields.io/badge/React.js-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)

**Security**

![AES](https://img.shields.io/badge/AES_Encryption-1B6DF0?style=flat-square&logo=letsencrypt&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![LDAP](https://img.shields.io/badge/LDAP_Auth-0A1F44?style=flat-square)
![SSL Pinning](https://img.shields.io/badge/SSL_Pinning-0A1F44?style=flat-square)

**Data &amp; servers**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)
![Tomcat](https://img.shields.io/badge/Tomcat-F8DC75?style=flat-square&logo=apachetomcat&logoColor=black)
![JBoss](https://img.shields.io/badge/JBoss-CE0000?style=flat-square&logo=redhat&logoColor=white)
![WildFly](https://img.shields.io/badge/WildFly-AD2E24?style=flat-square&logo=wildfly&logoColor=white)

**DevOps &amp; tooling**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-4B5563?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![SVN](https://img.shields.io/badge/SVN-809CC9?style=flat-square&logo=subversion&logoColor=white)

---

## Currently exploring

![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)

Happy to collaborate on **software development and Spring Boot projects**, and always glad to talk
through **software engineering and application security fundamentals**.

---

## Certifications

| Certification | Issuer | Date |
| :--- | :--- | :--- |
| Master Microservices with Spring Boot, Docker, Kubernetes | Udemy | Jun 2024 |
| Complete React Developer *(Redux, Hooks, GraphQL)* | Udemy | Nov 2023 |
| Java Design Patterns &amp; SOLID Design Principles | Udemy | Oct 2023 |
| Multiplatform Mobile App Development With React Native | Coursera | Aug 2023 |

- **Award** — *Going Beyond Call of Duty*, issued by the CEO, Expenzing (2023)
- **Education** — Bachelor of Computer Science, Bharati Vidyapeeth College of Engineering (2016 – 2020)

---

## Activity

<p align="center">
  <img alt="GitHub streak" src="https://streak-stats.demolab.com/?user=oroV2&theme=dark&hide_border=true&border_radius=8">
</p>

> [!TIP]
> The contribution graph on my profile includes private contributions, so it reflects the enterprise
> work described above rather than just the public repositories below it.

---

## Connect

[**Portfolio**](https://orov2.github.io) · [**LinkedIn**](https://www.linkedin.com/in/onkar-pawar-software-engineer/) · [**Stack Overflow**](https://stackoverflow.com/users/14092691/onkar-pawar) · [**Quora**](https://www.quora.com/profile/Onkar-Pawar-18) · [onkarpawar58@gmail.com](mailto:onkarpawar58@gmail.com)
