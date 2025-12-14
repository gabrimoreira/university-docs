# Software Verification, Validation, and Testing (V&V) - Project Tomato

This repository contains the documentation and artifacts generated during the **Software Verification, Validation, and Testing** (*Verificação, Validação e Teste de Software*) course at the Federal University of Ceará (UFC), Department of Computer Science.

The project focuses on applying V&V techniques to **"Tomato"**, an open-source FullStack food delivery application built with the MERN stack (MongoDB, Express.js, React.js, Node.js).

## Documentation Overview

The project is divided into four stages, documenting the lifecycle of the testing process:

### 1. Project Scope & Requirements
**File:** `TB1.pdf` (*Escopo do projeto de V&V*)

This document defines the scope of the V&V project and analyzes the target application.
* **Target Application:** Tomato (Food Delivery Website).
* **Objective:** Identification of Functional Requirements (RF) to be tested, covering both Client and Admin functionalities.
* **Key Requirements Mapped:** Login/Signup, Cart management, Order tracking, and Admin inventory management (Add/Remove items).

### 2. V&V Plan
**File:** `TB2.pdf` (*Plano de V&V*)

This document outlines the strategy and resources required for the testing phase.
* **Testing Strategy:** Definition of test levels, including Static Analysis, Unit Testing, Interface Testing, and Load Testing.
* **Tools Selected:** Jest, Cypress, ESLint, Postman, and Artillery.
* **Risk Management:** Identification of potential risks (e.g., team reduction, environment issues) and mitigation strategies.
* **Schedule:** Timeline for test execution and artifact delivery.

### 3. Test Specification
**File:** `TB4.pdf` (*Especificação de Teste*)

This document details the test cases derived from the functional requirements.
* **Test Design:** Specification of 20 Test Cases (CT001 - CT020) covering scenarios for Authentication, Shopping Cart, Order Status, and Admin Panel.
* **Techniques Applied:**
    * Equivalence Partitioning.
    * Boundary Value Analysis (e.g., cart quantity limits).
    * State Transition Testing.
    * Interface Testing.
* **Structure:** Each test case includes preconditions, input data, step-by-step execution, and expected results.

### 4. Failure Report & Test Results
**File:** `TB6.pdf` (*Relatório de Falhas*)

This final report presents the results of the test execution and documents the failures found.
* **Execution Summary:** 22 test cases executed with a ~25% failure rate (5 failures).
* **Critical Bugs Found:**
    * **Integrity:** System allows duplicate user registration (same email).
    * **Usability/Logic:** "Track Order" button unresponsive for pending orders.
    * **Validation:** Admin panel allows uploading non-image files (e.g., PDFs) as product images.
    * **Performance:** Excessive delay in item removal leading to multiple error notifications.

## Tools & Technologies
* **Target App Stack:** MERN (MongoDB, Express, React, Node).
* **Testing Tools:**
    * **Jest:** Unit Testing.
    * **Cypress:** Interface/E2E Testing.
    * **ESLint:** Static Code Analysis.
    * **Postman/Artillery:** Load Testing.

## Authors
* **Gabriel Moreira de Andrade**
* **Álvaro Siqueira Galvão**
* **Fábio Agostinho Filho**
