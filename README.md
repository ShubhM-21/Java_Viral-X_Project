# **ViralX Disease Management System**

## **📄 Overview**
The **ViralX Disease Management System** is a comprehensive Java-based application designed to manage and monitor viral disease outbreaks. This system helps track patients, symptoms, hospital admissions, and regional statistics while providing detailed insights into fatality rates and infection trends. The project incorporates **Object-Oriented Programming (OOP)** principles, ensuring scalability and modularity.

---

## **🛠 Features**
- **Patient Management**:  
  - Track patients' details, symptoms, test results, and contacts.
  - Identify high-risk contacts and manage patient admission status.  

- **Hospital Management**:  
  - Assign infected patients to hospitals with available capacity.  
  - Maintain hospital-level statistics such as total admitted and infected patients.  

- **Regional Data Management**:  
  - Monitor patient data at state and country levels.  
  - Calculate total patients, infection rates, recovery rates, and fatality rates.  

- **Data Export**:  
  - Export detailed reports to CSV and text files, including state and country-level data.  

- **Interactive User Input**:  
  - Add new patients with symptoms and contacts through the console interface.  

---

## **📂 Project Structure**
The project is organized into three main packages for modularity and clarity:  

1. **Location Package**:  
   - Manages geographic entities (Country, State, and Hospital).  
   - Implements an interface (`Display`) and abstract class (`Region`) to handle location-specific data.  

2. **Subject Package**:  
   - Manages patient data, symptoms, and test results.  
   - Tracks high-risk contacts and patient admission status.  

3. **Utility Package**:  
   - Provides helper classes to manage data input and processing.  
   - Reads patient and hospital data from input files for system initialization.  

---

## **🔑 Key Classes**
- **Country, State, and Hospital** (Location Package):  
  - Track patients and infection data for their respective levels.  
  - Export statistics to external files.  

- **Patient and Contact** (Subject Package):  
  - Manage patient symptoms, contacts, and test results.  
  - Include logic for determining infection status based on severity.  

- **all_data** (Utility Package):  
  - Reads input files (`input.txt` and `hospital.txt`) to create patients, states, and hospitals.  

---

## **📊 How It Works**
1. **Input Data**:  
   - Patient data is read from `input.txt`, which includes symptoms, severity, and contact information.  
   - Hospital data is read from `hospital.txt`, linking hospitals to specific states.  

2. **Process Flow**:  
   - Patients are assigned to hospitals based on availability.  
   - Infection and fatality statistics are calculated for hospitals, states, and the country.  

3. **Output**:  
   - Display patient and hospital details in the console.  
   - Generate CSV and text reports for regional statistics.

---

## **🛠 Technologies Used**
- **Java**: For object-oriented programming and system implementation.  
- **File Handling**: To read input files and export reports.  
- **CSV and Text Reporting**: To summarize infection and fatality data.  

---

## **🚀 How to Run**
1. Clone the repository to your local system:
   ```bash
   git clone <repository-link>
   ```
2. Compile and run the `Main.java` file using any Java IDE or the command line:
   ```bash
   javac Main.java
   java Main
   ```
3. Follow the console prompts to add new patients or view system statistics.
---
Let me know if you'd like any modifications or additions! 😊
