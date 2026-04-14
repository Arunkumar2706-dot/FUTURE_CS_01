# FUTURE_CS_01
# 🔐 Vulnerability Assessment Report

## 📌 Overview

This repository contains a **professional vulnerability assessment report** conducted on a publicly accessible web application.

The goal of this assessment was to identify common security weaknesses using **non-intrusive, read-only techniques** and present the findings in a clear, business-friendly format.

---

## 🌐 Target Website

* Application: OWASP Juice Shop
* URL: https://juice-shop.herokuapp.com

---

## 🎯 Scope

The assessment included:

* Public-facing web pages only
* Passive vulnerability scanning
* Security header and configuration analysis
* No login or authentication testing
* No exploitation or intrusive attacks

---

## 🛠️ Tools Used

* Nmap – Network scanning and port analysis
* OWASP ZAP – Passive vulnerability scanning
* Browser DevTools – Header and cookie inspection

---

## 🔍 Key Findings

* Missing security headers (CSP, HSTS)
* CORS misconfiguration
* Information disclosure (comments, timestamps)
* Cache-control misconfiguration
* No high-risk vulnerabilities identified

---

## 📊 Risk Summary

* Medium Risk: 3
* Low Risk: 3
* Informational: 1
* High Risk: 0


## ⚠️ Disclaimer

This assessment was conducted for **educational purposes only** using passive techniques.
No exploitation or harmful activity was performed.

---

## 👨‍💻 Author

Security Analyst (Student Project)
