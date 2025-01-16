# Stageless Payload Lab

This repository contains my midterm lab report for the **Stageless Payload Lab** conducted during my cybersecurity coursework.

---

## Overview

This lab demonstrates the creation, testing, and execution of a stageless payload using **Metasploit Framework**. The goal was to understand how stageless payloads differ from staged payloads and how to generate, test, and execute them in a controlled environment.

---

## Steps Performed

1. **Environment Setup**:
   - Updated the system using `sudo apt-get update` and `sudo apt-get upgrade`.
   - Initialized the Metasploit database using `msfdb reinit`.
   - Verified the functionality of `msfconsole`.

2. **Payload Generation**:
   - Created a stageless payload named `stagelessfinalnew.exe`.
   - Verified the payload configuration and generation.

3. **Execution and Testing**:
   - Deployed the payload in a controlled virtual environment.
   - Monitored the payload's behavior and verified the expected results.

---

## Files Included

- **Lab Report**: [StagelessPayloadLabReport.pdf](./StagelessPayloadLabReport.pdf)
- **Screenshots** (if applicable):
  - `payload-creation.png`: Shows the payload creation process.
  - `msfconsole-working.png`: Verifies Metasploit console functionality.

---

## Tools Used

- **Metasploit Framework**: For generating and testing the stageless payload.
- **Linux Environment**: Host machine for Metasploit setup and testing.

---

## Lessons Learned

- How to generate stageless payloads and their use cases in cybersecurity.
- Basics of using Metasploit for payload creation, deployment, and testing.
- The importance of controlled environments for testing potentially harmful payloads.

---

## Disclaimer

This lab was conducted in a controlled and ethical environment for educational purposes only. The payloads and methods used are intended solely for academic exercises and must not be deployed on unauthorized systems.
