# restarant-reservation-bot
# 🍽️ Gen-AI Restaurant Table Booking Chatbot

A **Gen-AI powered restaurant table booking chatbot** built for **Gen-Z users**, focusing on fast responses, simple interaction, and night-only dining reservations.  
The chatbot uses **deterministic booking logic** combined with an **LLM (Google Gemini)** to deliver natural, human-like conversations.

---

## 📌 Project Description

This project implements a conversational restaurant chatbot that helps users:
- Book tables
- Check availability
- Cancel bookings using a unique booking ID
- Get a branch contact number for late arrival queries

The chatbot is optimized using **compressed data structures** to ensure **low latency** and **high performance**, making it suitable for hackathons and Gen-AI demos.

The project is developed and tested in **Google Colab**.

---

## 🎯 Problem Statement

Create a dining reservation chatbot using compressed menu data and availability rules to streamline table bookings with improved response times and a Gen-AI conversational experience.

---

## ✨ Features

- 🤖 Gen-AI powered responses using Google Gemini  
- 🪑 Table types:
  - Single (1 seat)
  - Couple (2 seats)
  - Family (4–8 seats)
- 🌙 Night-only booking system  
- ⏰ Time validation (5 PM – 11 PM)  
- 🆔 Unique booking ID generation  
- ❌ Booking cancellation using booking ID  
- 📞 Random branch contact number for late arrivals  
- 💰 Reservation fee logic (currently FREE, non-refundable)  
- ⚡ Fast, lightweight, and Gen-Z friendly  

---

## 🛠️ Tech Stack

- **Programming Language:** Python  
- **LLM:** Google Gemini (Generative AI)  
- **Platform:** Google Colab  
- **Libraries Used:**
  - `google-generativeai`
  - `uuid`
  - `random`

---

## 🏗️ System Architecture
## Overview
This project implements a lightweight, command-line–driven restaurant table booking chatbot using Python. The system is designed to simulate an automated reservation workflow by validating user inputs, enforcing business constraints, and generating structured booking confirmations.

The application optionally integrates with a Large Language Model (Gemini) to enhance response naturalness while maintaining deterministic booking logic.

---

## Problem Definition
Conventional reservation mechanisms often rely on manual intervention or static interfaces, which can introduce latency and operational inefficiencies. The objective of this project is to abstract the reservation workflow into a conversational system that enforces temporal constraints and table-type allocation through programmatic validation.

---

## System Description
The chatbot operates through a sequential interaction pipeline:
- Initialization of restaurant configuration parameters
- Dynamic presentation of available table categories
- User-driven input acquisition for reservation metadata
- Validation of booking time against operational hours
- Generation of a consolidated reservation summary

The system is architected using modular Python functions to promote clarity, extensibility, and controlled execution flow.

---

## Functional Capabilities
- Command-line conversational interface
- Predefined table classification (Single, Couple, Family)
- Enforcement of night-only operational window (17:00–23:00)
- Deterministic input validation and error handling
- Reservation confirmation generation
- Optional LLM-backed response abstraction

---

## Technology Stack
- Python 3.x  
- Google Colab execution environment  
- Gemini API (optional enhancement layer)

