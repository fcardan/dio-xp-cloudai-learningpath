![XP](https://assets.dio.me/ZvuV4yYlj9NDooaV8lNY3TTSW-n2kOP9Rs_7GLL25FA/f:webp/q:80/w:480/L3RyYWNrcy8yYjZkM2NkZC0zOWFiLTRlNzktYTQ3OS04NzE0NmNmMTk5NzAucG5n)

# 🌟 DIO + XP Inc. = Cloud with Artificial Intelligence

This repository documents my learning journey through the **DIO + XP Inc. Cloud & AI bootcamp**, serving as a structured knowledge hub for key concepts, hands-on labs, and best practices in **cloud computing** and **artificial intelligence**.

---

## 🔹 Table of Contents

- [1️⃣ - Introduction to Cloud Computing](#1️⃣-introduction-to-cloud-computing)
- [2️⃣ - Fundamentals of Generative AI](#2️⃣-fundamentals-of-generative-ai)
- [3️⃣ - Working with Prompt Engineering](#3️⃣-working-with-prompt-engineering)
- [4️⃣ - Working with GitHub Copilot](#4️⃣-working-with-github-copilot)
- [5️⃣ - Working with Cloud AI Services](#5️⃣-working-with-cloud-ai-services)

---

## 1️⃣-Introduction to Cloud Computing

### 🌐 Infrastructure Models

#### On-Premises (Local)

- The on-premises model refers to the physical infrastructure and IT systems that are installed, maintained, and managed within the company's own facilities.  
  - **Advantages:** Greater control and customization.  
  - **Disadvantages:** High maintenance costs and the need for physical space.  

#### Cloud Model  

- The cloud model is an internet-powered infrastructure where the company or user utilizes IT resources from an external provider.  
  - **Advantages:** Lower costs, scalability, and flexibility.  
  - **Disadvantages:** Dependence on internet connectivity.  

#### Hybrid Model  

- The hybrid model combines the benefits of both on-premises and cloud models.  
  - **Advantages:** Flexibility to choose what stays where according to needs.  
  - **Disadvantages:** Complexity in management.  

---

### Cloud Benefits

#### 🔹 Availability
High availability ensures maximum uptime by mitigating disruptions and failure events.

**Key Features**:
- 99.9% SLA for most services
- Availability Zones (physical redundancy)
- Geo-redundant storage options
- Automatic failover mechanisms

---

#### 🔹 Scalability
The ability to adjust resources to meet demand fluctuations.

| Vertical Scaling (Scale-Up)          | Horizontal Scaling (Scale-Out)       |
|--------------------------------------|--------------------------------------|
| Increasing individual VM capacity    | Adding more VM instances            |
| CPU/RAM upgrades                     | Load-balanced distribution          |
| Temporary performance boosts         | Elastic workload handling           |

_Azure Services: VM Scale Sets, Azure Kubernetes Service (AKS)_

---

#### 🔹 Reliability
The system's ability to recover from failures and maintain functionality.

**Resilience Mechanisms**:
- Automated backups
- Fault domains (rack-level redundancy)
- Health monitoring
- Self-healing architectures

_Example: Azure Site Recovery for disaster recovery_

---

#### 🔹 Predictability

##### ⚡ Performance:  
Forecasting required resources to maintain optimal user experience:
- Azure Autoscale
- Performance benchmarks
- AI-powered load forecasting

##### 💰 Cost:  
Estimating and optimizing cloud expenditures:
- Azure Pricing Calculator
- Cost Management + Billing
- Reserved Instances (up to 72% savings)

---

#### 🔹 Manageability
Cloud capabilities that support governance and compliance across service models.

| IaaS Management               | SaaS Management                |
|-------------------------------|--------------------------------|
| Azure Resource Manager        | Microsoft 365 Admin Center    |
| Azure Policy                  | Azure AD Conditional Access   |
| Azure Monitor                 | Service Health monitoring     |

**Key Advantages**:
- Unified management portal
- Compliance certifications (ISO, SOC, GDPR)
- Infrastructure-as-Code support (ARM templates)

---

### ☁️ Cloud Service Types

#### IaaS (Infrastructure as a Service)
- The cloud provider is responsible for:  
  - Maintaining hardware  
  - Network connectivity (internet)  
  - Physical security  
_Example: Virtual machines, raw storage, networking components._

#### PaaS (Platform as a Service) 
- The cloud provider manages:  
  - Physical infrastructure  
  - Physical security  
  - Internet connectivity  
  - Operating systems, middleware, development tools, and BI services  
_Example: Development platforms, database management, app hosting._

#### SaaS (Software as a Service)
- A fully developed application rented/used by the customer.  
  - Email services (e.g., Gmail, Outlook)  
  - Financial software (e.g., QuickBooks)  
  - Messaging apps (e.g., Slack, Teams)  
  - Collaboration tools (e.g., Google Workspace)  

![XP](https://learn.microsoft.com/pt-br/training/wwl-azure/describe-cloud-service-types/media/shared-responsibility-b3829bfe.svg)

---

## 2️⃣-Fundamentals of Generative AI

### Key Concepts Covered:
- **Artificial Intelligence (AI)**: Systems designed to perform tasks that typically require human intelligence, such as learning, reasoning, and problem-solving.
- **Machine Learning (ML)**: A subset of AI where systems learn from data without being explicitly programmed, enabling them to improve their performance over time.
- **Deep Learning**: A subset of ML that utilizes neural networks with multiple layers (deep neural networks) to analyze various factors of data. This approach is particularly effective for complex pattern recognition tasks.
- **Generative AI**: A type of artificial intelligence that can create new content, such as text, images, video, audio, or software code, in response to a user's prompt or request. It learns patterns and structures from existing data and uses this knowledge to generate similar, yet original, content. 
- **Redes Neurais**: Computational models inspired by the human brain's interconnected neuron structure. They consist of layers of nodes (neurons) that process data by assigning weights and biases, enabling tasks like pattern recognition and data classification.
- **Generative Adversarial Networks (GANs)**: A class of deep learning architectures composed of two neural networks—a generator and a discriminator—that compete against each other. The generator creates new data instances, while the discriminator evaluates them for authenticity. This adversarial process enhances the quality of the generated data over time. 
- **Deep Fake**: Media content, typically videos or images, that have been altered or generated by AI to convincingly misrepresent someone as doing or saying something that did not occur. Deep fakes leverage advanced AI techniques, including GANs, to produce realistic yet fabricated content.

### Main AI Applications:
- **Computer Vision**: Image/object recognition (e.g., facial recognition)
- **Natural Language Processing**: Chatbots, translation, sentiment analysis
- **Predictive Analytics**: Forecasting trends from historical data

### Machine Learning Paradigms
- **Supervised Learning**:
In this approach, models are trained using labeled datasets, where each input is associated with a known output. The goal is to learn a mapping from inputs to outputs, enabling accurate predictions or classifications on new, unseen data.

- **Unsupervised Learning**:
Here, models work with unlabeled data and aim to uncover hidden patterns or intrinsic structures within the data. Techniques such as clustering and dimensionality reduction are commonly employed to identify groupings or representations that reveal the underlying distribution of the data.
  
- **Reinforcement Learning**:
This paradigm involves an agent that learns to make decisions by interacting with an environment. The agent receives feedback in the form of rewards or penalties based on its actions, and the objective is to learn a strategy that maximizes cumulative rewards over time.

![XP](https://camo.githubusercontent.com/551accff514385b3d66c83162de771eff03105bb3e18db861eb25bb27a6d4b9b/68747470733a2f2f6d69726f2e6d656469756d2e636f6d2f6d61782f313833382f312a6f4233533579484868766f75674a6b50587563386f672e676966)

### Computer Vision

- **Convolutional Neural Networks (CNNs or ConvNets)**:
Are a specialized type of deep neural network widely used in computer vision tasks such as image recognition, object detection, and semantic segmentation. Inspired by the organization of the biological visual cortex, CNNs are highly efficient at processing grid-structured data, like images.

- **Multimodal models**:
Integrate multiple data types (e.g., text, images, audio) to improve AI understanding and generation capabilities.

- **Azure AI Vision**:
Is a cloud-based service for image and video analysis, offering:

  - Pre-trained APIs: Object detection, OCR, facial recognition, and moderation.
  - Custom Vision: Train models with user-specific datasets (e.g., defect detection in manufacturing).
  - Spatial Analysis: Real-time video processing for scenarios like retail analytics.

![XP](https://cdn-dynmedia-1.microsoft.com/is/image/microsoftcorp/acom-full-it28kz3v-1?resMode=sharp2&op_usm=1.5,0.65,15,0&wid=1664&hei=1062&qlt=100&fmt=png-alpha&fit=constrain)

---

## 3️⃣-Working with Prompt Engineering

🚧 *Content under development...*

---

## 4️⃣-Working with GitHub Copilot

🚧 *Content under development...*

---

## 5️⃣-Working with Cloud AI Services

🚧 *Content under development...*

---
