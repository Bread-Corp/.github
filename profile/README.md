# 🦆🍞 Bread Corporation - Tender Tool 🍞🦆

Welcome to the official GitHub organization for **Bread Corporation**!

Our name comes from a simple idea: bread is a staple in most people's lives. As **BreadCorp**, we aim to provide **staple solutions**—robust, reliable, and essential tools that organizations can depend on every day.

We're thrilled to present our flagship project, **Tender Tool**, a complete, automated system for the discovery, classification, and analysis of public sector tenders in South Africa 🇿🇦.

---

## 🌟 Quick Start

**Experience Tender Tool right now:**

🚀 **[Live Application](https://release.dhfinobe712wv.amplifyapp.com/)** - Try our production system!

![WEBSITE SCREENSHOT](https://github.com/user-attachments/assets/103a9282-3da4-47fe-b152-dc707e59a4b4)

📊 **Explore 500+ tenders** from across South Africa's public sector

🔍 **Search & filter** with our AI-powered classification system

---

## 📜 Project Overview: Tender Tool

**Tender Tool** is your automated assistant that cuts through the noise of public procurement. It is a fully serverless, event-driven application that:

- 🕵️‍♂️ **Discovers** tenders from multiple government and state-owned entity (SOE) websites
- 🤖 **Summarizes** complex tender documents using Generative AI (Amazon Bedrock)
- 🏷️ **Tags & Categorizes** tenders automatically for easy filtering
- 🧹 **De-duplicates** and cleanses data to ensure high quality
- ☁️ **Serves** this data through a secure, scalable web API
- 🔍 **Enables advanced search** with our OpenSearch-powered discovery engine

No more manual hunting across dozens of websites. **Tender Tool** does the hard work, allowing businesses to focus on winning contracts. 💼

### 📈 By the Numbers

- **538 tenders** actively tracked
- **5 major sources** continuously monitored (eTenders, Eskom, SANRAL, SARS, Transnet)
- **100% serverless** architecture with zero server maintenance
- **AI-powered** summaries and categorization
- **Real-time** data processing pipeline

---

## 💡 The Problem We're Solving

Public tender information is crucial but notoriously difficult to manage. It's **scattered** across countless portals, **inconsistent** in format, and **hard to track**. Our goal was to build a system that:

- ✅ Centralizes tender information into one clean source
- ✅ Enables better and faster decision-making for suppliers
- ✅ Creates a foundation for transparency and data analysis on public spending
- ✅ Reduces the time-to-discovery from hours to seconds

**Before Tender Tool:** Manual checking of 20+ websites daily  
**After Tender Tool:** One unified dashboard with intelligent alerts

---

## 🚀 Our Cloud-Native Architecture

The entire Tender Tool system is built on a 100% serverless, event-driven architecture using **Amazon Web Services (AWS)**. This design makes it highly scalable, resilient, and extremely cost-effective.

### The Data Journey

Our system operates as a sophisticated data processing pipeline:

1. **🕷️ Scrapers & Ingestion:** Specialized AWS Lambda functions collect raw tender data from multiple sources
2. **🔄 Event-Driven Pipeline:** Data flows through **Amazon SQS** FIFO queues for guaranteed ordering and reliability
3. **⚡ Parallel Processing:** Independent Lambda functions handle different aspects simultaneously:
   - **📝 Database Writes:** Storing tender info in **AWS RDS**
   - **🤖 AI Summarization:** Generating concise summaries with Amazon Bedrock
   - **🏷️ AI Tagging:** Intelligent classification and tagging
   - **🧹 De-duplication:** Advanced algorithms to identify and merge duplicates
4. **🌐 API & Web:** High-performance .NET 8 API on **AWS Lambda** with **Amazon API Gateway**
5. **🔍 Advanced Search:** **Amazon OpenSearch** cluster for lightning-fast full-text search
6. **🛡️ Security & Auth:** **AWS Cognito** for secure user management
7. **📊 Monitoring & Logging:** Comprehensive observability with **AWS CloudWatch**

### Architecture Diagram

This diagram visualizes the complete flow from data ingestion to user-facing applications:

![Tender Tool Cloud Architecture Diagram (Final) - JPEG](https://github.com/user-attachments/assets/dc9efad0-9a43-4f65-bbc8-0d05e6604786)

---

## 🔧 Core Tech Stack

Built with modern, enterprise-grade technologies:

| Category | Technology | Purpose |
|----------|------------|---------|
| **☁️ Cloud Provider** | **Amazon Web Services (AWS)** | Complete cloud infrastructure |
| **⚡ Compute** | **AWS Lambda** (.NET 8 + Python) | Serverless function execution |
| **🗄️ Database** | **AWS RDS** (MS SQL Server) | Relational data storage |
| **🌐 API Layer** | **Amazon API Gateway** (REST) | Secure API management |
| **📨 Messaging** | **Amazon SQS** (FIFO Queues) | Reliable message processing |
| **🔍 Search Engine** | **Amazon OpenSearch** | Advanced search capabilities |
| **🤖 AI/ML** | **Amazon Bedrock** (Claude 3 Sonnet) | AI summarization & tagging |
| **🔐 Authentication** | **AWS Cognito** | User management & security |
| **📦 Storage** | **AWS S3** | File storage & static hosting |
| **📊 Monitoring** | **AWS CloudWatch** | Logging, metrics & alarms |
| **🚀 Frontend Hosting** | **AWS Amplify** | React app deployment & CI/CD |
| **🔄 CI/CD** | **GitHub Actions** | Automated deployment pipelines |
| **🏗️ Backend Framework** | **.NET 8** | High-performance API development |
| **🎨 Frontend Framework** | **React + TypeScript** | Modern web application |

---

## 🎯 Key Features & Capabilities

### For Businesses
- **🔍 Intelligent Search:** Find relevant tenders across all sources instantly
- **📊 Smart Filtering:** Filter by category, region, value, and closing dates
- **🤖 AI Summaries:** Get the key points without reading lengthy documents
- **📱 Mobile-Friendly:** Access from any device, anywhere
- **🔔 Real-Time Updates:** Stay informed about new opportunities

### For Developers
- **📖 Comprehensive APIs:** RESTful endpoints with full documentation
- **🔒 Secure Authentication:** OAuth 2.0 / JWT token-based security
- **⚡ High Performance:** Sub-second response times with caching
- **📈 Scalable Architecture:** Handles traffic spikes automatically
- **🛠️ Developer-Friendly:** Clear error messages and extensive logging

---

## 🛣️ Our Journey & Future Roadmap

This project represents the culmination of our final-year team's journey. Across our **16 repositories**, we've built a complex, production-ready system from scratch, mastering everything from cloud architecture and DevOps to AI integration and data engineering.

### 🎯 Current Status: **Production Ready** ✅

### 🔮 Future Enhancements

- **💬 Conversational AI:** Amazon Lex integration for natural language queries
  > *"Find me all IT tenders in Gauteng closing this month"*
- **⚡ Performance Optimization:** Amazon ElastiCache for millisecond response times
- **📊 Advanced Analytics:** Predictive insights and market trend analysis

---

## 🧑‍💻 Meet the Team Behind BreadCorp

We are **Bread Corporation** - a passionate team of final-year Computer Science students who transformed an idea into a production-ready system that's changing how businesses discover public sector opportunities.

### 👥 The Dream Team

| Team Member | Primary Role | Secondary Role | Expertise |
|-------------|--------------|----------------|-----------|
| **Ashish Deepak Dannyeswar** | 🎯 Project Manager | 🏗️ Solutions Architect | Strategic planning & system design |
| **Sashveer Lakhan Ramjathan** | ⚙️ DevOps Engineer | ☁️ Cloud Architect | AWS infrastructure & automation |
| **Blaise Mikka de Gier** | 🔧 Lead Backend Developer | 🤖 AI/ML Specialist | API development & machine learning |
| **Kayden Ryan Reddy** | 📱 Android Developer | 🔐 Auth Specialist | Mobile development & security |
| **Fathima Bibi Shariff** | 🎨 Frontend Developer | 🎯 UI/UX Designer | React development & user experience |
| **Atiyyah Moola** | 🗄️ Database Administrator | 📊 Data Analyst | Data architecture & optimization |
| **Azrah Abdul Habib** | 📋 Research Coordinator | 📈 Business Analyst | Market research & requirements |

*Each team member contributed unique skills that made this ambitious project possible.*

---

## 🤝 Contributing & Community

While this is primarily a showcase of our capstone project, we welcome:

- 🐛 **Bug reports** and feature suggestions
- 📖 **Documentation** improvements
- 🤝 **Collaboration** opportunities
- 💼 **Professional networking**

---

## 📄 License

This project and all its associated code are licensed under the **Apache 2.0 License**.

---

## 🙏 Acknowledgments

Special thanks to our academic supervisors, AWS for educational credits, and the open-source community that made this project possible.

---

> **Built with ☕, 🍞, and determination by Bread Corporation** 🦆❤️💻  
> *Serving up staple solutions, one line of code at a time*

**Ready to explore?** [**Try Tender Tool Now →**](https://release.dhfinobe712wv.amplifyapp.com/)
