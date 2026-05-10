# Gypsum Board Production Fault Diagnosis System
A structured knowledge base and CLI diagnostic tool for gypsum board production line troubleshooting, deployed as an offline-capable PWA for factory-floor use in resource-constrained environments.
## Problem
- 94 recorded production faults buried in 12 monthly reports (Chinese), inaccessible to local technicians
- Knowledge lost with rotating expat staff
- Frequent power outages & limited internet in Sub-Saharan Africa
## Solution
- Structured 94 faults into symptom→root cause→action quadruples (JSON)
- Python CLI tool with weighted keyword matching in Chinese & English
- Offline PWA via Firebase Hosting + Service Worker
## Tech Stack
Python · JSON · Firebase · PWA · Service Worker · HTML/CSS
## Usage
python fault_diagnosis_cli.py --query "板边黄"
## Screenshots
<img width="1007" height="920" alt="PixPin_2026-05-10_19-46-18" src="https://github.com/user-attachments/assets/ff9b88aa-1569-421c-940a-c49b969ec91b" />
<img width="969" height="1206" alt="PixPin_2026-05-10_19-49-53" src="https://github.com/user-attachments/assets/e67e8df2-d16f-4e48-a1ca-bb4800599a0b" />
<img width="981" height="799" alt="PixPin_2026-05-10_19-51-59" src="https://github.com/user-attachments/assets/d410534d-ef34-4536-a156-811e78ffdcc1" />
## Author
Xintao Shi — Process Engineer, Tanzania
