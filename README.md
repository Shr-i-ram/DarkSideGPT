# DarkSideGPT

An AI-powered persuasion game where players assume the role of Darth Jar Jar Binks and attempt to convert Jedi Knights to the Dark Side through conversation, manipulation, and strategic influence.

Built using Flask and Google's Gemini API, DarkSideGPT combines role-playing, dynamic NPC behavior, and conversational AI to create an interactive Star Wars experience where every Jedi presents a unique challenge.

---

## Overview

The Galactic Republic has fallen into turmoil.

As Darth Jar Jar Binks, secret mastermind of the Sith Order, your mission is to corrupt captured Jedi and recruit them into the Dark Side.

Each Jedi possesses:

* Unique personality traits
* Individual motivations and weaknesses
* Varying resistance to persuasion
* Dynamic reactions to player actions

Your goal is to identify their vulnerabilities and slowly manipulate them until they embrace the Dark Side.

---

## Features

### AI-Powered NPCs

Each Jedi responds using Gemini-powered dialogue generation, allowing for dynamic and unpredictable conversations.

### Unique Jedi Personalities

Every character has:

* Different beliefs
* Different emotional triggers
* Different resistance levels
* Different persuasion strategies

### Sith Ascendancy System

Successful conversions increase your influence and strengthen your position within the Sith hierarchy.

### Dynamic Events

Random galactic events influence conversations and create new persuasion opportunities.

### Persistent Conversation Context

Jedi remember previous interactions, enabling multi-turn persuasion and character development.

---

## Gameplay Loop

```text
Choose a Jedi
      ↓
Analyze Their Personality
      ↓
Engage in Conversation
      ↓
Exploit Weaknesses
      ↓
Increase Dark Side Influence
      ↓
Convert the Jedi
      ↓
Expand Sith Ascendancy
```

---

## Tech Stack

### Backend

* Flask
* Python

### AI

* Google Gemini API

### Frontend

* HTML
* CSS
* JavaScript
* Axios

---

## Project Structure

```text
DarkSideGPT/
│
├── main.py
├── requirements.txt
├── README.md
│
├── templates/
│   └── index.html
│
└── static/
    ├── app.js
    ├── style.css
    └── assets/
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/DarkSideGPT.git

cd DarkSideGPT
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## API Key Setup

Create a `.env` file:

```env
GOOGLE_API_KEY=YOUR_API_KEY
```

Or set an environment variable directly.

### Windows PowerShell

```powershell
$env:GOOGLE_API_KEY="YOUR_API_KEY"
python main.py
```

### Linux/macOS

```bash
export GOOGLE_API_KEY="YOUR_API_KEY"
python main.py
```

---

## Running the Application

Start the Flask server:

```bash
python main.py
```

Open your browser:

```text
http://127.0.0.1:5000
```

---

## Example Scenario

```text
Jedi: "The Dark Side only brings suffering."

Darth Jar Jar:
"Does the Jedi Council truly care for you,
or have they simply used you as another pawn?"

Jedi:
"...Perhaps the Council has made mistakes."
```

Every conversation can alter a Jedi's loyalty and bring them closer to conversion.

---

## Future Improvements

* Additional Jedi and Sith characters
* Character memory systems
* Long-term progression mechanics
* Voice interaction
* Multiplayer persuasion battles
* Fine-tuned Star Wars NPC models
* Leaderboards and campaign mode

---

## Author

Shriram

Interests:

* Artificial Intelligence
* Machine Learning
* Quantum Computing
* Human-AI Interaction
* Game Development

GitHub:
https://github.com/Shr-i-ram

---

## Disclaimer

This project is an unofficial fan-made Star Wars experience created for educational and entertainment purposes.
