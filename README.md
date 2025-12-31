# Zoom RTMS Transcription & Translation App

## This repository contains a Zoom App that uses Zoom Real-Time Media Streaming (RTMS) to process live meeting audio and provide real-time transcription and optional translation using Azure Speech Services.

## 🚀 Features

1. Real-time audio streaming from Zoom meetings via RTMS

2. Live speech-to-text transcription using Azure Speech-to-Text

3. Optional real-time language translation

4. Secure OAuth 2.0 authentication with Zoom

5. Webhook verification for Zoom event notifications

6. No permanent storage of audio or transcripts

## 🧱 Architecture Overview

1. User starts a Zoom meeting

2. Zoom streams live audio via RTMS

3. Node.js backend receives audio over secure WebSocket

4. Audio is forwarded to Azure Speech Services

5. Transcribed (and translated) text is returned in real time

6. All data is processed in-memory and discarded after use

## 🔐 Security & Privacy

1. All communication uses HTTPS / Secure WebSockets (TLS)

2. OAuth 2.0 is used for authorization

3. Webhook requests are cryptographically verified

4. Audio and transcription data are not stored

5. Data is processed only during the live session

## 📄 Documentation

1. Privacy Policy: See /privacy.html

2. Terms of Use: See /terms.html

3. Support: See /support.html

4. User Guide: See /docs.html

## 🧩 Technology Stack

1. Node.js (Express)

2. Zoom RTMS & Webhooks

3. Azure Speech-to-Text

4. Azure Translator

5. ngrok (development only)

