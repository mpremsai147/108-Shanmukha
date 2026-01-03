1. Problem Statement

Indoor navigation in large buildings such as hospitals, malls, airports, universities, and offices is difficult due to:

Lack of GPS accuracy indoors

Complex layouts and poor signage

Limited accessibility for visually or cognitively impaired users

Existing solutions requiring costly hardware (beacons, sensors)

Users need an intelligent, interactive, and intuitive indoor navigation system that understands natural language queries and provides real-time AR guidance.

2. Proposed Solution

The proposed system uses:

Large Language Models (LLMs) for conversational interaction

Augmented Reality (AR) for visual navigation cues

Indoor positioning techniques (QR codes / Wi-Fi / BLE / visual markers)

Users can talk to the system like:

“Take me to the cardiology department”
“Where is the nearest washroom?”
“Guide me to Room 305”

The system responds with:

Conversational directions

AR arrows and markers overlaid on the real environment

Context-aware instructions (turn left, go straight, floor change)

3. Key Features

Conversational navigation using natural language

Real-time AR path visualization

Multi-floor indoor navigation

Accessibility support (voice guidance)

Context-aware responses (distance, obstacles)

Dynamic rerouting

Works without GPS
4. Technologies & Tools
AI & NLP

Python

LLMs: OpenAI API / LLaMA / Gemini

NLP libraries: LangChain, spaCy

AR & Frontend

Unity + ARCore (Android) / ARKit (iOS)

OR WebAR (Three.js + A-Frame)

HTML, CSS, JavaScript

Backend

FastAPI / Flask

REST APIs

Database

PostgreSQL / Firebase / MongoDB

Indoor map graph storage

Indoor Positioning

QR codes

BLE beacons (optional)

Visual marker tracking

5. Workflow

User opens AR app

Camera scans environment / QR code

User gives voice/text command

LLM understands intent & destination

Navigation engine calculates path

AR overlays directions in real time

Voice + visual guidance provided

6. Use Cases

Hospitals (patient & visitor navigation)

Shopping malls

Airports & railway stations

University campuses

Corporate offices

Smart buildings
