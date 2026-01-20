# Assignment 03 (Individual) – GAMES DEVELOPMENT

**SE4031 – Games Development**  
**Title – Immersive VR Simulation Experience: VIRTUAL EMERGENCY RESPONSE**  
**Assignment Created By:** Mr. Aruna Ishara Gamage, Mr. Nushkan Nismi  
**End Digit:** 4  
**Assignment Weight:** 30%

---

## OBJECTIVE

Virtual Emergency Response

Design and develop an immersive Virtual Reality (VR) emergency response simulation using Unity,  
where the player must respond to critical and time-sensitive scenarios.

Players navigate emergency environments, interact with rescue equipment, issue voice-based  
emergency commands, and make decisions under pressure to successfully complete a time-critical  
emergency challenge.

---

## ASSIGNMENT STRUCTURE (2 Parts)

- **Part A (60%) – Based on Tutorials + Lab Sheets**  
  Students can score Part A using concepts and techniques covered in tutorials and lab sessions.

- **Part B (40%) – Self-Learning + Advanced Work (Required for High Grades)**  
  Part B requires independent research and creativity, focusing on voice-based ritual invocation  
  and a unique sanctuary challenge.

---

## CORE REQUIREMENTS

## Part A Requirements (60%)

### 1. VR Movement & Locomotion

- Use teleportation or joystick-based movement.
- Allow safe and comfortable navigation across emergency environments (rooms, zones, outdoor areas)

### 2. Emergency Interactable

- Implement at least three (3) of the following:
  - Emergency equipment: Extinguishers, medical kits, or tools)
  - Victims / NPCs: Characters requiring assistance
  - Switches, breakers, panels: Control systems or power
  - Doors or access barriers: Open or restrict access

### 3. VR UI Elements

- Include a HUD or VR-friendly UI displaying:
  - Emergency priorities or task list
  - Warnings and alerts
  - Timers or condition indicators

### 4. Basic Environmental Feedback

- Alarm sounds, hazard indicators, or urgency cues
- Environmental responses to player actions

---

## Part B Requirements (40%) – Self Learning

### 5. Ritual Invocation System (Voice Input Only)

- The player must trigger at least three (3) emergency actions using voice commands only.

Example Commands (DO NOT USE):

- “Apply CPR” – Stabilizes a patient
- “Extinguish Fire” – Suppresses a hazard
- “Call Backup” – Summons assistance

#### IMPORTANT NOTE

- The ritual names listed below are EXAMPLES ONLY
- Students MUST create their own original emergency command phrases
- Using the example words exactly as written will result in 0 marks for this component.

The system must:

- Accurately detect commands using voice input tools (e.g., Windows Speech API (wit.ai).
- Provide visual/audio feedback upon successful commands recognition.
- Show a response or warning for unrecognized commands.
- When the application is built and executed directly on a VR headset, the Windows Speech API will not function. However, the same voice command system will work correctly when the application is built as a Windows Desktop (.exe) and run on a PC with a connected VR headset.

### 6. Voice Command Integration

- Integrate a real-time speech recognition system.
- Provide visual and/or audio feedback for:
  - Correct emergency commands
  - Incorrect or unrecognized commands
- Voice recognition must remain responsive during gameplay

### 7. Dynamic Scenario Reaction System

- Emergency commands and decisions must trigger clear scenario-based reactions, such as:
  - Fire spreading or being suppressed
  - Changes in victim condition
  - Escalation or resolution of hazards

### 8. Emergency Challenge Area (Mandatory)

- Include a dedicated emergency response scenario where the player must:
  - Use voice commands under time pressure
  - Combine equipment interaction + decision-making
  - Successfully complete a time-critical rescue or stabilization challenge

⚠️ Part B Creative Challenge Note

Part B includes a creative challenge, and it must be unique (not copied from other students) to score marks.

---

## Folder Structure & Code

- Unity project must follow the folder structure.
- Scripts and assets must be well-named and organized.

---

## Game Documentation

- Submit a PDF with:
  - Title, student name, and IT number
  - Game summary and spell list
  - Screenshots of gameplay
  - Control guide (movement, voice usage)
  - Credits for any assets/tools used

---

## Submission Requirements

### Windows .exe Build

Include .exe and Data folder, playable with a VR headset.

### Zipped Unity Project Folder

Must follow the folder structure.  
Upload to a shared Google Drive folder in Courseweb.

### Gameplay Demo Video

- 5 minutes showcasing:
  - Voice-activated spellcasting
  - Movement
  - Item collection and target interaction
  - Spellbook interaction
  - Challenge zone gameplay

---

## PLAGIARISM / ORIGINALITY VERIFICATION (VIVA)

- A mandatory one-to-one viva will be conducted
- Students must clearly explain:
  - Voice command logic
  - System interaction behavior
  - Emergency challenge design
- Failure to justify originality may result in mark deductions or zero marks

---

## Assessment Rubric (Part A + Part B)

## Part A (60 Marks)

| Criteria | Excellent | Good | Satisfactory | Poor | Marks |
|---------|-----------|------|--------------|------|-------|
| VR Movement & Locomotion | Smooth, immersive, and comfortable navigation across emergency environments | Navigation implemented with minor comfort or control issues | Basic navigation with noticeable limitations | No or broken navigation | 12 |
| Emergency Interactables | All required interactables fully implemented with clear visual/audio feedback and logical responses | Most interactables working with minor issues | Limited or partially functional interactables | No meaningful interactables | 12 |
| VR UI Elements | Clear, VR-friendly HUD showing priorities, alerts, and timers | UI mostly clear with minor usability issues | Basic UI with limited usefulness | No VR UI elements | 10 |
| Folder Structure & Code Quality | Fully structured Unity project with clean, well-named scripts and assets | Mostly structured with few misplacements | Inconsistent structure | Disorganized or missing structure | 8 |
| Game Documentation | Complete, clear PDF covering all required sections | Mostly complete with minor missing details | Basic documentation with limited explanation | No documentation submitted | 8 |
| **Part A Total** |  |  |  |  | **60** |

---

## Part B (40 Marks) – Self Learning

| Criteria | Excellent (Full Marks) | Good | Satisfactory | Poor | Marks |
|---------|--------------------------|------|--------------|------|-------|
| Voice-Based Emergency Commands (Voice Only) | Three (3) unique emergency commands accurately triggered via voice with clear VFX/SFX | Two commands working, one partially functional | Only one unstable or partially working command | Commands missing or not voice-controlled | 20 |
| Voice Command Integration | Voice system is stable, responsive, and provides clear feedback with captions | Minor delays or recognition issues | Frequently unresponsive or inconsistent | Not implemented or unusable | 12 |
| Dynamic Scenario Reaction + Emergency Challenge Area | Strong immersion with dynamic scenario reactions and a fully playable time-critical emergency challenge | Working challenge with minor functional issues | Weak reactions with a basic or low-pressure challenge | Poor or missing reactions and challenge | 8 |
| **Part B Total** |  |  |  |  | **40** |

Plagiarism / Originality Verification (Viva)
