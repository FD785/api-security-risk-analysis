# 🛡️ API Security Risk Analysis Report

## 📌 Overview

This project presents a professional API security assessment conducted on a public REST API using ethical, read-only testing techniques. The goal is to identify common API security risks and demonstrate real-world vulnerability analysis.

## 🎯 Objective

* Analyze API endpoints and behavior
* Identify security risks and misconfigurations
* Evaluate authentication and access control
* Provide actionable remediation strategies

## 🔍 Target API

**Base URL:** https://jsonplaceholder.typicode.com

**Endpoints Tested:**

* `/users`
* `/users/1`
* `/posts`

## ⚠️ Key Findings

* 🔴 No Authentication (High Risk)
* 🟠 Excessive Data Exposure (Medium Risk)
* 🟠 Lack of Rate Limiting (Medium Risk)
* 🟠 Broken Access Control (BOLA / IDOR)

## 🛠️ Tools Used

* Postman (API testing)
* Browser DevTools

## 📸 Evidence

Screenshots demonstrating the findings are available in the `/screenshots` folder.

## 📄 Report


Full report available here: [Download Report](report.pdf)

## ⚖️ Disclaimer

This assessment was conducted on a public test API for educational purposes only. No exploitation or harmful activity was performed.
