# 🛡️ API Security Risk Analysis Report

## 📌 Overview

This project presents a security assessment of a public API using read-only testing techniques. The analysis identifies common API security risks and demonstrates how vulnerabilities can impact real-world systems.

## 🎯 Objective

* Identify API security risks
* Analyze authentication and access control
* Evaluate data exposure
* Provide remediation recommendations

## 🔍 API Tested

Base URL: https://jsonplaceholder.typicode.com

Endpoints:

* `/users`
* `/users/1`
* `/posts`

## ⚠️ Key Findings

* No Authentication (High Risk)
* Excessive Data Exposure (Medium Risk)
* Lack of Rate Limiting (Medium Risk)
* Broken Access Control / BOLA (Medium Risk)

## 🛠️ Tools Used

* Postman
* Browser DevTools

## 📸 Evidence

Screenshots are available in the `/screenshots` folder.

## 📄 Report

Full report available here: [Download Report](report.pdf)

## ⚖️ Disclaimer

This assessment was conducted on a public test API for educational purposes only. No exploitation or harmful activity was performed.
