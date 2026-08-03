#  Clinic Scheduler – Salesforce CRM

A Salesforce-powered clinic management system built to help **Tier-3 and local hospitals and clinics** replace paper-based record keeping with a secure and organized digital solution.

The application brings patient information, doctor records, appointment scheduling, and medical records into one centralized system, helping clinic staff manage everyday operations more efficiently.

---

##  Project Objective

The objective of this project is to build a simple and reliable clinic management solution for Tier-3 and local healthcare providers using Salesforce CRM.

It aims to reduce dependency on handwritten records while improving patient information management, appointment scheduling, and access to medical history.

---

##  Problem Statement

Many local hospitals and clinics still rely on handwritten records to manage patient information, appointments, prescriptions, and medical histories.

This manual approach can lead to:

* Data loss or misplacement
* Errors while recording information
* Difficulty retrieving patient history
* Inefficient appointment management
* Delays during follow-up consultations

The project addresses these challenges by digitizing important clinic operations through Salesforce CRM.


##  Solution

Clinic Scheduler centralizes patient, doctor, appointment, and medical record management into a single Salesforce application.

It enables local clinics to digitize their everyday operations, reduce paperwork, and improve the accuracy and accessibility of important healthcare information.

The application allows clinic staff to manage:

* Patient information
* Doctor profiles
* Appointment scheduling
* Medical records


##  Features

###  Patient Management

* Store patient information digitally
* Maintain patient contact details
* Record basic patient information
* Access patient-related records from one system

###  Doctor Management

* Create and manage doctor profiles
* Maintain doctor information
* Connect doctors with appointment records
* Keep doctor data separate from patient information

###  Appointment Scheduling

* Create and manage appointments
* Support virtual and in-person consultation modes
* Link an appointment with a patient
* Link an appointment with a doctor
* Maintain appointment information digitally

  Medical Records

* Maintain patient medical records
* Store consultation-related information
* Connect medical records with patient information
* Improve access to records during future consultations


  Security and Access Control

* System Administrator profile
* Standard User profile
* Record-level security
* Field-level security
* Login restrictions
* Permission-based access to clinic information


##  Data Model

The application is organized using four main Salesforce custom objects:

* Patient
* Doctor
* Appointment
* Medical Record

Relationships between the objects are created using:

* Lookup Relationships
* Master-Detail Relationships

These relationships allow appointments to be connected with the appropriate patient and doctor while keeping the clinic's data organized.

---

##  Basic System Architecture

```text
Patient
   │
   ├──────────────┐
   │              │
   ▼              ▼
Appointment   Medical Record
   │
   ▼
Doctor
```

The patient and doctor records are connected through appointments, while medical records are maintained for patient-related healthcare information.

---

##  Workflow

1. A patient contacts the hospital or clinic to request an appointment.
2. Clinic staff collects the patient's basic information.
3. The patient selects a doctor.
4. The consultation mode is selected as virtual or in-person.
5. Clinic staff creates the appointment in the Salesforce application.
6. The appointment is connected with the selected patient and doctor.
7. The clinic confirms the appointment with the patient.
8. Medical information can be maintained for future consultations.

---

##  User Interface

The application interface was built using:

* Salesforce Lightning Experience
* Salesforce Lightning App Builder
* Custom object tabs
* Salesforce record pages

The interface separates patients, doctors, appointments, and medical records into different sections to make navigation easier for clinic staff.

---

## Data Management

The project includes the following data-management practices:

* Salesforce cloud storage
* Weekly data backups
* Permission-based data access
* Data integrity management

These practices help reduce accidental data loss and improve the reliability of clinic records.

---

##  Benefits

* Reduces dependency on handwritten records
* Improves patient record organization
* Reduces manual recording errors
* Simplifies appointment scheduling
* Makes patient history easier to retrieve
* Connects patients, doctors, and appointments
* Improves access to medical records
* Supports virtual and in-person consultation records
* Provides secure cloud-based data storage
* Improves the everyday workflow of local clinics

---

## 🛠️ Technologies Used

* Salesforce CRM
* Salesforce Lightning Experience
* Salesforce Lightning App Builder
* Salesforce Custom Objects
* Lookup Relationships
* Master-Detail Relationships
* Salesforce Profiles
* Field-Level Security
* Record-Level Security

---

##  Demovideo - [Click here to watch Demo Video](https://drive.google.com/file/d/1_R9lOz8Xt294dDAYUXcO5jhBqX9w0FZe/view)

The video demonstrates how the Salesforce Clinic Scheduler application was created and configured.

---

##  Future Enhancements

* Analytics dashboard for clinic data
* Real-time appointment updates
* External hospital-system integration
* Integration with laboratories and pharmacies
* External database connectivity
* Improved notification system
* API monitoring and error handling
* Integration with task-management tools
* Secure external authentication using OAuth

---

##  Learning Outcomes

Through this project, we gained practical experience with:

* Salesforce CRM application development
* Creating custom objects
* Defining custom fields
* Data modeling
* Lookup and Master-Detail Relationships
* Creating Salesforce profiles
* Managing user permissions
* Configuring record-level security
* Using Salesforce Lightning App Builder
* Designing record pages and object tabs
* Managing clinic data in Salesforce
* Understanding CRM-based healthcare workflows

---

##  License

This project was developed as a Salesforce learning project for educational purposes.
