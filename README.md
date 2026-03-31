# MVC Web Development in Java

This repository contains resources and exercises to help you learn the basics of web development in Java, using **servlets** and **JSP pages**.

> [!TIP]
> **Access the full course:** [https://stahe.github.io/en-java-web-mvc-mai-2006/](https://stahe.github.io/en-java-web-mvc-mai-2006/)

---

## 📖 Introduction

The aim of this resource is to cover the fundamental concepts of Java web programming through a **3-tier MVC** architecture. This document is based on the January 2005 article ‘Java web development with Eclipse and Tomcat’, adding:
* The use of the **Eclipse WTP** plugin.


* A structure based on **3-tier architecture**.


* A practical example using a **DBMS**.



## 🏗️ Application architecture

The project follows a three-tier structure to ensure the code’s modularity and stability:

**Web layer [web]** | Interface allowing the user to control the application and receive information.

**Business Layer [business]** | Contains the business logic. Independent of the interface (web, console, etc.), it is the most stable layer.

**Data Access Layer [DAO]** | Manages access to persistent data (DBMS) or external data (sensors, network).


## 🚀 Learning methods

There are several possible approaches to this content, ranging from the quickest to the most effective:

1. **Experienced Approach:** Install the tools and test the downloaded code directly (for developers familiar with Eclipse/WTP only).


2. **Quick Approach:** Copy and paste the code whilst following the document. Allows you to progress quickly, but some concepts may remain ‘magical’.


3. **Guided Approach:** Identical to method 2, but consult the reference document `[ref1]` (Introduction to Web Programming in Java) whenever advised.


4. **Recommended Approach:** Type out the entire code manually whilst reading carefully. This is the most effective method for understanding the logic and correcting your own syntax errors.

