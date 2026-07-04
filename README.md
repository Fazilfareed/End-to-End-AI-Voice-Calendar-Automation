# \# 🎙️ End to End AI Voice Calendar Automation

# 

# An end-to-end AI-powered voice scheduling system that enables users to book appointments using natural conversation. The assistant checks calendar availability in real time, creates calendar events, and performs post-call workflow automation including logging booking details and sending confirmation emails.

# 

# \---

# 

# \# Overview

# 

# This project demonstrates how modern AI voice agents can automate scheduling workflows by integrating conversational AI with cloud productivity tools.

# 

# The assistant understands natural language, extracts structured scheduling information, validates availability, books appointments, and automatically performs follow-up tasks after the call.

# 

# \---

# 

# \# Features

# 

# \- 🎤 Natural voice conversations

# \- 🧠 AI-powered intent recognition

# \- 📅 Google Calendar availability checking

# \- ✅ Automatic event creation

# \- 📄 Structured output generation

# \- 🔗 n8n webhook integration

# \- 📊 Google Sheets booking log

# \- 📧 Gmail confirmation emails

# \- ⚡ End-to-end workflow automation

# 

# \---

# 

# \# System Architecture

# 

# !\[Architecture](architecture/architecture-diagram.png)

# 

# \---

# 

# \# Workflow

# 

# \## During the Call

# 

# 1\. User speaks with the AI assistant.

# 2\. Vapi converts speech into text.

# 3\. The LLM extracts scheduling information.

# 4\. Google Calendar is checked for availability.

# 5\. If available, the appointment is created.

# 6\. The assistant confirms the booking.

# 

# \---

# 

# \## After the Call

# 

# Once the conversation ends:

# 

# 1\. Vapi generates an End-of-Call Report.

# 2\. The report contains:

# &#x20;  - Transcript

# &#x20;  - Metadata

# &#x20;  - Structured Output

# 3\. Vapi sends the report to an n8n webhook.

# 4\. n8n extracts the booking details.

# 5\. Booking information is stored in Google Sheets.

# 6\. Gmail sends a confirmation email to the attendee.

# 

# \---

# 

# \# Architecture

# 

# ```text

# User

# &#x20;│

# &#x20;▼

# Vapi Voice Assistant

# &#x20;│

# &#x20;▼

# LLM

# &#x20;│

# &#x20;▼

# Google Calendar

# &#x20;│

# &#x20;├── Check Availability

# &#x20;└── Create Event

# &#x20;│

# &#x20;▼

# Booking Confirmation

# &#x20;│

# &#x20;▼

# End of Call

# &#x20;│

# &#x20;▼

# Webhook

# &#x20;│

# &#x20;▼

# n8n

# &#x20;├── Google Sheets

# &#x20;└── Gmail

# ```

# 

# \---

# 

# \# Tech Stack

# 

# | Technology | Purpose |

# |------------|---------|

# | Vapi | Voice AI Assistant |

# | OpenAI GPT | Natural Language Understanding |

# | Google Calendar | Availability \& Event Creation |

# | n8n | Workflow Automation |

# | Google Sheets | Booking Storage |

# | Gmail | Email Notifications |

# 

# \---

# 

# \# Sample Structured Output

# 

# ```json

# {

# &#x20; "title": "Project Meeting",

# &#x20; "date": "2026-07-05",

# &#x20; "time": "15:00",

# &#x20; "duration": 60,

# &#x20; "userEmail": "john@example.com",

# &#x20; "confirmed": true

# }

# ```

# 

# \---

# 

# \# Project Highlights

# 

# \- Real-time calendar availability checking

# \- AI-powered voice scheduling

# \- Automatic appointment booking

# \- End-of-call data processing

# \- Multi-service workflow automation

# \- Structured output extraction

# \- Cloud-based integrations

# 

# \---

# 

# \# Future Improvements

# 

# \- Outlook Calendar support

# \- Zoom \& Google Meet link generation

# \- SMS confirmations

# \- CRM integration

# \- Multi-language support

# \- RAG-based company knowledge

# \- Database support (MongoDB/PostgreSQL)

# \- Analytics Dashboard

# 

# \---

# 

# \# Author

# 

# \*\*Mohomad Fazil\*\*

# 

# Computer Science Undergraduate  

# AI Automation \& Full Stack Developer

# 

# LinkedIn: \*(Add your profile)\*

# 

# Portfolio: \*(Add your portfolio)\*

# 

# \---

