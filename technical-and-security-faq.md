# Technical & Security FAQ

## **Introduction**

The X-ray Simulator is an advanced X-ray simulation software designed to support educational institutions in providing high-quality training for radiologic technology students. This guide addresses key security, compliance, and technical considerations for IT and security personnel evaluating the solution.

## **Business Purpose & Functionality**

### **What is the X-ray Simulator?**

The X-ray Simulator is a virtual training platform that allows educators to simulate real-world X-ray imaging scenarios. It enhances student learning through interactive exercises, and risk-free guided training.

#### **Key Features:**

* Realistic X-ray simulation for student training
* Interactive image acquisition and positioning
* Scalable platform for individual and classroom use
* Secure locally installed software with online license authentication

## **Common Questions:**

**Q: Who would our direct contact be for support/assistance?**\
**A:** Support is provided through **support@vitasim.dk**, and reference guides and documentation can be found at **support.vitasim.dk**. Support is available during the times listed on the website.

**Q: Is the software cloud-based and hosted by the X-ray Simulator?**\
**A:** No, the X-ray Simulator is a desktop-based software that requires installation on a PC. However, it does use the internet for license authentication during login.

**Q: Does the software integrate with any other systems?**\
**A:** No, the X-ray Simulator does not integrate with external systems. It is a standalone application that must be installed on a PC. The only online interaction occurs during authentication.

**Q: What types of data are collected and stored in the X-ray Simulator?**\
**A:** The software does not store personal data. Instead, it uses **“dump” users** that institutions can distribute to students. The data collected includes:

* **Logging of activity**, such as login time and application performance metrics (e.g., FPS).
* **Simulation progress** should a user choose to save their progress for future sessions.

**Q: What is a "dump" user, and why does the X-ray Simulator use them?**\
**A:** A "dump" user is a generic, non-personalized account provided to institutions to assign to students. Instead of tracking individual users, the X-ray Simulator allows institutions to manage access through pre-set accounts (e.g., User X1, X2, etc.), ensuring that no personally identifiable information (PII) is stored within the system. These accounts can be reset or reassigned as needed.

**Q: Does the X-ray Simulator require an internet connection to function?**\
**A:** The software only requires an internet connection for user authentication upon login. Once authenticated, it operates fully offline.

**Q: What are the hardware requirements for using the X-ray Simulator?**\
**A:** The X-ray Simulator requires a PC that adhere to the requirements below for optimal performance. The VR version also requires a compatible tethered VR headset. Institutions should ensure that their hardware meets the system requirements before installation.

* For **VR hardware requirements**, visit: [Minimum Requirements for VR the X-ray Simulator](https://support.vitasim.dk/x-ray-simulator/useful-knowledge/minimum-requirements-for-running-the-vr-x-ray-simulator)
* For **Desktop hardware requirements**, visit: [Minimum Requirements for Desktop the X-ray Simulator](https://support.vitasim.dk/x-ray-simulator/useful-knowledge/minimum-requirements-for-running-the-desktop-x-ray-simulator)

**Q: How are users managed within the X-ray Simulator?**\
**A:** Institutions receive a set of **“dump” user accounts** (e.g., X1, X2, etc.), which can be assigned to students as needed. These accounts do not store personal data and can be reset upon request.

**Q: Does the X-ray Simulator support role-based access?**\
**A:** No, the X-ray Simulator operates on a simple user authentication model. A user either has access or does not—there are no distinct roles or permission levels within the system.

**Q: How is the X-ray Simulator installed and managed on institutional computers?**\
**A:** The software requires **administrator privileges** for installation on institutional PCs. Once installed, students can access it using the provided credentials.

**Q: How does the X-ray Simulator handle access control?**\
**A:** Access control is managed at the institutional level by assigning user credentials. the X-ray Simulator does not have internal user role-based permissions.

## **Data Handling & Security**

### **Does the X-ray Simulator store or process sensitive data (ePHI, PII, financial information)?**

No. The X-ray Simulator does not collect, store, or process electronic protected health information (ePHI), personally identifiable information (PII), or financial data. The system operates solely with "dump user" and simulated data.

#### **How does the X-ray Simulator ensure data security?**

* **Encryption**: All data transmissions related to authentication are encrypted using industry-standard protocols.
* **Access Management**: Institutions control user access through assigned credentials.
* **Data Governance**: No real patient data is processed or stored within the application.
* **Audit Logging**: The system maintains detailed logs to track user activity for compliance and security monitoring.

## **Hosting & Compliance**

### **Is the X-ray Simulator hosted externally or on-premises?**

The X-ray Simulator is a locally installed desktop application. It does require an internet connection to authenticate the user license upon login, but all other operations are performed offline.

### **What security measures are in place for the solution?**

* The X-ray Simulator does not store personal data, ensuring compliance with institutional privacy policies.
* All authentication requests are securely encrypted to prevent unauthorized access.
* The system logs user activity and performance data for troubleshooting and optimization.

## **Institutional Integration & Deployment**

### **Which institutions and departments use the X-ray Simulator?**

The X-ray Simulator is used by:

* Radiologic technology training programs

### **How does the X-ray Simulator integrate with an institution's existing infrastructure?**

* **User Authentication**: the X-ray Simulator requires login authentication but does not integrate with external identity management systems.
* **Standalone Operation**: The software does not require integration with Learning Management Systems (LMS) or hospital IT networks.
* **IT Support**: Dedicated support is available for onboarding and technical troubleshooting.

### **User Management**

The X-ray Simulator uses a **“dump” user** system where institutions are provided with a set of usernames and passwords (e.g., User X1 with password X1, and X2 with password X2, etc.). These users can be assigned to students as needed. This approach ensures:

* No personal user data is stored.
* Users can be reset upon request.
* Simple administration with no role-based access levels.

For further inquiries or technical support, please contact our IT security team at **support@vitasim.dk** or visit **support.vitasim.dk**.
