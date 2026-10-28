# Thrift Abaya WhatsApp AI Agent

A context-aware, multilingual (Hausa, Nigerian Pidgin, and English) WhatsApp Business automation agent built for 1-of-1 thrift abaya inventory management and automated price negotiation.

## Key Features

- **Northern Nigerian Code-Switching:** Understands and replies naturally in Hausa, Pidgin, and English using few-shot persona prompting from real vendor chat history.
- **1-of-1 Thrift Inventory Management:** Real-time stock lookup and item reservation (`Available` -> `Reserved`) powered by Google Sheets as a zero-cost ERP.
- **Bounded Haggling Engine:** Negotiates prices naturally with customers while strictly enforcing a hidden `Floor_Price_NGN`.
- **PII Data Scrubber:** Includes regex data-cleaning pipelines to strip customer phone numbers and bank details from raw WhatsApp training data. `.txt` exports.
