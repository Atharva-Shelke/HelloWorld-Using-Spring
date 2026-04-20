# Hello World application using Spring Framework (XML Configuration)

A foundational application demonstrating the core concepts of the **Spring Framework** using traditional XML-based configuration (without Spring Boot).

## 🚀 Overview

This project serves as a starting point for understanding how Spring manages objects using **Inversion of Control (IoC)** and **Dependency Injection (DI)**. It shows how a simple Java class (POJO) is configured and managed by the Spring container.

## 🛠️ Features

* **Spring IoC Container**: Uses `ApplicationContext` to manage beans.
* **XML Configuration**: Bean definitions and dependencies configured in `beans.xml`.
* **Dependency Injection**: Injects values using setter-based DI.
* **Loose Coupling**: Business logic is independent of framework code.

## 📂 Project Structure

* `HelloWorld.java`: A simple POJO with a message property and a method to display it.
* `MainApp.java`: Loads the Spring container and retrieves the bean.
* `beans.xml`: XML configuration file defining the Spring bean and injected values.
* `pom.xml`: Maven configuration for dependencies.

## ⚙️ How to Run

1. Import this project into **Eclipse** or **Spring Tool Suite (STS)**.
2. Ensure Maven dependencies are downloaded (`Maven → Update Project`).
3. Navigate to `MainApp.java`.
4. Right-click and select **Run As → Java Application**.
5. Console output will display the message.

## 📝 Prerequisites

* **JDK 1.8**
* **Maven**
* **Eclipse / Spring Tool Suite (STS)**
