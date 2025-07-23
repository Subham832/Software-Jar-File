
# 📦 Software Jar File Repository

A centralized and professionally maintained collection of essential development tools and runtime environments to streamline the setup of full-stack Java-based enterprise applications. This repository ensures efficient onboarding and configuration using pre-hosted binaries.

---

## 🔧 Table of Contents

1. [General Utilities](#1-general-utilities)  
2. [Web & Application Servers](#2-web--application-servers)  
3. [Developer IDEs](#3-developer-ides)  
4. [Java SDKs & Libraries](#4-java-sdks--libraries)  
5. [Databases & Drivers](#5-databases--drivers)  
6. [Build Tools](#6-build-tools)  
7. [Kafka Installation Guide](#7-kafka-installation-guide)  
8. [Usage Notes](#8-usage-notes)  

---

## 1️⃣ General Utilities

| Software  | Description             | Download Link |
|-----------|-------------------------|----------------|
| AnyDesk   | Remote desktop client   | [Download]()   |
| Chrome    | Web browser             | [Download]()   |
| Git       | Version control system  | [Download]()   |
| Postman   | API testing tool        | [Download]()   |

---

## 2️⃣ Web & Application Servers

| Server          | Purpose                          | Download Link |
|------------------|----------------------------------|----------------|
| Apache Tomcat     | Servlet and JSP container        | [Download]()   |
| Apache ZooKeeper  | Distributed coordination         | [Download]()   |
| Kafka             | Event streaming platform         | [Download]()   |
| Elasticsearch     | Search and analytics engine      | [Download]()   |
| Kibana            | Elasticsearch dashboard          | [Download]()   |
| LogStash          | Data pipeline and ETL tool       | [Download]()   |
| Ngrok             | Expose localhost to internet     | [Download]()   |

---

## 3️⃣ Developer IDEs

| IDE               | Description                     | Download Link |
|------------------|----------------------------------|----------------|
| Eclipse           | Open-source Java IDE             | [Download]()   |
| IntelliJ IDEA     | IntelliJ Community Edition       | [Download]()   |
| Spring Tool Suite | Spring-specific Java IDE         | [Download]()   |

---

## 4️⃣ Java SDKs & Libraries

| Component | Version | Download Link |
|-----------|---------|----------------|
| JDK       | 17      | [Download]()   |
| JDK       | 1.8     | [Download]()   |
| JSTL      | 1.2     | [Download]()   |

---

## 5️⃣ Databases & Drivers

| Tool               | Description                    | Download Link |
|--------------------|--------------------------------|----------------|
| MongoDB            | NoSQL database                 | [Download]()   |
| MongoSh Shell      | MongoDB CLI interface          | [Download]()   |
| MySQL Connector/J  | JDBC driver for MySQL          | [Download]()   |
| MySQL Workbench    | MySQL Workbench GUI            | [Download]()   |

📹 _[Watch: MySQL Workbench Setup Tutorial](#)_

---

## 6️⃣ Build Tools

| Tool   | Version | Description                     | Download Link |
|--------|---------|----------------------------------|----------------|
| Maven  | 3.9.11  | Project management & build tool | [Download apache-maven-3.9.11-bin.zip]() |

---

## 7️⃣ Kafka Installation Guide

A step-by-step local Kafka setup for development:

### ✅ Step 1: Download Kafka 3.9.1 (Scala 2.13)

📦 [Download kafka_2.13-3.9.1.tgz](#)  
Includes Kafka, ZooKeeper, and shell scripts.

### ✅ Step 2: Extract Kafka Archive

Use WinRAR, 7-Zip, or a terminal-based tool and extract to:

```
C:\kafka\kafka_2.13-3.9.1
```

### ✅ Step 3: Start ZooKeeper & Kafka Servers

#### 🔹 Terminal 1: Start ZooKeeper

```bash
cd C:\kafka\kafka_2.13-3.9.1
.in\windows\zookeeper-server-start.bat .\config\zookeeper.properties
```

_Keep this terminal running._

#### 🔹 Terminal 2: Start Kafka Server

```bash
cd C:\kafka\kafka_2.13-3.9.1
.in\windows\kafka-server-start.bat .\config\server.properties
```

✅ Kafka will be available at: `localhost:9092`

---

## 8️⃣ Usage Notes

- 🔗 **Access:** Ensure all Google Drive links are set to `Anyone with the link → Viewer`.
- 💾 **Backups:** Maintain local copies of critical binaries.
- 📌 **Updates:** Record version upgrades and broken links in your team changelog.

---

## 👨‍💻 Maintainer

**Subham Kumar**  
📫 _Contact for updates, additions, or improvement requests._

---

