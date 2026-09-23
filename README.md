# CSI: The Silent Room

**CSI: The Silent Room** is an interactive **forensic crime-scene investigation simulator** built with **A-Frame, WebXR, HTML, JavaScript, and Three.js**.

The project creates a fictional crime scene where players can explore the environment, identify suspicious objects, inspect evidence, physically interact with evidence items, collect clues, and manage the investigation through an in-game **Case File** and **Evidence Inventory**.

The experience is designed to work in both **Desktop/Laptop mode** and **Meta Quest 3S VR mode**.

## 🕵️ Features

* Interactive 3D fictional crime scene
* Forensic investigation gameplay
* Explore the crime scene from a first-person perspective
* Identify and inspect evidence
* Grab and release evidence objects
* Collect evidence into the investigation inventory
* Evidence identification system with unique IDs
* Evidence descriptions and investigation information
* In-game **Case File**
* Evidence **Inventory**
* Investigation objectives
* Real-time evidence collection status
* Desktop keyboard interaction
* WebXR-based VR experience
* Meta Quest 3S compatibility
* Browser-based gameplay
* A-Frame-powered 3D environment
* Three.js-based interaction and scene control

## 🎮 Desktop Controls

The simulator can be played using a laptop or desktop keyboard without requiring a mouse for the main investigation interactions.

| Key               | Action                            |
| ----------------- | --------------------------------- |
| **W / A / S / D** | Move                              |
| **Arrow Keys**    | Look around                       |
| **G**             | Grab / Release evidence           |
| **E**             | Inspect evidence                  |
| **C**             | Collect evidence                  |
| **Q**             | Open Case File                    |
| **I**             | Open Evidence Inventory           |
| **Esc**           | Close panels / cancel interaction |

The keyboard interaction system allows players to investigate and collect evidence without depending on traditional mouse controls.

## 🥽 Meta Quest 3S / VR

The project is designed around **WebXR**, allowing the investigation environment to be experienced in an immersive VR headset.

In VR, players can:

* Look around naturally using head movement
* Move through the crime scene using VR controls
* Point toward evidence
* Interact with evidence objects
* Grab and release evidence
* Inspect clues
* Collect evidence
* Review investigation information

The VR interaction system is intended to provide the same core investigation experience as the desktop version.

## 🔎 Evidence System

Each investigation item has its own unique evidence identity.

For example:

```text
E01 — Suspicious Key
E02 — Mobile Phone
E03 — Glass Fragment
E04 — Handwritten Note
```

Each evidence item can contain information such as:

* Evidence ID
* Evidence name
* Description
* Collection status
* Investigation state
* Physical 3D object

When evidence is collected, its status is updated in the investigation system and the item is added to the Evidence Inventory.

## 📁 Case File

The **Case File** provides an overview of the investigation.

It can display:

* Case name
* Investigation objectives
* Total evidence
* Collected evidence
* Remaining evidence
* Evidence identification numbers
* Investigation progress

This gives the player a centralized way to track the investigation.

## 🎒 Evidence Inventory

The Evidence Inventory keeps track of evidence successfully collected from the crime scene.

For example:

```text
E01 — Suspicious Key ✓
E02 — Mobile Phone ✓
E03 — Glass Fragment
E04 — Handwritten Note
```

The inventory allows the player to see which pieces of evidence have already been collected and which remain to be investigated.

## 🌐 Technology Stack

The project uses web technologies to create a browser-based immersive experience.

* **HTML5**
* **JavaScript**
* **A-Frame**
* **WebXR**
* **Three.js**
* **Meta Quest 3S**
* **GitHub Pages**

## 💻 Desktop + VR

One of the main goals of the project is to provide two interaction modes within the same application:

```text
                 CSI: THE SILENT ROOM
                         │
             ┌───────────┴───────────┐
             │                       │
       Desktop Mode              VR Mode
             │                       │
       Laptop Keyboard          Meta Quest 3S
             │                       │
       Explore Scene             Explore Scene
       Inspect Evidence          Inspect Evidence
       Grab Evidence             Grab Evidence
       Collect Evidence          Collect Evidence
             │                       │
             └───────────┬───────────┘
                         │
                  Shared Evidence
                      System
                         │
                  Case File +
                  Inventory
```

## 🎯 Project Objective

The purpose of **CSI: The Silent Room** is to explore the possibilities of creating an accessible **browser-based forensic investigation experience** using WebXR.

Instead of requiring a traditional game engine installation, the project aims to make the experience accessible through a modern web browser while also providing an immersive VR experience through Meta Quest 3S.

The project focuses on:

* Web-based VR development
* 3D interaction
* Evidence collection mechanics
* Immersive investigation
* Keyboard-based interaction
* WebXR experimentation
* Cross-platform accessibility

## 🚀 Running the Project

The project can be hosted using a web server or **GitHub Pages**.

For VR/WebXR functionality, the project should be accessed through a secure **HTTPS** connection.

Once deployed, users can open the project in a compatible browser or access it through a supported Meta Quest browser.

## ⚠️ Disclaimer

**CSI: The Silent Room** is a fictional crime-scene investigation simulation created for educational, experimental, and entertainment purposes.

The crime scene, evidence, clues, characters, and investigation scenarios are fictional and are not intended to represent a real criminal investigation or professional forensic investigation system.

## 📌 Project Status

The project is an ongoing WebXR development project focused on improving:

* VR interaction
* Evidence handling
* Investigation mechanics
* 3D environments
* Case management
* Desktop controls
* Meta Quest compatibility
* Overall immersion and usability

---

### 🔍 Explore. Investigate. Collect the Evidence. Solve the Case.

**CSI: The Silent Room — A WebXR Forensic Investigation Experience**
<img width="1896" height="894" alt="Screenshot 2026-09-23 202918" src="https://github.com/user-attachments/assets/75928792-d2d8-453b-b109-c1c33e61ea14" />
<img width="1873" height="879" alt="Screenshot 2026-09-23 203021" src="https://github.com/user-attachments/assets/8fce617a-23e1-4470-8649-12fe7a0b54ee" />
<img width="1879" height="875" alt="Screenshot 2026-09-23 203101" src="https://github.com/user-attachments/assets/c3578350-956b-45c9-9ca2-27de53d36be2" />
<img width="1891" height="877" alt="Screenshot 2026-09-23 203250" src="https://github.com/user-attachments/assets/4d2207ab-2507-4cd3-bbaa-f294b11100e5" />
<img width="1888" height="890" alt="Screenshot 2026-09-23 203335" src="https://github.com/user-attachments/assets/d2df476a-58f7-4331-adbc-e1a2cfdf9be2" />

