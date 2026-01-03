Problem Statement (Humanized)

Navigating large indoor spaces can be confusing and stressful, especially for first-time visitors, elderly individuals, and people with visual or cognitive impairments. Places like hospitals, airports, shopping malls, and university campuses often have complex layouts with multiple floors, departments, and corridors. Traditional signboards are often insufficient, difficult to understand, or poorly placed, leading to confusion and wasted time.

Unlike outdoor navigation, indoor environments do not support accurate GPS tracking, and most existing indoor navigation systems require costly hardware, specialized sensors, or pre-installed infrastructure. As a result, these solutions are not widely accessible or affordable. Additionally, most current systems lack natural interaction and fail to provide personalized, real-time guidance.

There is a need for an intelligent indoor navigation system that is easy to use, cost-effective, and accessible to all users. Such a system should understand natural human language, provide real-time guidance, and visually assist users within their surroundings. This project aims to address these challenges by developing an LLM-powered conversational AR indoor navigation system that enhances indoor mobility, improves accessibility, and supports smart building environments.
Abstract:Indoor navigation remains a major challenge in large and complex environments such as hospitals, shopping malls, airports, and university campuses. Unlike outdoor navigation, where GPS provides accurate guidance, indoor spaces lack reliable positioning systems and intuitive navigation support. Existing solutions often depend on expensive infrastructure, fixed sensors, or static maps, making them difficult to scale and inaccessible to many users.

This project proposes an LLM-Powered Conversational AR Indoor Navigation System that combines Large Language Models (LLMs) with Augmented Reality (AR) to deliver an intelligent, interactive, and user-friendly indoor navigation experience. The system allows users to communicate naturally through voice or text commands, such as asking for directions to a specific room or facility. The LLM understands the user’s intent, processes contextual information, and generates accurate navigation instructions.

Using AR technology, the system overlays real-time visual cues—such as arrows, labels, and markers—directly onto the user’s physical environment, guiding them step-by-step to their destination. The solution does not rely on GPS and can operate using indoor positioning methods such as QR codes or visual markers. This approach enhances accessibility, improves user confidence, and provides an efficient navigation solution for smart indoor environments.

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
