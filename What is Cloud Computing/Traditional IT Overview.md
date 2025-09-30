## Traditional IT Overview
# ☁️ AWS Cloud Basics – Lecture Summary (CLF-C02)

Welcome to the **introduction to Cloud and Cloud Computing**.  
This section explains the basics of IT infrastructure, how servers and networks work, and why **Cloud Computing** offers advantages over traditional on-premises setups.

---

## 🌍 How Websites Work
- A **server** hosts the website.  
- A **client** (your browser) sends requests over a **network**.  
- The server processes the request and sends back a response.  
- This communication uses **IP addresses** (like sending/receiving letters with return addresses).  

---

## 🖥️ Components of a Server
A server typically includes:  
- **CPU (Compute)** 🧮 → performs calculations.  
- **RAM (Memory)** ⚡ → fast, temporary storage.  
- **Storage** 💾 → long-term storage (files, structured databases).  
- **Networking** 🌐 → routers, switches, DNS.  

➡️ Together, they form the foundation of IT infrastructure.  

---

## 📡 Networking Basics
- **Network** → group of cables, routers, and servers.  
- **Router** → forwards data packets between computers/networks.  
- **Switch** → directs packets to the correct client within a network.  

Analogy:  
📨 Router = Post office delivering letters.  
📬 Switch = Local mailman delivering to the correct home.  

---

## 🏠 Traditional IT Infrastructure
- Companies often started with servers in a **garage or office**.  
- As demand grew, they built **data centers** with multiple servers.  

### Challenges of On-Premises Data Centers
- 💰 **High Costs** → rent, electricity, cooling, maintenance.  
- 🕒 **Slow Scaling** → ordering & installing new servers takes time.  
- 👷 **Staffing Needs** → requires 24/7 monitoring.  
- ⚡ **Disaster Risks** → earthquakes, fires, outages can cause downtime.  

---

## ☁️ Why Cloud Computing?
Cloud providers (like **AWS**) solve these problems by:  
- Offering **on-demand IT resources**.  
- Eliminating large upfront costs.  
- Providing **scalability, reliability, and global availability**.  

---

# 📖 Exam-Style Practice Questions (CLF-C02)

Below are **10 AWS Certified Cloud Practitioner CLF-C02 style questions**.  
Some require **one correct answer**, others require **multiple answers**.

---

### Q1: Which of the following are advantages of using AWS Cloud over traditional on-premises infrastructure? *(Select TWO)*  
A. Pay-as-you-go pricing model  
B. Unlimited free usage  
C. Global reach and scalability  
D. No need for security  

<details><summary>Click to reveal</summary>  
✅ Correct Answer(s): A, C  
**Explanation:** AWS Cloud provides cost efficiency with pay-as-you-go and global scalability. Security is still required and usage is not unlimited free.  
</details>  

---

### Q2: What is the primary role of a router in networking?  
A. Storing data files  
B. Forwarding packets between networks  
C. Acting as temporary memory  
D. Encrypting all traffic  

<details><summary>Click to reveal</summary>  
✅ Correct Answer: B  
**Explanation:** A router forwards packets between networks, deciding the best path.  
</details>  

---

### Q3: Which AWS feature allows customers to scale resources up and down based on demand?  
A. Elasticity  
B. Durability  
C. Compliance  
D. Availability Zones  

<details><summary>Click to reveal</summary>  
✅ Correct Answer: A  
**Explanation:** Elasticity means adjusting compute/storage as workload demands change.  
</details>  

---

### Q4: In the analogy of sending a letter, what represents the **IP address**?  
A. The content of the letter  
B. The post office building  
C. The address written on the envelope  
D. The delivery truck  

<details><summary>Click to reveal</summary>  
✅ Correct Answer: C  
**Explanation:** The IP address functions like an address on the envelope so the network knows where to deliver.  
</details>  

---

### Q5: What are common problems with running your own data center? *(Select THREE)*  
A. High upfront costs  
B. Fast and automatic scaling  
C. Need for cooling and power supply  
D. Disaster recovery risks  

<details><summary>Click to reveal</summary>  
✅ Correct Answer(s): A, C, D  
**Explanation:** On-premises requires high CapEx, electricity/cooling, and faces risks like fire or outages.  
</details>  

---

### Q6: Which AWS concept provides redundancy across multiple geographic areas?  
A. Availability Zones  
B. Edge Locations  
C. Regions  
D. Virtual Private Cloud (VPC)  

<details><summary>Click to reveal</summary>  
✅ Correct Answer: C  
**Explanation:** AWS Regions are separate geographic areas. AZs exist inside regions.  
</details>  

---

### Q7: What is the role of a switch in networking?  
A. Forward data between networks  
B. Decide the best path across the internet  
C. Deliver packets to the correct device in a local network  
D. Store structured data in tables  

<details><summary>Click to reveal</summary>  
✅ Correct Answer: C  
**Explanation:** A switch directs packets to the correct device within a LAN.  
</details>  

---

### Q8: Which AWS pricing advantage is most important for startups?  
A. Large upfront investment  
B. Pay-as-you-go model  
C. Long hardware procurement cycles  
D. Free unlimited support  

<details><summary>Click to reveal</summary>  
✅ Correct Answer: B  
**Explanation:** Pay-as-you-go lets startups experiment without heavy upfront investment.  
</details>  

---

### Q9: Which AWS Cloud benefit directly helps in case of sudden traffic spikes?  
A. Elastic Load Balancing  
B. CloudFormation  
C. Elasticity  
D. Multi-Factor Authentication  

<details><summary>Click to reveal</summary>  
✅ Correct Answer: C  
**Explanation:** Elasticity lets resources scale up during spikes and scale down afterward.  
</details>  

---

### Q10: Why is Cloud Computing considered more reliable than on-premises infrastructure? *(Select TWO)*  
A. Built-in disaster recovery across regions  
B. Requires no maintenance at all  
C. On-demand scalability  
D. Data redundancy across Availability Zones  

<details><summary>Click to reveal</summary>  
✅ Correct Answer(s): A, D  
**Explanation:** AWS reliability comes from redundancy and disaster recovery features, but customers still share responsibility for maintenance.  
</details>  

---

# 📂 Suggested File Name
`aws-clf-c02-intro-to-cloud-summary.md`
