<img width="1280" height="640" alt="git (1)" src="https://github.com/user-attachments/assets/8920b256-2ba8-4988-b824-5351134eb4bd" />



# THE COUNCIL OF BUTTONS 🎯


## Basic Details
### Team Name: HK


### Team Members
- Team Lead: HAMRAAZ MOHAMMED - SAHRDAYA COLLEGE OF ENGINEERING AND TECHNOLOGY 
- Member 2: MUHAMMED IRSHAD - SAHRDAYA COLLEGE OF ENGINEERING AND TECHNOLOGY 

### Project Description

THE COUNCIL OF BUTTONS is a single-file web application containing 500 buttons, and pressing them accomplishes absolutely nothing. Every button has its own name, personality, mood, and sound; they hold chain-reaction conversations with each other, react to your cursor, fire you from an ATM, and — via your webcam — let your own face join the Council as a floating member the buttons gossip about.
It is a meticulously engineered waste of time: 500 buttons, zero functions, one hundred percent alive.

### The Problem (that doesn't exist)

Modern software is too useful. Every app demands goals, productivity, and outcomes. Humanity is suffering from a critical shortage of software that lets you press a button labeled "DO NOT PRESS," watch it dodge your cursor three times, click it anyway, survive a dramatic countdown — and have absolutely nothing happen.
Also: nobody has ever asked what happens when a button identifies as a potato. We answered anyway.



### The Solution (that nobody asked for)

A "digital council chamber" housing 500 circular buttons with genuine personalities (nervous, arrogant, dramatic, one convinced it's a potato). Buttons talk to each other via glowing chain reactions, hold meaningless votes, stage fire drills, run karaoke night, and weather reports get judged by the Council. A Photo Booth (camera API) turns your face into a floating Council member that wanders the room, gets flung across it, and becomes the subject of button gossip. There is a Pointlessness Meter that measures how successfully you've accomplished nothing, an ATM that puts you in debt, a Lottery with 1-in-"no" odds, and 25+ hidden secrets. Everything is real, working, interactive engineering — pointed directly at producing nothing of value.


## Technical Details
### Technologies/Components Used
For Software:
- Languages: HTML5, CSS3, JavaScript (vanilla ES6+, zero frameworks)
- Frameworks/Libraries: None by design — the whole point is doing it the hard way
APIs used:
- Web Audio API — 25+ sound effects synthesized live (oscillators + noise buffers + compressor), with per-sound cooldowns and a voice cap
- Canvas 2D API — particle bursts, confetti, glowing beam effects, ripples on a 3600×2400 world-space layer
- MediaDevices / getUserMedia — webcam Photo Booth; face becomes a physics-simulated Council member
- Geolocation + Open-Meteo API — the "is it too hot to press buttons" weather line
- localStorage — persistence of presses, secrets, and preferences
- Tools: Any modern browser, VS Code, python -m http.server (for camera/HTTPS testing)

For Hardware:
- Any laptop/PC with a browser (16 GB RAM not required; the app is lighter than it deserves)
- Webcam (optional — the Council "commissions a portrait" if denied)
- Speakers/headphones (optional — sound captions exist for the mute)

### Implementation
For Software:
# Installation
- No install. One file. That's the flex.
- (Optional — only to enable the webcam locally:)
python -m http.server 8000

# Run
- Option A: double-click council.html
- Option B (webcam enabled):
- open http://localhost:8000/council.html
- Then: click to enter → press things → accomplish nothing


### Project Documentation
For Software:

# Screenshots (Add at least 3)
<img width="1280" height="800" alt="Screenshot 2026-09-12 030542" src="https://github.com/user-attachments/assets/1342b15a-d2bb-495a-bbd1-2a8523364ec5" />


<img width="1280" height="798" alt="Screenshot 2026-09-12 030410" src="https://github.com/user-attachments/assets/e9cec7b9-a972-4c13-b515-9ac0675a323c" />
Photo Booth overlay + a floating circular face-photo

<img width="1280" height="800" alt="Screenshot 2026-09-12 030311" src="https://github.com/user-attachments/assets/3c69375d-acaa-439e-992c-abc64784fdf0" />
You have accomplished nothing popup 

# Diagrams

<img width="1224" height="1285" alt="councilofbuttons flowchart" src="https://github.com/user-attachments/assets/7d3c1c59-e150-440c-b6c1-a7cf08e3df15" />

                                         



### Project Demo
# Video
https://drive.google.com/drive/folders/1k0sG5rEkwcbOgw8RwebiqmqAgYOqiEMU?usp=sharing

## Team Contributions
- HAMRAAZ MOHAMMED (Team Lead): Core engine — 500-button generation system, personalities/mood state machine, chain-reaction scheduler with hop budgets, spring-physics animation loop, camera/Photo Booth system with drag-and-fling physics, Web Audio synthesis engine (25 sounds), chain/FX canvas renderer.
- MUHAMMED IRSHAD: UI/UX and the Pointlessness layer — dock, search, guided tour, minimap, inspector; the v3/v4 systems (hourglass, floppy save, printer & permits, store, door, screensaver, wallpaper, stalker, lottery, T&C, ATM, suggestion box, hotline); secrets design (25+), random events (fire drill, karaoke, the cloud), dialog/typography system, testing and demo polish.

---
Made with ❤️ at TinkerHub Useless Projects 

![Static Badge](https://img.shields.io/badge/TinkerHub-24?color=%23000000&link=https%3A%2F%2Fwww.tinkerhub.org%2F)
![Static Badge](https://img.shields.io/badge/UselessProjects--26-26?link=https%3A%2F%2Ftinkerhub.org%2Fevents%2F1M8ORET9A1%2Fuseless-projects-3.0)



