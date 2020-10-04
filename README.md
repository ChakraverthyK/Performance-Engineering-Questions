# ⚡ Performance Engineering Questions

## ✨ Overview
As a performance tester/engineer, we have to understand of almost everything about the project, application and what not. To acquire that knowledge we need to ask questions to the architects, developers, product owners etc.

No questions are stupid, only the answers are. This repository will list out the questions you can ask to your team.

> *Even Einstein asked questions.*

## ❗ Assumptions

- In this context, application means it could web application, services, database etc. Based on the project, you can ask the relevant question.
- These questions derived based on web protocols.

## ❓ Questions

### 🕸 Application/Service

 - What is the objective of this exercise(performance testing)?
 - Known performance issues
 - Can I get the access to the architecture diagram?
 - What is the core aspect of the application/service?
 - Tech stack of the application
 - Is the functional testing completed? 
 - Is the application served over HTTPS?
 - Is the application on cloud?
 - Is the auto scaling turned on?
 - Is caching enabled?
 - Is the application load balanced?
 - Is the firewall enabled?
 - Is proxy required to access the application?

### 🌐 Environment

 - Is it already available in production?
    - If it is in production, can I get access to the production logs?
 - Is stage or non-production environment available?
 - Is the test environment identical to the production?
    - If not, what is the scaled down factor?
 - Is APM solution available?
 - Is the performance testing environment up-to-date?
 - Is the application under test stable?
 - Do I get access to start/stop/restart the servers?

### 👨‍👩‍👧‍👦 End Users

 - Who are all the end users?
 - End users demographics
 - End users device preferences
 - End users network preferences
 - End users broswer preferences

### 🔢 SLAs, SLOs and all about numbers

 - What are all the SLAs and SLOs?
 - How many users/transactions need to be injected?
 - Acceptable SLAs: 
    - Response time
    - Throughput
    - CPU
    - Memory
    - Garbage Collection
    - Disk
    - Network
 - What is the network virtualization distribution?

### 💾 Test data

 - Is the test data available?
 - Is the test data reusable?
 - Is there a dedicated team available to help me out to generate test data?

### ⚒️ Tools

 - Is the performance testing tool available?
 - Is the relevant licenses available?
 - Do we need to inform any other team before we begin the testing?

### 📜 Scripting

 - Critical scenarios to be tested
 - List of browsers to be tested 
 - List of services and its method to be tested

### 📊 Testing

 - Types of performance testing in scope
 - Is the workload model design available?
 - Is IP spoofing required?
 - Ramp up, steady state, and ramp down duration
 - Duration of the test
 - Is baseline results available?
 - Is performance trend report required?
 
### 🔁 Process 

 - Before we start the test, do we need to inform any other team?
 - Timeline for the project
 - To whom I can assign the defect?
 - What is the escalation process?
 - What are all the risks involved in this project and its mitigation plan?
 - List of contacts of developers, architects, and others

## 🙏 Contributions

All kinds of contributions are welcome. Please submit a [PR](https://github.com/QAInsights/Performance-Engineering-Questions/pulls).