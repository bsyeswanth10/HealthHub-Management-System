# **Medical Center Management System**  

## **Overview**  
The HealthHub Management System is a web-based application designed for the Meenakshi Medical College Hospital and Research Institute to streamline and automate their existing manual processes. This system aims to enhance efficiency in managing patient information, distributing medicine, maintaining inventory, and generating reports.  

## **Problem Statement**  
The current system at Meenakshi Medical College Hospital and Research Institute is heavily reliant on paper-based, manual processes for managing patient demographics, issuing prescriptions, distributing medicine, and maintaining medicine stock. This results in inefficiencies, increased workload, and the potential for errors. Therefore, an automated online management system is required to improve service delivery and operational efficiency.  

## **Project Objectives**  
The proposed system provides a user-friendly graphical interface to manage tasks such as:  
- Patient diagnosis management and test prescriptions.  
- Prescription and medication management, including dietary advice and precautions.  
- Medicine inventory management across central-store and sub-store levels.  
- Monitoring the flow of newly purchased medicine and stock levels.  
- Generating billing reports for employees and other relevant reports.  
- Recommending future medicine purchases based on stock levels and usage trends.  
- Password recovery through security questions.  

## **Users**  
- **General Users:** Patients (Students and Staff).  
- **Administrative Users:** Doctors, Pharmacists, Store Officers, Medicine Distributors.  

## **System Features**  
- Comprehensive digitalization of the current management system.  
- Secure online access for patients to view prescriptions from anywhere.  
- Web-based and desktop-based user interfaces for convenience and accessibility.  
- Efficient medicine inventory management through centralized and decentralized stores.  
- Support for generating reports and monitoring inventory levels.  

## **System Interfaces**  
- **Internet Clients:** Accessed via web browsers on any operating system.  
- **Intranet Clients:** Accessed via client software or web browsers over TCP/IP protocol.  
- **Web Server:** Apache Tomcat, compatible with various operating systems.  
- **Database:** MySQL.  

## **Communication Protocols**  
- **Internet Clients:** HTTP/HTTPS Protocol.  
- **Intranet Clients:** TCP/IP Protocol.  

## **Installation Guide**  
1. Install JDK.  
2. Install NetBeans IDE (Version 6.9.1).  
3. Install MySQL and configure with username: `root` and password: `admin` (can be customized by modifying `database.java` file in the project directory).  
4. Install Firefox web browser.  
5. Open NetBeans IDE and import the MedicalCentre project as a web project.  
6. Add `mysql-connector-java-5.1.6-bin.jar` to the project libraries if not already included.  

## **Known Issues**  
If database configuration errors occur, refer to the `DBQuery.sql` file for necessary database queries, triggers, procedures, and events.  

## **Dummy User Accounts for Testing**  

| User Name | Password | User Type           |
|-----------|----------|---------------------|
| Rishi     | d        | Doctor              |
| Namitha   | d        | Doctor              |
| pharmacist| p        | Pharmacist          |
| md        | md1      | Medicine Distributor|
| a-cse     | p        | Patient (Employee)  |
| b-cse     | p        | Patient (Employee)  |
| 2007331039| mokarrom | Patient (Student)   |
| 2007331023| p        | Patient (Student)   |
