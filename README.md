# AI-Powered Messenger Chatbot for Real-Time Sales and Customer Interaction
I built an AI chatbot that automates customer interaction for my mom’s online clothing (saree) business on Facebook Messenger. It can answer product queries, handle bargaining, track inventory, and detect serious vs time-wasting customers—demonstrating a practical application of AI, NLP, and full-stack development.

**Automating Customer Interaction, Inventory Tracking, and Smart Bargaining**

---

## Project Summary

I built an AI chatbot that automates customer interaction for my mom’s saree business on Facebook Messenger.  
The bot handles product queries, manages pricing negotiations within predefined margins, tracks inventory in real-time, and detects serious vs casual customers.  

This project demonstrates practical application of **AI, NLP, and full-stack development** to solve a real-world business challenge.

---

## Key Features

- **Bilingual Messaging:** Supports mixed Bengali-English conversations with transliteration  
- **Smart Bargaining:** Automatically handles price negotiations within defined limits  
- **Concurrent Conversations:** Can respond to multiple customers simultaneously  
- **Inventory Lookup:** Integrates with Google Sheets for live stock and pricing  
- **Analytics & Logging:** Tracks customer interactions, sales leads, and engagement metrics  

---

## Tech Stack / Skills Demonstrated

- Python, Node.js, or your chosen backend language  
- Facebook Messenger API / Meta Business API  
- Google Sheets API for inventory and pricing  
- NLP for language handling and intent detection  
- Multi-threading for simultaneous conversation handling  

---

## System Architecture

```text
Customer Message
       |
       v
   NLP Engine
       |
       v
 Decision Logic (pricing, response selection)
       |
       v
    Messenger API
       |
       v
 Customer receives response
