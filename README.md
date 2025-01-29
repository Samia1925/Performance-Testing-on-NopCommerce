# Performance-Testing-on-NopCommerce


## Overview

This project focuses on conducting performance testing for the [NopCommerce](https://www.nopcommerce.com/) platform to evaluate its behavior under various load conditions. The primary objective is to identify potential bottlenecks and ensure the application's scalability and reliability.

## Objectives

- **Load Testing**: Assess how the application performs under expected user loads.
- **Stress Testing**: Determine the application's robustness by subjecting it to extreme conditions.
- **Scalability Analysis**: Evaluate the application's ability to scale with increasing demands.
- **Resource Utilization Monitoring**: Monitor CPU, memory, and other resources during testing to identify potential inefficiencies.

## Tools and Technologies

- **[Apache Maven](https://maven.apache.org/download.cgi)**: to manage dependencies and automate the build process
- **[Apache JMeter](https://jmeter.apache.org/download_jmeter.cgi )**: Utilized for designing and executing performance test plans.
- **[Java](https://www.oracle.com/bd/java/technologies/downloads/ )**: Required for running JMeter.

## Test Plan

The performance test plan includes:

- **User Registration**: Simulating multiple users registering simultaneously.
- **Product Search and Browsing**: Evaluating response times for product searches and category browsing.
- **Add to Cart and Checkout**: Assessing the performance during the checkout process with concurrent users.

## Setup and Execution

1. **Java JDK Installation**:
   
   Access the [Link](https://www.oracle.com/bd/java/technologies/downloads/ ) and download Java JDK if it's not installed on device previously.

   To check if java is installed or not, write below command in the command prompt.
   ```bash
   java --version

2. **Apache Maven Installation**:
   
   Access the [Link](https://maven.apache.org/download.cgi) and install "binary zip archive" to install Apache Maven.

   To check if maven installed or not run below command in command prompt.
   ```bash
   mvn --version

3. **JMeter Installation**:
   
   Access the [Link](https://jmeter.apache.org/download_jmeter.cgi ) and install zip file from the binaries.

   To check if maven installed or not run the below command in command prompt.
   ```bash
   jmeter -v  

4. **Clone the Repository**:
   
   ```bash
   git clone https://github.com/Samia1925/Performance-Testing-on-NopCommerce.git
   ```
   ```bash
   cd Performance-Testing-on-NopCommerce
5. **Web Recording and Install Proxy Server**:

   To do web-record video using JMeter further it is required to install proxy server. For that go to the bin folder of the JMeter installation folder. And double click on **ApacheJMeterTemporaryRootCA** and install it. Then upload it to desired browser.


## Output
### View Results Tree
The View Results Tree listener shows the test results in a hierarchical format. It displays detailed information for each individual request made during the test, including response data, status (pass/fail), response time, and other associated data. This is useful for debugging and analyzing specific requests, especially if you want to see which requests failed or took longer than expected.

![Screenshot 2025-01-29 135239](https://github.com/user-attachments/assets/b32a6d41-35b3-46f7-ab2a-86cdde0df15c)

### Summary Report
The Summary Report listener provides a high-level overview of the test results, typically in a tabular format. It summarizes key performance metrics such as average response time, throughput, error rate, and the number of requests processed. This is ideal for quickly assessing overall system performance and for identifying any major issues in a single glance.

![image](https://github.com/user-attachments/assets/a85ffde4-3709-4568-82a7-a61d8207bc4f)


## Contributing
I welcome contributions from the community! To contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.
6. Please make sure to update tests as appropriate and adhere to the project's coding standards.

## Contact 
Samia Jahan-
[LinkedIn](https://www.linkedin.com/in/samia-jahan-binte-nour/)-
[github](https://github.com/Samia1925)

## **References:**
1. [JMeter User Manual](https://jmeter.apache.org/usermanual/index.html)
