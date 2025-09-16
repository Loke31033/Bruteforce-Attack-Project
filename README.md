# Brute-Force Attack Lab — Simulating Web & SSH Brute-Force Attacks

**Author:** LOKESHWAR V
**Affiliation:** ETHICAL HACKING INTERN (INLIGHN TECH)  
**Date:** 2025-09-16

---

## 🔍 Project Overview
This repository contains the lab work for simulating and analyzing brute-force attacks against vulnerable web login forms and SSH services using **Burp Suite (Intruder)** and **Hydra**. The goal is to demonstrate how weak authentication can be exploited and to suggest practical mitigations.

> **Important:** All tests were performed in a controlled lab environment on machines I own / have explicit permission to test. Do **NOT** run these techniques against systems you don't own or have authorization to test.

---

## 🧰 Tools & Requirements
- Kali Linux (or equivalent)
- Burp Suite (Community or Pro)
- THC Hydra
- Target VM with bWAPP or DVWA installed
- SSH server running on target (for SSH lab)
- Small username/password lists (e.g., `lists/usernames.txt`, `lists/passwords.txt`)

---

## 🛠 Lab Setup
1. Start attacker (Kali) and target VM.  
   - Replace placeholders: `ATTACKER_IP`, `TARGET_IP`.
2. Ensure web app r
