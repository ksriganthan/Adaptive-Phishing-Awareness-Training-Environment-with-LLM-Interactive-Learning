# An Adaptive Phishing Awareness Training Environment Based on LLMs and Interactive Learning

# PhishingChatbot – CyberPhil (English)
AI-based Phishing Awareness Training (Proof of Concept → Research Prototype)

PhishingChatbot (**CyberPhil**) is an **interactive phishing awareness training system** developed as part of an FHNW research and coursework project.  
The project demonstrates how **chatbots and (later) Large Language Models (LLMs)** can be used to simulate realistic phishing scenarios and actively train users to recognize and respond to social-engineering attacks.

This repository represents the **technical Proof of Concept (PoC)** that bridges **academic research** and **practical implementation**.

---

## Why This Project Exists

Phishing remains one of the most effective cybersecurity attack vectors because it targets the **human factor** rather than technical vulnerabilities.  
Traditional awareness training is often **passive, static, and non-interactive**, which limits learning effectiveness.

This project addresses that gap by:
- simulating **realistic phishing scenarios**
- embedding a chatbot directly into a web environment
- providing **immediate, contextual feedback**
- supporting **interactive learning instead of passive instruction**

The PoC validates the feasibility of chatbot-based phishing simulations and serves as a foundation for adaptive, AI-driven training systems.

---

## Research Context & Publication

This project was developed in the context of academic research at **FHNW** and evolved beyond coursework into a **peer-reviewed research contribution**.

### Academic Paper (Published)

**Title:**  
*An Adaptive Phishing Awareness Training Environment Based on LLMs and Interactive Learning*

**Publisher:** IEEE  
**Conference:** 2025 IEEE 9th Forum on Research and Technologies for Society and Industry (RTSI)  
**Authors:** Kapischan Sriganthan, Felix Härer  

The paper presents:
- the theoretical foundation
- a structured literature review
- the training concept
- the chatbot architecture
- and the evaluation of this Proof of Concept

The PoC implemented in this repository directly supports and demonstrates the concepts discussed in the paper.

IEEE Xplore: https://ieeexplore.ieee.org/document/11212360
---

## Project Evolution (Versions)

This project exists in **three evolutionary stages**:

### Version 1 – Initial Proof of Concept
- Rule-based chatbot (intents.json)
- Flask backend
- Simulated website environment
- Static phishing scenarios
- Focus: **feasibility & interaction flow**

📌 Archived in the private repository `ksriganthan/phishingchatbot`. Available on request.

---

### Version 2 – Improved Design (Paper Pre-Submission Version)
- UI/UX improvements
- Refined phishing scenarios
- Better visual integration of the chatbot
- Adapted for academic paper submission and demonstration

📌 Archived in the private repository `ksriganthan/tobit_poc`. Available on request.

---

### Version 3 – LLM-Based Research Prototype (Conference Version)
- Conceptual integration of **Large Language Models**
- Adaptive feedback and contextual responses
- Research-grade prototype for conference presentation
- Focus: **interactive learning & adaptivity**

https://github.com/fhaer/adaptive-phishing-awareness-training.git
---

## What This Repository Contains

This repository contains the **first functional Proof of Concept**, intentionally kept simple and transparent to demonstrate:

- chatbot-website integration
- phishing simulation logic
- user interaction and feedback flow
- architectural feasibility without LLM dependency

The chatbot **CyberPhil** acts as:
- a guide
- a trainer
- and a feedback mechanism during phishing simulations

---

## Features

- Interactive phishing simulations
- Embedded chatbot (CyberPhil)
- Immediate feedback on user actions
- Rule-based intent handling via `intents.json`
- Web-based UI (HTML, CSS, JavaScript)
- Flask backend
- Lightweight and reproducible PoC architecture

---

## Technologies Used

- Python 3.8+
- Flask
- NLTK
- Torch (foundational ML support)
- HTML / CSS / JavaScript
- Qwen 2.5 7B (Ollama)

---

# Eine adaptive Phishing-Awareness-Trainingsumgebung basierend auf LLMs und interaktivem Lernen

# PhishingChatbot – CyberPhil (Deutsch)
KI-basiertes Phishing-Awareness-Training (Proof of Concept → Forschungsprototyp)

PhishingChatbot (**CyberPhil**) ist ein **interaktives Phishing-Awareness-Trainingssystem**, das im Rahmen eines FHNW-Forschungs- und Studienprojekts entwickelt wurde.  
Das Projekt zeigt, wie **Chatbots und (später) Large Language Models (LLMs)** zur Simulation realistischer Phishing-Szenarien eingesetzt werden können, um Benutzer aktiv zu trainieren, Social-Engineering-Angriffe zu erkennen und darauf zu reagieren.

Dieses Repository repräsentiert den **technischen Proof of Concept (PoC)**, der **akademische Forschung** und **praktische Umsetzung** verbindet.

---

## Warum dieses Projekt existiert

Phishing bleibt einer der effektivsten Angriffsvektoren im Bereich Cybersicherheit, weil es den **menschlichen Faktor** und nicht technische Schwachstellen anvisiert.  
Traditionelles Awareness-Training ist oft **passiv, statisch und nicht-interaktiv**, was die Lerneffektivität einschränkt.

Dieses Projekt schließt diese Lücke durch:
- Simulation **realistischer Phishing-Szenarien**
- Einbettung eines Chatbots direkt in eine Webumgebung
- Bereitstellung von **unmittelbarem, kontextuellem Feedback**
- Unterstützung **interaktiven Lernens anstelle passiver Unterweisung**

Der PoC validiert die Machbarkeit chatbot-basierter Phishing-Simulationen und dient als Grundlage für adaptive, KI-gesteuerte Trainingssysteme.

---

## Forschungskontext & Publikation

Dieses Projekt wurde im Kontext akademischer Forschung an der **FHNW** entwickelt und entwickelte sich über Studienarbeiten hinaus zu einem **peer-reviewten Forschungsbeitrag**.

### Wissenschaftliche Veröffentlichung (Published)

**Titel:**  
*An Adaptive Phishing Awareness Training Environment Based on LLMs and Interactive Learning*

**Verlag:** IEEE  
**Konferenz:** 2025 IEEE 9th Forum on Research and Technologies for Society and Industry (RTSI)  
**Autoren:** Kapischan Sriganthan, Felix Härer  

Die Veröffentlichung präsentiert:
- die theoretische Grundlage
- eine strukturierte Literaturübersicht
- das Trainingskonzept
- die Chatbot-Architektur
- und die Evaluation dieses Proof of Concept

Der in diesem Repository implementierte PoC unterstützt und demonstriert direkt die im Paper diskutierten Konzepte.

IEEE Xplore: https://ieeexplore.ieee.org/document/11212360
---

## Projektentwicklung (Versionen)

Dieses Projekt existiert in **drei Entwicklungsstufen**:

### Version 1 – Initial Proof of Concept
- Regelbasierter Chatbot (intents.json)
- Flask Backend
- Simulierte Website-Umgebung
- Statische Phishing-Szenarien
- Fokus: **Machbarkeit & Interaktionsfluss**

📌 Archiviert im privaten Repository `ksriganthan/phishingchatbot`. Auf Anfrage gebe ich Einsicht.

---

### Version 2 – Improved Design (Paper Pre-Submission Version)
- UI/UX-Verbesserungen
- Verfeinerte Phishing-Szenarien
- Bessere visuelle Integration des Chatbots
- Angepasst für Einreichung und Demonstration der wissenschaftlichen Arbeit

📌 Archiviert im privaten Repository `ksriganthan/tobit_poc`. Auf Anfrage gebe ich Einsicht.

---

### Version 3 – LLM-basierter Forschungsprototyp (Konferenzversion)
- Konzeptionelle Integration von **Large Language Models**
- Adaptives Feedback und kontextuelle Antworten
- Forschungsprototyp für Konferenzpräsentation
- Fokus: **interaktives Lernen & Adaptivität**

https://github.com/fhaer/adaptive-phishing-awareness-training.git
---

## Was dieses Repository enthält

Dieses Repository enthält den **ersten funktionalen Proof of Concept**, absichtlich einfach und transparent gehalten, um Folgendes zu demonstrieren:

- Chatbot-Website-Integration
- Phishing-Simulationslogik
- Benutzerinteraktions- und Feedback-Fluss
- Architektonische Machbarkeit ohne LLM-Abhängigkeit

Der Chatbot **CyberPhil** fungiert als:
- ein Leitfaden
- ein Trainer
- und ein Feedback-Mechanismus während Phishing-Simulationen

---

## Features

- Interaktive Phishing-Simulationen
- Eingebetteter Chatbot (CyberPhil)
- Unmittelbares Feedback zu Benutzeraktionen
- Regelbasierte Intent-Verarbeitung via `intents.json`
- Web-basierte UI (HTML, CSS, JavaScript)
- Flask Backend
- Leichtgewichtige und reproduzierbare PoC-Architektur

---

## Verwendete Technologien

- Python 3.8+
- Flask
- NLTK
- Torch (grundlegende ML-Unterstützung)
- HTML / CSS / JavaScript
- Qwen 2.5 7B (Ollama)

---
