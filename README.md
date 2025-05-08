# User-and-Role-Management

[![Java](https://img.shields.io/badge/Java-17+-blue.svg)](https://www.oracle.com/java/)  
[![Spring Boot](https://img.shields.io/badge/Spring--Boot-3.x-brightgreen.svg)](https://spring.io/projects/spring-boot)  
[![Build](https://img.shields.io/badge/Build-Maven-blue.svg)](https://maven.apache.org/)  
[![License](https://img.shields.io/badge/License-MIT-lightgrey.svg)](LICENSE)

A Spring Boot project demonstrating Clean Architecture for a basic Role-Based Access Control (RBAC) system.

## 📌 Key Features

- Create users and roles  
- Assign roles to users  
- Fetch user details with assigned roles  
- Follows Clean Architecture (Domain, Use Case, Infrastructure, Configuration layers)  
- In-memory H2 database integration  
- Strong input validation and detailed error handling  
- Unit testing of the Use Case layer  

---

## 🚀 Getting Started

### Prerequisites

- Java 17 or newer  
- Maven  
- IntelliJ IDEA (recommended)

### Run the Application

```bash
git clone https://github.com/yourusername/your-repo-name.git
cd RBAC
mvn clean install
mvn spring-boot:run
