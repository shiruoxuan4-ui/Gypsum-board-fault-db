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
## Author
Xintao Shi — Process Engineer, Tanzania
