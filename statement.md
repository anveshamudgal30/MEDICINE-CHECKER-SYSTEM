# 📋 Project Statement

## 🚨 Problem Statement

In environments where quick access to essential drug information is critical, relying on paper records or large, complex digital systems can be time-consuming and inefficient. The problem is the need for a **simple, accessible, and manageable system** to store, retrieve, and update vital details—such as dosage, precautions, side effects, and availability—for a limited set of commonly used medicines. The current solution aims to address the need for a basic digital inventory and information checker for common drugs.

## 🎯 Scope of the Project

The scope of this project is limited to:

1.  **Core CRUD Operations:** Implementing the four primary functions: **C**reate (Add), **R**ead (Search/Show All), **U**pdate, and **D**elete (Remove) on medicine records.
2.  **In-Memory Data Storage:** The medicine data is stored in a Python dictionary. The data is **not persistent**; it resets every time the program is closed and restarted.
3.  **Command-Line Interface (CLI):** The entire interaction is handled through terminal input and output, without any graphical user interface.
4.  **Basic Validation:** Includes checking if a medicine exists before adding, updating, or removing, and handling invalid menu choices.

The project **does not** include:
* Integration with external databases (e.g., SQL, NoSQL).
* User authentication or security features.
* Advanced search capabilities (e.g., searching by side effect, dosage range).
* Persistent data storage (saving data to a file like CSV, JSON, or a database).

## 👤 Target Users

The primary target users for this system are:

* **Small Pharmacy Technicians/Assistants:** For quick lookups of common drug information and checking basic stock status.
* **Clinic Staff (Non-Prescribing):** For rapid reference on patient inquiries regarding dosage and general precautions.
* **Students/Individuals:** For educational purposes or for personal management of a small, household medicine cabinet inventory.

## 🚀 High-Level Features

1.  **Information Retrieval:** Provide instantaneous access to full medicine details based on name.
2.  **Data Management:** Allow for flexible modification and removal of medicine entries.
3.  **Availability Tracking:** Include a simple method to record and display the current stock level (`In stock`, `Low stock`, `Out of stock`).
4.  **User-Friendly CLI:** Present a clear, numbered menu system for ease of navigation.