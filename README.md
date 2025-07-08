# 🧠 AI Agent for Fitness Studio Class Performance Analysis

## 🚀 Overview

This project demonstrates how to build a simple AI-powered data agent that analyzes class attendance data for a boutique fitness studio — like **RockBox** — and generates actionable insights in plain English.

We simulate real-world class data, clean it using PySpark, compute key trends (top classes, underperformance, coach impact), and finally use an LLM (e.g., GPT-4) to summarize findings as if you had a business analyst on your team.

---

## 🎯 Problem Statement

Many fitness studios collect class attendance and coach scheduling data, but rarely turn it into **actionable insights**. This results in:

- Missed opportunities to optimize class times
- Poor visibility into coach performance
- Difficulty understanding what’s driving retention or drop-offs
- Wasted time generating weekly or monthly reports manually

---

## 💡 Use Case: RockBox Studio

**Client Base**: ~250 active members  
**Class Schedule**:
- **Monday–Thursday**: 5 classes/day (3 morning, 2 evening)
- **Friday**: 2 classes (1 morning, 1 evening)
- **Saturday**: 2 morning classes
- **Sunday**: 1 morning class  

**Goal**: Help the owner understand:
- Which class times are underbooked
- What coaches have the highest attendance/retention
- Which days have peak engagement
- Seasonal patterns in class attendance

---

## ⚙️ What This Agent Does

1. **Simulates class attendance data**
2. **Cleans and processes it using PySpark**
3. **Analyzes trends across days, times, and coaches**
4. **Uses GPT (via OpenAI API) to generate natural language insights**
5. (Optional) Sends the weekly summary via email or Slack

---

## 📊 Sample Insights

> “Coach Alex’s 6:30 AM Monday class has the highest average attendance.”  
> “Wednesday evening classes have dropped by 18% this month — consider a format change.”  
> “Saturday morning has the best retention rate across the board.”

---

## 🛠️ Tech Stack

- **Python**
- **PySpark** for data cleaning & aggregation
- **OpenAI GPT API** for summary generation
- **GitHub Copilot** to assist with coding
- (Optional) **Streamlit** for dashboard UI

---

## 📁 Folder Structure

