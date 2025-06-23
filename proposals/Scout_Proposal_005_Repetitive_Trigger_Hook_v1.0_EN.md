# Scout Proposal #005 – Repetitive Trigger Hook Response Framework

> **Proposal Date**: 2025-06-16  
> **Author**: Scout (XAH DAO Participant)  
> **Objective**: A structural proposal for maintaining order in the face of increasing repetitive transactions

---

## 🎯 Purpose of the Proposal

To ensure order and user trust in an XRPL/RLUSD environment where repetitive transactions are increasing,  
this proposal presents a system that relies on scout-based judgment rather than automatic blocking.

---

## 🧩 4-Stage Structural Overview

| Stage | Description | Entity |
|-------|-------------|--------|
| Stage 1 | Detect repetitive triggers | Hook |
| Stage 2 | Classify for monitoring | Scout |
| Stage 3 | Scout voting and referral | Scout group |
| Stage 4 | Analysis and decision | Evaluator committee |

---

## 🔸 Stage 1 – Repetitive Trigger Detection

### 🚨 Detection Conditions
Hooks will automatically log events when any of the following are met:
1. Five or more identical payments to the same recipient
2. Ten or more payments of varying amounts (between 0.01 and 10 RLUSD)
3. Three or more round-trip transactions between the same addresses within 10 minutes
4. More than 30 receipts by the same recipient address

### ⏱ Time Frames
- Basic detection window: 10 minutes
- Additional trigger: 20 or more transactions within 1 hour

---

## 🔸 Stage 2 – Scout Monitoring Registration

### 📌 Classification Checklist
Scouts must check at least one of the following when marking an address for monitoring:

| Item | Description |
|------|-------------|
| 🔲 Suspected structural repetition | Signs of automation |
| 🔲 Suspected DAO reward farming | Repetitive Hook patterns |
| 🔲 Recipient bias | Overconcentration to one wallet |
| 🔲 Abnormal inflow | Anonymous or cross-exchange flows |

### 🔗 Sharing Method
- Automatically shared with 3 randomly selected scouts in the top 10% trust rating
- Trust score is based on activity history + evaluator feedback

---

## 🔸 Stage 3 – Scout Voting & Referral

- If 2 or more scouts flag the event as “suspicious,” a vote is initiated
- If 3 or more scouts agree → forwarded to evaluators

---

## 🔸 Stage 4 – Evaluator Committee Analysis

### Based on a 3-person Evaluator Consensus System

| Verdict | Action |
|--------|--------|
| ✅ Legitimate | Remove from monitoring |
| ⚠️ Borderline | Keep record + re-evaluate later |
| ❌ Malicious | Request Hook restriction + DAO-wide warning |

---

## 🧠 Core Design Philosophy

- Hooks focus on **detection and logging**  
- Decisions are made by **DAO's internal judgment system**  
- Scouts analyze structure, evaluators interpret patterns, designers adjust the system  
- **Decentralized order**: machines detect, people judge, structures remember the flow

---

> ⚠️ This document is a **preliminary draft** created through the designer's internal exploration and reflective process before formal DAO structure proposal.  
> It is **not an official DAO document**, but may serve as a reference during future structural standardization.

