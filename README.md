# Performance-Testing-on-NopCommerce


## Overview

This project focuses on conducting performance testing on the [NopCommerce](https://www.nopcommerce.com/) platform to evaluate its behavior under various load conditions. The primary objective is to identify potential bottlenecks and ensure the application's scalability and reliability.

## Objectives

- **Load Testing**: Assess how the application performs under expected user loads.
- **Stress Testing**: Determine the application's robustness by subjecting it to extreme conditions.
- **Scalability Analysis**: Evaluate the application's ability to scale with increasing demands.
- **Resource Utilization Monitoring**: Monitor CPU, memory, and other resources during testing to identify potential inefficiencies.

## Tools and Technologies

- **Apache JMeter**: Utilized for designing and executing performance test plans.
- **Java**: Required for running JMeter.
- **NopCommerce**: The e-commerce platform under test.

## Test Plan

The performance test plan includes:

- **User Registration**: Simulating multiple users registering simultaneously.
- **Product Search and Browsing**: Evaluating response times for product searches and category browsing.
- **Add to Cart and Checkout**: Assessing the performance during the checkout process with concurrent users.

## Setup and Execution

1. **Java JDK Installation**
   Access the [Link](https://www.oracle.com/bd/java/technologies/downloads/ ) and download Java JDK if it's not installed on device previously.

   To check if java is installed or not, write below command in the command prompt.
   ```bash
   java --version

2. **Apache Maven Installation**
   Access the [Link](https://maven.apache.org/download.cgi) and install "binary zip archive" to install Apache Maven.

   To check if maven installed or not run below command in command prompt.
   ```bash
   mvn --version

3. **JMeter Installation**
   Access the [Link](https://jmeter.apache.org/download_jmeter.cgi ) and install zip file from the binaries.

   To check if maven installed or not run the below command in command prompt.
   ```bash
   jmeter -v  

4. **Clone the Repository**:
   ```bash
   git clone https://github.com/Samia1925/Performance-Testing-on-NopCommerce.git
   cd Performance-Testing-on-NopCommerce
5. **Web Recording and Install Proxy Server**
   To do web-record video using JMeter further it is required to install proxy server. For that go to the bin folder of the JMeter installation folder. And double click on **ApacheJMeterTemporaryRootCA** and install it. Then upload it to desired browser.



 
