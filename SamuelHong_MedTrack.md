# MedTrack

## Project Abstract

MedTrack is an original project proposal. The purpose of the project will be to help patients stay compliant with their medication regimens and allow doctors to keep track of a patient's response to a medication. The project will contain two major parts: a mobile application that will be used by the patient, and a website that will be used by the doctor. When the doctor prescribes the patient a medication, he enters the medication into the website, along with the duration, timing, and frequency that it must be taken by the patient. A new medication regimen can also be initiated by the patient. The patient will then receive periodic reminders on their smartphone during the day when it is time to take the medication. When the patient interacts with the app, it will prompt the user to give any side effects along with their severity and/or health indicators (such as blood pressure) via a drop-down menu. When the patient returns to the doctor's office, the doctor can use the website to check the patient's health indicators and use the information to inform care decisions going forward.

## Project Relevance

This project will involve several educational goals of this course. These are some of the programming principles that will be used to develop the project:
 * Object Oriented Design: The mobile application will be written in Java and be reliant on OOP principles.
 * Remote Procedure Calls: The project will use the client-server model to handle data inputs from the patient.
 * Unified Modeling Language: The project will be documented via. UML in order to convey its structure to interested parties.
 * Debugging: Self explanatory.
 * Graphic User Interface: The project will rely on a front-facing mobile application for the patient and a web interface for the doctor.
 * Access to Database: A server database will be required in order to store and retrieve all relevant information.
 
On a broader level, this project fulfills an important function in the field of healthcare that is ripe for development. In addition to the above skills, this project will be developed by a small team using version control, testing, and issue tracking in order to fulfill the requirements necessary to develop a useful end product. The project will be open source.

## Conceptual Design

MedTrack will be developed as an open-source original project. I am proposing Android as the patient app development platform. The team will develop a login screen for the user to access the application. We will develop a website which will allow the doctor to add the medication information (e.g. the blood pressure medication Lisinopril), which will be stored in our database server. A notification system will be developed to give the user reminders to take a medication (e.g. by vibrating the phone), stopping after about three attempts. When a patient responds to the notification, a pop-up will appear to query them about side effects, severity, and important indicators. This information will then be sent to the server. The website will then allow the doctor to navigate to the patient's health profile, where charts containing the relevant information over time will be constructed.

## Background

This as an original project proposal. The cencept for this project was solicited from a healthcare provider.

## Required Resources

 * Software: Android Studio, HTML editor.
 * Hardware: An external server, such as a VPS
 * Languages: Java, XML, HTML, CSS. As needed: JavaScript, SQL
 * Personnel: A small team of developers
