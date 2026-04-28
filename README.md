# Sovereign Persona Sentinel (SPS) 
An AI-based cybersecurity training platform that tests how vulnerable a user is, simulates realistic cyberattacks, and then gives tailored advice on how to stay protected.
Model : Gemini 2.5 
API : Gemini

_____________________________________________________________________________________________________________________________________________________________________________________________
Sovereign Persona Sentinel (SPS)
_____________________________________________________________________________________________________________________________________________________________________________________________
An AI-powered behavioral intelligence system that constructs Data Shadows and Data Twins to simulate, analyze, 
and defend against targeted phishing attacks.

_____________________________________________________________________________________________________________________________________________________________________________________________

Overview:

Sovereign Persona Sentinel models human behavior to identify vulnerabilities and simulate realistic phishing scenarios.

It is built on two core concepts:

Data Shadow — Passive digital footprint derived from user behavior
Data Twin — AI-generated behavioral replica used for simulation

_____________________________________________________________________________________________________________________________________________________________________________________________

Tech Stack: 

Backend:
Python
FastAPI (Uvicorn)
Gemini API
Frontend:
React (Vite)

The system enables:

Vulnerability prediction
Targeted attack simulation
Intelligent defense generation
_____________________________________________________________________________________________________________________________________________________________________________________________

Project Structure:

<pre> SPS/ ├── backend/ │ ├── main.py │ ├── shadow_mapper.py │ ├── vulnerability_engine.py │ ├── attack_generator.py │ ├── trust_score.py │ ├── defense_generator.py │ ├── gemini_client.py │ └── requirements.txt │ ├── frontend/ │ ├── src/ │ ├── index.html │ ├── package.json │ └── vite.config.js </pre>
_____________________________________________________________________________________________________________________________________________________________________________________________

Installation:

<pre>
git clone &lt;(https://github.com/Mahi-KK/Errix_Sovereign-Persona-Sentinel-SPS-.git)&gt;
cd SPS
</pre>
_____________________________________________________________________________________________________________________________________________________________________________________________

Running Sequence:

<pre>
cd backend
pip install -r requirements.txt
uvicorn main:app --reload

cd ../frontend
npm install
npm run dev

Access: http://localhost:3000
</pre>
_____________________________________________________________________________________________________________________________________________________________________________________________

System Workflow:

<pre>
User Input / Persona
        ↓
Data Shadow Construction
        ↓
Data Twin Simulation
        ↓
Vulnerability Analysis
        ↓
Attack Generation
        ↓
Trust Score Evaluation
        ↓
Defense Generation
        ↓
Frontend Visualization
</pre>
_____________________________________________________________________________________________________________________________________________________________________________________________

Modules:

<pre> 
shadow_mapper.py         → Builds Data Shadow
        
vulnerability_engine.py  → Identifies vulnerabilities
        
attack_generator.py      → Generates phishing scenarios
        
trust_score.py           → Calculates risk score
        
defense_generator.py     → Suggests defenses
        
gemini_client.py         → Handles AI communication
</pre>
_____________________________________________________________________________________________________________________________________________________________________________________________

Important Note Pointers:
<pre>
- Configure .env with your API key before running
- Backend runs on localhost:8000 by default
- Start backend before frontend
</pre>
_____________________________________________________________________________________________________________________________________________________________________________________________

# ⚠️ Caution!!! - Ethical Use only:

<pre>
This project is intended strictly for:
- Cybersecurity research
- Awareness and training
- Controlled simulations only
</pre>

