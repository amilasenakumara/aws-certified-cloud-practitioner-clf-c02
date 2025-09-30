# ☁️ AWS Certified Cloud Practitioner (CLF-C02) Notes

## 🌐 Types of Cloud Computing

AWS provides different types of cloud computing models:

### 1. **Infrastructure as a Service (IaaS)**
- Provides **raw building blocks**:  
  - Networking  
  - Virtual servers (compute)  
  - Storage  
- High flexibility, similar to building with **LEGOs**.  
- Ideal for migrating from traditional on-premises IT to the cloud.  
- Examples:
  - **AWS:** Amazon EC2  
  - **Others:** Google Cloud, Azure, Rackspace, Digital Ocean, Linode  

### 2. **Platform as a Service (PaaS)**
- AWS manages the **underlying infrastructure** (servers, storage, networking).  
- You manage only:
  - Applications  
  - Data  
- Simplifies deployment and management of applications.  
- Examples:
  - **AWS:** Elastic Beanstalk  
  - **Others:** Heroku, Google App Engine, Microsoft Azure  

### 3. **Software as a Service (SaaS)**
- Fully managed by AWS or provider.  
- You just use the software; no infrastructure management needed.  
- Examples:
  - **AWS:** Rekognition (Machine Learning service)  
  - **Others:** Gmail, Dropbox, Zoom  

---

## 🏠 Comparison with On-Premises

| Component              | On-Premises | IaaS | PaaS | SaaS |
|------------------------|------------|------|------|------|
| Applications           | ✅         | ✅   | ✅   | ✅   |
| Data                   | ✅         | ✅   | ✅   | ✅   |
| Runtime                | ✅         | ✅   | ❌   | ❌   |
| Middleware             | ✅         | ✅   | ❌   | ❌   |
| OS                     | ✅         | ✅   | ❌   | ❌   |
| Virtualization         | ✅         | ❌   | ❌   | ❌   |
| Servers                | ✅         | ❌   | ❌   | ❌   |
| Storage                | ✅         | ❌   | ❌   | ❌   |
| Networking             | ✅         | ❌   | ❌   | ❌   |

---

## 💰 AWS Pricing Fundamentals

AWS pricing is **pay-as-you-go**:

1. **Compute** – pay for exact compute time used.  
2. **Storage** – pay for exact amount of data stored.  
3. **Networking** – pay only when data **leaves the cloud**; data coming in is free.  

**Benefit:** Huge cost savings compared to traditional IT.

---

## 📝 10 AWS CLF-C02 Exam-Style Questions

### Question 1
Which cloud model allows you to manage applications and data, while the provider manages servers, storage, and networking?

A. On-Premises  
B. IaaS  
C. PaaS  
D. SaaS  

<details><summary>Click to reveal</summary>
**Answer:** C. PaaS  
**Explanation:** Platform as a Service (PaaS) lets you manage applications and data only, while the cloud provider handles the infrastructure.
</details>

---

### Question 2
Which AWS service is an example of IaaS?

A. Amazon S3  
B. Amazon EC2  
C. Rekognition  
D. Gmail  

<details><summary>Click to reveal</summary>
**Answer:** B. Amazon EC2  
**Explanation:** EC2 provides virtual servers, making it Infrastructure as a Service.
</details>

---

### Question 3
Which of the following is true about SaaS? (Select two)

A. Provider manages infrastructure  
B. User manages servers  
C. Fully managed application  
D. User manages OS  

<details><summary>Click to reveal</summary>
**Answer:** A, C  
**Explanation:** SaaS is fully managed by the provider; users only use the software without managing the underlying infrastructure.
</details>

---

### Question 4
What is the main advantage of pay-as-you-go pricing?

A. You pay a fixed monthly fee  
B. You pay only for resources used  
C. You own all hardware  
D. No need for internet  

<details><summary>Click to reveal</summary>
**Answer:** B. You pay only for resources used  
**Explanation:** AWS allows cost optimization by charging only for the resources consumed.
</details>

---

### Question 5
Which cloud model gives you the **highest flexibility**?

A. SaaS  
B. PaaS  
C. IaaS  
D. None  

<details><summary>Click to reveal</summary>
**Answer:** C. IaaS  
**Explanation:** IaaS provides raw building blocks, giving users more control and flexibility.
</details>

---

### Question 6
Which of the following services is PaaS?

A. Elastic Beanstalk  
B. Amazon EC2  
C. Dropbox  
D. Amazon S3  

<details><summary>Click to reveal</summary>
**Answer:** A. Elastic Beanstalk  
**Explanation:** Elastic Beanstalk manages infrastructure while you focus on application and data.
</details>

---

### Question 7
In AWS, data transfer **into the cloud** is:

A. Free  
B. Paid per GB  
C. Paid per hour  
D. Charged per request  

<details><summary>Click to reveal</summary>
**Answer:** A. Free  
**Explanation:** AWS does not charge for incoming data; outgoing data is billed.
</details>

---

### Question 8
Which cloud model requires you to manage **everything**, including servers and networking?

A. SaaS  
B. PaaS  
C. IaaS  
D. On-Premises  

<details><summary>Click to reveal</summary>
**Answer:** D. On-Premises  
**Explanation:** Traditional on-premises IT requires management of all components.
</details>

---

### Question 9
Which of these is NOT a benefit of cloud computing?

A. Reduced maintenance cost  
B. Scalability  
C. Unlimited free compute time  
D. Pay-as-you-go pricing  

<details><summary>Click to reveal</summary>
**Answer:** C. Unlimited free compute time  
**Explanation:** AWS charges for resources used; there’s no unlimited free compute.
</details>

---

### Question 10
Which AWS service is SaaS?

A. Amazon EC2  
B. Amazon Rekognition  
C. Elastic Beanstalk  
D. Amazon S3  

<details><summary>Click to reveal</summary>
**Answer:** B. Amazon Rekognition  
**Explanation:** Rekognition is a fully managed AI service, classified as Software as a Service.
</details>

---


