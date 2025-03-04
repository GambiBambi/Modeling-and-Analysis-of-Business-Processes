# 🚀 Camunda BPMN - Issue Management System

## 📝 Project Description

This project is a system for managing issue reports in an IT company that outsources its services. The system is based on a BPMN model implemented in Camunda and embedded in a Java environment. The main functionalities of the system include:

- 🛠️ **Registering issue reports** submitted by clients.
- 🔄 **Automatically assigning a technician** to the report.
- 📞 **Allowing the technician to contact** the client for additional information.
- ✅ **Finalizing the issue and notifying the client** about the result.
- 🔁 **Allowing the issue to be reopened** or continued if necessary.

## 🛠️ Technologies

- ⚙️ **Camunda BPM** – workflow engine for managing business processes.
- ☕ **Java** – the main programming language for the backend.
- 🌱 **Spring Boot** – framework for web application management.

## 🏗️ System Architecture

1. 📝 **Client submits an issue report** – via a web form.
2. 👨‍💻 **System assigns a technician** – business rules determine the most suitable technician.
3. 🔍 **Technician analyzes the issue** – with the ability to contact the client.
4. 🏁 **Technician resolves the issue and closes the report** – system sends a notification to the client.
5. ♻️ **Client can reopen the issue** – if the problem persists, the issue is returned to the technician.

## 🚀 BPMN Execution

The process is executed using the **Camunda Modeler** and **Camunda Platform**. The Camunda BPMN process definition is deployed to the Camunda engine, which manages the workflow execution. Users interact with the process through the **Camunda Tasklist** and **Cockpit** interfaces.

## 👩‍💻 Author
- **Julia Podsadna**

