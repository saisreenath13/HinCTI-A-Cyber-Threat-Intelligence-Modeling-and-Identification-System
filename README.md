Hin-CTI
A Cyber Threat Intelligence Modeling and Identification System Based on Heterogeneous Information Network (HIN)
📌 Overview

Hin-CTI is a Cyber Threat Intelligence (CTI) modeling and threat identification system that leverages a Heterogeneous Information Network (HIN) to model complex cyber threat infrastructure relationships and identify threat types using a Heterogeneous Graph Convolutional Network (GCN).

The system integrates multiple cyber threat indicators such as:

IP Addresses

Domain Names

Malware Hashes

Email Addresses

URLs

By modeling their semantic relationships, Hin-CTI enhances threat detection accuracy and supports early threat warning.

🚀 Problem Statement

Traditional CTI systems face two major challenges:

Limited labeled threat data due to high manual labeling cost.

Inability to model higher-level semantic relationships between different cyber entities.

Most existing systems rely on:

Homogeneous networks

Simple correlation methods

Fingerprint-based similarity

These approaches fail to capture deep structural relationships among cyber threat entities.

💡 Proposed Solution

Hin-CTI addresses these challenges by:

Modeling Cyber Threat Intelligence using a Heterogeneous Information Network (HIN)

Introducing a Meta-Path and Meta-Graph Instance-based Threat Infrastructure Similarity (MIIS) measure

Applying a Heterogeneous Graph Convolutional Network (GCN) for threat type classification

Using Hierarchical Regularization to reduce overfitting

This enables accurate threat classification even with partial or incomplete labeled data.

🏗 System Architecture

The system consists of the following modules:

1️⃣ Data Collection

Threat intelligence feeds

IDS logs

Malware databases

Network logs

2️⃣ Data Preprocessing

Data cleaning

Normalization

Structuring threat indicators

3️⃣ HIN Construction

Node types: IP, Domain, URL, Hash, Email

Relationship modeling (resolves-to, communicates-with, etc.)

4️⃣ Meta-Path & Meta-Graph Extraction

Higher-level semantic pattern discovery

Structural similarity computation (MIIS)

5️⃣ GCN-Based Threat Classification

Graph Convolutional Network training

Threat type prediction

Confidence score generation

6️⃣ Threat Analysis Interface

Visualization

Query-based analysis

Threat type results display

🛠️ Technology Stack
Backend

Java (J2EE – JSP & Servlets)

JDBC

Apache Tomcat

Frontend

HTML

CSS

JavaScript

Database

MySQL

Architecture

Client-Server Model

Three-Tier Architecture

Heterogeneous Information Network

📊 Key Features

HIN-based CTI modeling

MIIS similarity computation

Heterogeneous GCN-based threat classification

Admin & User authentication system

Dataset upload and threat detection

Threat type visualization

Support for limited labeled data

🧠 Threat Types Identified

The system can classify infrastructure nodes into categories such as:

Malware Activity

Spam URLs

Brute Force Login Attacks

Botnet Node Activity

Benign Entities

🔐 Advantages

Captures complex semantic relationships

Works with incomplete labeled data

Reduces analyst workload

Improves classification performance over traditional methods

Scalable and extendable architecture

💻 Hardware & Software Requirements
Hardware

Intel i3/i5/i7 Processor

4GB RAM (Minimum)

256GB Storage

Software

Windows 7/8/10/11

Apache Tomcat

MySQL

JDK

Web Browser

📈 Results

Experimental results on real-world datasets demonstrate:

Improved threat classification accuracy

Better performance compared to baseline models

Reduced overfitting using hierarchical regularization

📚 Academic Context

This project was developed as a Major Project for:

Bachelor of Technology (B.Tech)
Computer Science and Engineering (AI & ML)

👥 Contributors

T. Sai Sreenath
📌 Future Enhancements

Real-time streaming threat analysis

Integration with SIEM platforms

Deep learning-based threat behavior modeling

Cloud deployment

📜 License

This project is developed for academic and research purposes.
