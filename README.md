# Zoom RTMS Transcription & Translation App

## This repository contains a Zoom App that uses Zoom Real-Time Media Streaming (RTMS) to process live meeting audio and provide real-time transcription and optional translation using Azure Speech Services.

🚀 Features

Real-time audio streaming from Zoom meetings via RTMS

Live speech-to-text transcription using Azure Speech-to-Text

Optional real-time language translation

Secure OAuth 2.0 authentication with Zoom

Webhook verification for Zoom event notifications

No permanent storage of audio or transcripts

🧱 Architecture Overview

User starts a Zoom meeting

Zoom streams live audio via RTMS

Node.js backend receives audio over secure WebSocket

Audio is forwarded to Azure Speech Services

Transcribed (and translated) text is returned in real time

All data is processed in-memory and discarded after use

🔐 Security & Privacy

All communication uses HTTPS / Secure WebSockets (TLS)

OAuth 2.0 is used for authorization

Webhook requests are cryptographically verified

Audio and transcription data are not stored

Data is processed only during the live session

📄 Documentation

Privacy Policy: See /privacy.html

Terms of Use: See /terms.html

Support: See /support.html

User Guide: See /docs.html

🧩 Technology Stack

Node.js (Express)

Zoom RTMS & Webhooks

Azure Speech-to-Text

Azure Translator

ngrok (development only)

📬 Support

For questions or support, contact:
Email: torsten@zhineng-qigong-students-hub.com

