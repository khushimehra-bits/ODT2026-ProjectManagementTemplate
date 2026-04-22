# Open Design and Technology  
## Final Project README

> **Project Weight:** 70%  
> **Team Size:** 2 students  
> **Project Duration:** 4 weeks  
> **Class Time Available:** 6 hours per class  
> **Total Time Available:** 48 effort-hours per team  
> **Project Type:** Playful, interactive, technology-based experience

---

# Before you begin

## Fork and rename this repository
After forking this repository, rename it using the format:

`ODT-2026-PULLPIN`

### Example
`ODT-2026-PixelWizards`

Do not keep the default repository name.

---

# How to use this README

This file is your team’s **working project document**.

You must keep updating it throughout the 4-week build period.  
By the final review, this README should clearly show:
- your idea,
- your planning,
- your design decisions,
- your technical process,
- your build progress,
- your testing,
- your failures and changes,
- your final outcome.

## Rules
- Fill every section.
- Do not delete headings.
- If something does not apply, write `Not applicable` and explain why.
- Add images, screenshots, sketches, links, and videos wherever useful.
- Update task status and weekly logs regularly.
- Use this file as evidence of process, not only as a final report.

---

# 1. Team Identity

## 1.1 Studio / Group Name
Suksha and Khushi

## 1.2 Team Members

| Name | Primary Role | Secondary Role | Strengths Brought to the Project |
|---|---|---|---|
| `[Khushi]` | `[[Electronics / App / Fabrication / Mechanics]` | `[making the physical setup and app]` | `[Physical build of the setup and mechanics]` |
| `[Suksha]` | `[Electronics / Coding/ Debugging]` | `[Coding and electronics]` | `[Coding prowess and troubleshooting]` |

## 1.3 Project Title
`[Pull pin game]`

## 1.4 One-Line Pitch
`[A game where you have to drop coins through a maze by testing your decision making ability]`

## 1.5 Expanded Project Idea
In 1–2 paragraphs, explain:
- what your project is,
- what kind of playful experience it creates,
- what makes it fun, curious, engaging, strange, satisfying, competitive, or delightful,
- what technologies are involved.

**Response:**  
`[A game with several pins that need to pulled out using a web interface to make a coin/ several coins together go through and obstacle course down the correct shoot into the bucket which holds an ultra sonic sensor. It creates a fun and adrenaline filled game of chance. It is based partially on chance and partially on reflexes, the time sensitivity, and planning.]`

---

# 2. Philosophy Fit

## 2.1 Experience, Not Social Problem
This module does **not** require your project to solve a large social problem.

You are allowed to build:
- toys,
- games,
- interactive objects,
- playful machines,
- kinetic artifacts,
- humorous devices,
- strange but delightful experiences,
- things that are entertaining to use or watch.

## 2.2 What kind of experience are you creating?
Answer the following:
- What is the experience?
- What do you want the player or participant to feel?
- Why would someone want to try it again?

**Response:**  
`[This project creates an interactive, arcade-like experience where players trigger mechanisms to release coins and aim to achieve a winning condition. The experience is fast, responsive, and visually engaging, combining physical movement with light feedback. The player should feel excitement, anticipation, and a sense of control while interacting with the system. The unpredictability of outcomes and the satisfying physical response encourage repeated attempts and playful experimentation.]`

## 2.3 Design Persona
Complete the sentence below:

> We are designing this project as if we are a small creative studio making a **[toy / game / playable object / interactive experience]** for **[children / teens / adults / classmates / exhibition visitors / mixed audience]**.

**Response:**  
`[We are designing this project as if we are a small creative studio making an interactive game for a mixed audience of classmates and exhibition visitors, focusing on creating a playful, engaging, and easy-to-understand experience that invites quick participation and repeat interaction.]`

---

# 3. Inspiration

## 3.1 References
List what inspired the project.

| Source Type | Title / Link | What Inspired You |
|---|---|---|
| `[Toy /App/ Website]` | `[[(https://poki.com/en/g/how-to-loot-pin-pull)]` | `[We took from this concept and made the hardware to match the game]` |
| `[Toy / Game]' |  '['Coin pusher arcade machines].	'[The idea of using coins, physical reward systems, and repeatable play for engagement.]'|
|  '[Object]' | '[Servo-based mechanisms]' | '[Using controlled mechanical movement to create precise, repeatable interactions.]` |

## 3.2 Original Twist
What makes your project original?

**Response:**  
`[The project translates a digital pin-pull game into a physical, interactive system using servos, sensors, and real coins. It combines app-based control with tangible mechanics, adding unpredictability through real-world physics and feedback through lights and motion, making the experience more immersive and playful than its digital inspiration.]`

---

# 4. Project Intent

## 4.1 Core Interaction Loop
Describe the main loop of interaction.

Examples:
- press → launch → score → reset
- connect → control → observe → repeat
- turn → trigger → react → repeat
- move object → sensor detects → sound/light response → player reacts

**Response:**  
`[Connect → Select pin (app) → Trigger servo (pull pin) → Coin drops → Ultrasonic sensor detects → light as experience (NeoPixel) → Observe result → Repeat]`

## 4.2 Intended Player / Audience

| Question | Response |
|---|---|
| Who is this for? | `[Students, casual players, and exhibition visitors interested in interactive physical-digital games]` |
| Age range | `[9+]` |
| Solo or multiplayer | `[Primarily solo, but can be played turn-based in groups]` |
| Expected duration of one round | `[2-3 minutes]` |
| What should the player feel? | `[Curiosity, anticipation, and satisfaction through cause-and-effect interaction, along with playful engagement]` |
| Is explanation required before use? | `[Minimal — intuitive interaction, but basic instructions improve experience]` |

## 4.3 Player Journey
Describe exactly how a player will use the project.

1. **Approach:** [The player encounters a physical setup with multiple pins and a coin collection bucket, accompanied by a mobile interface.]
2. **Start:** [The player takes the phone contected to the system via Bluetooth using the app.]
3. **First Action:** [They press a button on the app to select and trigger a specific pin.]
4. **Main Interaction:** [The player continues selecting different pins through the app, experimenting with timing and choice to release coins into the bucket.]
5. **System Response:** [Each input triggers a servo that pulls a pin, releasing a coin. The ultrasonic sensor detects the coin drop, and NeoPixel lights respond with dynamic color feedback.]
6. **Win / Lose / End Condition:** [A round ends after a fixed number of attempts or time. Success can be defined by the number of coins collected or achieving a target weight.]
7. **Reset:** [Pins are manually reset to their original positions, the bucket is emptied and weight reset, and the system is ready for the next player.]

## 4.4 Rules of Play
If your project is a game, list the rules clearly.

[Press one of the five buttons to trigger a corresponding pin (servo).]
[Each pin releases coins into the system.]
[Players can press buttons multiple times to influence the outcome.]
[Win: When enough coins reach the target area (detected by the sensor), the game triggers a win response.]

---

# 5. Definition of Success

## 5.1 Definition of “Playable”
Your project will be considered complete only if these conditions are met.

- [YES] `[App successfully connects to the ESP32 via WiFi]
- [YES]  '[Each button correctly triggers its corresponding servo]
- [YES]  [Pins release coins reliably without jamming]
- [YES]   [System detects a win condition using the sensor]
- [YES]   [Visual feedback (NeoPixel lights) responds to gameplay]
## 5.2 Minimum Viable Version
What is the smallest version of this project that still delivers the core experience?

**Response:**  
`[The smallest version of the project includes one servo-controlled pin, a basic app with one button to trigger it, and a simple mechanism to release coins. The core experience is achieved if pressing the button causes a visible mechanical action and produces a satisfying, repeatable interaction.]`

## 5.3 Stretch Features
What features are nice to have but not essential?

- `[Lightfeedback from Neopixel]`
- `[Ultrasonic sensor to detect win]`
- `[App instead of physical buttons]`

---

# 6. System Overview

## 6.1 Project Type
Check all that apply.

- [YES] Electronics-based
- [ ] Mechanical
- [YES] Sensor-based
- [YES] App-connected
- [YES] Motorized
- [ ] Sound-based
- [YES] Light-based
- [YES] Screen/UI-based
- [YES] Fabricated structure
- [YES] Game logic based
- [YES] Installation / tabletop experience
- [ ] Other: `[Write here]`

## 6.2 High-Level System Description
Explain how the system works in simple terms.

Include:
- input,
- processing,
- output,
- physical structure,
- app interaction if any.

**Response:**  
`[The system is controlled through a mobile app that acts as the main input, where each button press sends a signal over WiFi to the ESP32. The ESP32 processes these signals and triggers the corresponding servo motors to pull pins and release coins. An ultrasonic sensor continuously monitors the system to detect when enough coins reach the target area, acting as a win condition. Based on this, the system processes whether the game is ongoing or completed. Outputs include the physical movement of servos, coins falling through the structure, and visual feedback through NeoPixel LEDs that animate during gameplay and celebrate when the player wins. The physical structure consists of a frame holding the pins, servo mechanisms, coin pathways, and a collection area, creating a tangible and interactive game controlled digitally through the app.]`

## 6.3 Input / Output Map

| System Part | Type | What It Does |
|---|---|---|
| `[ App Input]` | Input | `[Sends]` |
| `[ESP32 / Controller]` | Processing | `[Receives signals, processes game logic, triggers servos, reads sensor data, and controls LEDs]` |
| `[Servos + NeoPixel LEDs]` | Output | `[Servos pull pins to release coins; LEDs provide visual feedback and animations]` |
| `[Mechanical Assembly]` | Physical Action | `[Pins, threads, and structure guide and release coins into the collection area]` |

---

# 7. Sketches and Visual Planning

## 7.1 Concept Sketch
Add an early sketch of the full idea.

**Insert image below:**  
`[Upload image and link here]`
<img width="900" height="1600" alt="Plan sketch " src="https://github.com/user-attachments/assets/aebdeb3e-d01b-4d04-8938-2f7d9e9001a4" />

Example:
```md


```

## 7.2 Labeled Build Sketch
Add a sketch with labels showing:
- structure,
- electronics placement,
- user touch points,
- moving parts,
- output elements.

**Insert image below:**  
`[Upload image and link here]`
<img width="449" height="651" alt="build sketch" src="https://github.com/user-attachments/assets/42890a6d-70bb-46e4-9b88-db61ddec8fcc" />


## 7.3 Approximate Dimensions

| Dimension | Value |
|---|---|
| Length | `[50cm]` |
| Width | `[35cm]` |
| Height | `[2cm]` |
| Estimated weight | `[2kg]` |

---

# 8. Mechanical Planning

## 8.1 Mechanical Features
Check all that apply.

- [ ] Gears
- [YES] Pulleys
- [ ] Belt drives
- [YES] Linkages
- [ ] Hinges
- [ ] Shafts
- [ ] Springs
- [ ] Bearings
- [ ] Wheels
- [YES] Sliders
- [YES] Levers
- [ ] Not applicable

## 8.2 Mechanical Description
Describe the mechanism and what it is meant to do.

**Response:**  
`[The servo pulls an axel it is attatched to, which is inturn pulling the pin (the lever) that makes the coins fall through the slots made.]`

## 8.3 Motion Planning
If something moves, explain:
- what moves,
- what causes the movement,
- how far it moves,
- how fast it moves,
- what could go wrong.

**Response:**  
The servo arm rotates when triggered, the servo pulls the pin and the coin drops through the slot (if in the rigth position). The motion is about 45 to 55 degrees, controlled by the servo’s programmed angle, and occurs over a few seconds for smooth release. The pin moves linearly outward, allowing coins to fall. The speed is moderate to ensure control and avoid jamming. Possible issues include thread slipping, servo not generating enough torque, or the pin getting stuck due to friction or misalignment.

## 8.4 Simulation / CAD / Animation Before Making
If your project includes mechanical motion, document the digital planning before fabrication.

| Tool Used | File / Lnk | What Was Tested |
|---|---|---|
| `[-]` |

## 8.5 Changes After Digital Testing
What changed after the CAD, animation, or simulation stage?

**Response:**  
`[-]`

---

# 9. Electronics Planning

## 9.1 Electronics Used

| Component | Quantity | Purpose |
|---|---:|---|
| `[ESP32]` | `1` | `[Main controller]` |
| `[Servo]` | `[4]` | `[control the obstacles of the game and the motion of the coins]` |
| `[Ultra sonic sensor]` | `[1]` | `[senses the coins falling in the winning slot and sends a signal to the neopixel]` |
| `[Neopixel]` | `[1]` | `[Remains red until it recieves the signal from the ultra sonic and then turns green and after that a gradient in celebration ]` |

## 9.2 Wiring Plan
Describe the main electrical connections.

**Response:**  
In concurrence with the code - the wiring of 4 of the sercos will be on GPIOs 22, 4, 5, and 19. The GNDs of these servos will be connected to PSU GND. The 6th servo which is the continous sweep servo will be connected to GPIO 22 and the GND will be connected to PSU GND. PSU GND will be connected to the ESP 32's GND so that both grounds are connected. All red cables of the servos go to the 5V power unit and the yellow wires go to the GPIO pins while all the black wires of the servos go to GND. Then, the ultrasonic sensor will be connected via jumper cables. TRIG and ECHO will be connected to GPIO pins 32 (Pin.OUT) and 33 (Pin.IN) respectively. GND of the sensor will again go to PSU GND and VCC will go to 5V power. The NeoPixel will be connected to the GPIO pin 13 and the red and black wires will go to power and GND respectively. The placement of these can be toggled/shifted with jumper cables - but this is the essence of the wiring in our project.

## 9.3 Circuit Diagram
Insert a hand-drawn or software-made circuit diagram.

**Insert image below:**  
`[Upload image and link here]`
<img width="900" height="1600" alt="Circuit diagram " src="https://github.com/user-attachments/assets/b972c3f6-b574-4b47-9437-a62f9208e79b" />


## 9.4 Power Plan

| Question | Response |
|---|---|
| Power source | `[Power Supply Unit - connected to the adapter]` |
| Voltage required | `[5V]` |
| Current concerns | `[There was concern that the current passing through the circuit would not be enough to power 4 servos, the neopixel and the sensor, but that concern was resolved through the trials]` |
| Safety concerns | `[We were concerned that the PSU migth over heat and burn - which did happen once - but then we found out how to manage the current in the circuit well enough that all the components are powered and it is safe to work around.]` |

---

# 10. Software Planning

## 10.1 Software Tools

| Tool / Platform | Purpose |
|---|---|
| Micropython code | Used to create a code to connect ESP32, PSU, servos, neopixel, ultrasonic sensor and record its functions |
| MIT App inventor | Used to make interface for pressing the buttons required to move the pull pins |
| Laser cutting software tool | Used to make the hardware intricate parts by laser cutting acrylic sheets |
| Servo motors (3 of the 4) | Servos have a function of moving an angle of 45 to 55 degrees to let the coins pass that path |
| Continous sweep servo (4th servo) | This servo has the function of moving an angle of 110 to 125 degrees continously and the player must time the pull accurately to win the game |
| Ultrasonic sensor | The sensor is placed on the platfrom that decides the winner - the second coins fall on that platform the colour changes to green and then multiple celebratory colours |
| Neopixel | The neopixel rotates a red light on the circular strip until the player wins and then it resets |

## 10.2 Software Logic
Describe what the code must do.

Include:
- startup behavior,
- input handling,
- sensor reading,
- decision logic,
- output behavior,
- communication logic,
- reset behavior.

**Response:**  
The startup starts with all the servos excpet the continous sweep servo in rest position. The continous sweep servo moves continously 110 to 125 degrees back and forth - this is to increase the difficulty of the game. The neopixel is also on during startup - it powers a red light going round and round the neopixel - it loops until the winner is decided. As shown in the flowchart, the initialization of the app also happens during runtime. Once the app is ready, the buttons correspond to the servos to be moved. The buttons are pressed to make the coins move in the path the player intends. The buttons cannot be pressed more than once - demanding higher awareness and planning from the player. Each time a button is pressed, the corresponding servo moves 90 degrees and pulls the pin attatched to it making the coins fall into a path. The Ultrasonic sensor senses coins as they fall into the path that determines if the player wins the game or not. As soon as the sensor senses coins falling into that path, it makes the neopixel change from red to flash green twice to signal the win and then it transforms into celbratory colors for a while and then resets the game. The reset means that the runtime is over and for the game to be played again, the code needs to be run again.

## 10.3 Code Flowchart
Insert a flowchart showing your code logic.
<img width="739" height="1600" alt="Flow chart code" src="https://github.com/user-attachments/assets/49d11fc1-b6de-4390-b2d4-1773c1a37a8d" />

Suggested sequence:
- start,
- initialize,
- wait for input,
- read input,
- decision,
- trigger output,
- repeat or reset,
- error handling.

This is the flowchart for the code:

**Insert image below:**  
`[Upload image and link here]`

## 10.4 Pseudocode

```text
[Somewhere during the project experimentation, we wanted to experiment with a load cell and map out the wins based on the amount/weight of the coins that landed on the load cell platform - but all our load cell hardware was faulty and due to unvailability of a replacement, we decidede to go ahead with our initial idea of using a ultrasonic sensor to give the win feedback to the player.
- The code consists of 6 servos, one ultrasonic sensor and one neopixel.
- One servo is continously sweeping and the player has to time the pulling of the pin accurately.
- The 3 other servos are controlled by the buttons made on the app.
- Once the coin falls, the signal is picked up by the ultrasonic sensor and it is sent to the neopixel and the win signal is shown.

]
```

---

# 11. MIT App Inventor Plan

## 11.1 Is an app part of this project?
- [YES] Yes
- [ ] No

If yes, complete this section.

## 11.2 Why is the app needed?
Explain what the app adds to the experience.

Examples:
- remote control,
- score tracking,
- mode selection,
- personalization,
- triggering effects,
- displaying data.

**Response:**  
`[Instead of having physical buttons and more wiring, it more convenient to have a different interface that makes the experience neater and better, Remote controlling]`

## 11.3 App Features

| Feature | Purpose |
|---|---|
| `[Buttons]` | `[Buttons pressed to make the servos move to pull the pins]` |

## 11.4 UI Mockup
Insert a sketch or screenshot of the app interface.

**Insert image below:**  
`[Upload image and link here]`
<img width="573" height="751" alt="app UI" src="https://github.com/user-attachments/assets/615c4fa8-1fa4-4268-9632-1e173e77d140" />

## 11.5 Connect: Join WiFi kmehrawifi
[Control: Press buttons (Servo 1–5)
Play: Servos move, game responds
Reset: Win → reset game]

---

# 12. Bill of Materials

## 12.1 Full BOM

| Item | Quantity | In Kit? | Need to Buy? | Estimated Cost | Material / Spec | Why This Choice? |
|---|---:|---|---|---:|---|---|
| `[ESP32]` | `1` | `Yes` | `No` | `0` | `[Spec]` | `[It powers the arduino set]` |
| `[Servo motor]` | `[6]` | `[Yes]` | `[Yes]` | `[125x5]` | `[Spec]` | `[Servo motors are easy to program and work with]` |
| `[Neopixel]` | `[Qty]` | `[Yes]` | `[No]` | `[0]` | `[Spec]` | `[To be used as player feedback by using light for both game startup and win]` |
| `[Ultrasonic sensor]` | `[1]` | `[Yes]` | `[No]` | `[0]` | `[Spec]` | `[To sense the coins as they fall into the win path]` |
| `[Power supply]` | `[1]` | `[Yes/No]` | `[Yes/No]` | `[Cost]` | `[Spec]` | `[Gives additional voltage to the circuit - 5V]` |

## 12.2 Material Justification
Explain why you selected your main materials and components.

Examples:
- Why acrylic instead of cardboard?
- Why MDF instead of 3D print?
- Why servo instead of DC motor?
- Why bearing instead of a plain shaft hole?

**Response:**  
`[Pine wood instead of MDF because it would not hold the continuous movement happening through the game and also the MDF deteriorates with time. Arcylic is transparent and light so it does not put pressure on the servos.]`

## 12.3 Items to Purchase Separately

| Item | Why Needed | Purchase Link | Latest Safe Date to Procure | Status |
|---|---|---|---|---|
| `[Servo motors]` | `[A few of our servos were faulty so we needed to get some extra for the project]` | `[Amazon delivery]` | `[12th April]` | `[Ordered on the 10th, arrivedd on the 19th - but since it was physically also procured, we had 4 extra.]` |
| `[Power supply unit]` | `[The power supply unit had stopped working so it had to be replaced]` | `[Physically procured]` | `[17th April (It went out on the 17th)]` | `[Recieved on the 18th of April, tested and assembled.]` |

## 12.4 Budget Summary

| Budget Item | Estimated Cost |
|---|---:|
| Electronics | `[0]` |
| Mechanical parts | `[0]` |
| Fabrication materials | `[0]` |
| Purchased extras | `[Servos + Power supply = 770+500 = 1270 total]` |
| Contingency | `[already factored]` |
| **Total** | `[1270]` |

## 12.5 Budget Reflection
If your cost is too high, what can be simplified, removed, substituted, or shared?

**Response:**  
`[Although we had expected to do this without having to buy the electronics, we had left room for last minute purchases or fixes - and this came under that. As for the servos, it costed much less than expected - its just the delivery charges that added up. Overall, the cost was shared.]`

---

# 13. Planning the Work

## 13.1 Team Working Agreement
Write how your team will work together.

Include:
- how tasks are divided,
- how decisions are made,
- how progress will be checked,
- what happens if a task is delayed,
- how documentation will be maintained.

**Response:**  
- The tasks were divided as such: Khushi to handle the physical materials and app mechanics, Suksha to handle the working of the code and software debugging.
 - The decisions were made smoothly as communication was direct and immediate. Each memeber would keep track of their work and share progress timely with the other to ensure concurrence.
- Progress goals for each week were set and both members focused on completion of those tasks to ensure good time management
- Tasks were done on time. On the cases of hardware failure, we did fall back a couple steps but it helped us understand the process more and the time crunch wasn't as heavily felt as we had planned time for probavle failures too.
- Documentation was maintained throughout the process as tasks were getting done. As for the compilation of sketches, pictures and flowcharts - that happened at the end.
- The last few days of assembly and finalization set us back a few steps due to physical planning and software misalignment - so we re-worked and made a better system of interation of the servos with the pins and the coins. The number of servos to 4 and added more obstacles to increase the difficulty of the game.
- When the buttons on the app were not working as per the motion planned, we checked and rechecked code, wiring and app mechanics and identified a few discrapencies that would make the game work well at the end.

## 13.2 Task Breakdown

| Task ID | Task | Owner | Estimated Hours | Deadline | Dependency | Status |
|---|---|---|---:|---|---|---|
| T1 | `[Finalize concept]` | `[Khushi and suksha]` | `2` | `[30th march]` | `None` | `Done` |
| T2 | `[Complete BOM]` | `[Khushi and Suksha]` | `2` | `[6th april]` | `T1` | `Done` |
| T3 | `[Test electronics]` | `[Khushi and Suksha]` | `5-6` | `[Continous]` | `T1` | `Done` |
| T4 | `[Build structure]` | `[Khushi]` | `20` | `[16th April]` | `T1` | `Done` |
| T5 | `[Write control code]` | `[Suksha]` | `16` | `[v1 was done on 6th April and v5 was done 17th April]` | `T3` | `Done` |
| T6 | `[Integrate system]` | `[Khushi and Suksha]` | `16` | `[15th April]` | `T4, T5` | `Done` |
| T7 | `[Playtest]` | `[Khushi and Suksha]` | `5` | `[18th April` | `T6` | `Done` |
| T8 | `[Refine and document]` | `[Khushi and suksha]` | `14` | `[20th april]` | `T7` | `Done` |

## 13.3 Responsibility Split

| Area | Main Owner | Support Owner |
|---|---|---|
| Concept and gameplay | `[Khushi and Suksha]` |
| Electronics | `[Khushi and Suksha]` |
| Coding | `[Suksha]` | `[Khushi]` |
| App | `[Khushi]` | `[Suksha]` |
| Mechanical build | `[Khushi]` | 
| Testing | `[Suksha]]` | `[Khushi]` |
| Documentation | `[Khushi and Suksha]` | 

---

# 14. Weekly Milestones

## 14.1 Four-Week Plan

### Week 1 — Plan and De-risk
Expected outcomes:
- [yes] Idea finalized
- [yes] Core interaction decided
- [yes] Sketches made
- [yes] BOM completed
- [yes] Purchase needs identified
- [yes] Key uncertainty identified
- [yes] Basic feasibility tested

### Week 2 — Build Subsystems
Expected outcomes:
- [yes] Electronics tests completed
- [yes] CAD / structure planning completed
- [yes] App UI started if needed
- [yes] Mechanical concept tested
- [yes] Main subsystems partially working

### Week 3 — Integrate
Expected outcomes:
- [yes] Physical body built
- [yes] Electronics integrated
- [yes] Code connected to hardware
- [yes] App connected if required
- [yes] First playable version exists

### Week 4 — Refine and Finish
Expected outcomes:
- [yes] Technical bugs reduced
- [yes] Playtesting completed
- [yes] Improvements made
- [yes] Documentation completed
- [yes] Final build ready

## 14.2 Weekly Update Log

| Week | Planned Goal | What Actually Happened | What Changed | Next Steps |

| Week 1 | Finalize idea, sketch mechanism, identify components | Idea evolved from a simple servo mechanism to a game-based system with multiple servos and sensors | Added game logic (win condition + LED feedback) instead of just a mechanical output      | Start testing individual components (servo, ultrasonic, LEDs) |
| Week 2 | Test electronics and basic mechanism  | Faced issues with servo movement, power supply, and calibration   | Adjusted servo angles, changed duty values, and introduced external power considerations | Stabilize individual components and begin combining them      |
| Week 3 | Integrate system (code + hardware + structure)       | Integration was more complex than expected—WiFi/app control and timing issues came up              | Simplified logic, improved code structure, removed blocking delays  | Get a fully working playable prototype |
| Week 4 | Refine interaction and finalize build  | System became stable, but small bugs and mechanical misalignments remained but were fixed in time  | Fine-tuned timing, improved reliability, adjusted physical alignment   | Final testing, polish interaction, complete documentation   |
 |

---

# 15. Risks and Unknowns

## | Risk | Type | Likelihood | Impact | Mitigation Plan                                                                                     | Owner |

| WiFi/app fails to connect to ESP32 | Technical  | Medium     | High   | Test with direct browser requests, simplify request format, ensure stable hotspot connection  | Team  |
| Structure misalignment causes jamming  | Mechanical | Medium | High   | Adjust alignment, increase tolerances, test with mockups before final assembly | Team|
| Servo does not move correctly due to mechanical error | Mechanical | High  | High | Recalibrate angles, adjust linkage/thread tension, reposition servo for better torque and alignment | Team  |
| Power supply insufficient for multiple servos | Technical  | Medium     | High   | Use external 5V supply and common ground, test load before full integration | Team|
| Timing issues causing delayed or missed actions | Technical  | Medium | Medium | Reduce blocking delays, optimize code, test timing under real conditions | Team  |

## 15.2 Biggest Unknown Right Now
What is the single biggest uncertainty in your project at this stage?

**Response:**  
`[The pulling out of the pins in a straight line]`

---

# 16. Testing and Playtesting

## 16.1 Technical Testing Plan

| What Needs Testing | How You Will Test It | Success Condition |
|---|---|---|
| `[Bluetooth connection]` | `[Connect wiring system to the ESP32 and run the code. Connect to WiFi and open the App. The goal is to test the working of the buttons]` | `[If the App opens the correct interface and the buttons make the servos move as intended. DONE.]` |
| `[Mechanism movement]` | `[Test codes were made for each component, so running them would make us test the servo's function]` | `[If 3 servos move 45 degree and the 4th moves 125 degrees]` |
| `[Sensor behavior]` | `[The sensor is connectd to the neopixel for feedback, so we run the test code for the ultrasonic and neopixel. We drop a coin in the vicinity of the sensor and make it read the signal]` | `[If the signal is picked up, the neopixel light will change from red to green and then mulitple colours as celebration]` |
| `[App communication]` | `[Coonection to WiFi and button interface working]` | `[If the buttons make the servos move. Same as bluetooth test]` |

## 16.2 Playtesting Plan

| Question | How You Will Check |
|---|---|
| Do players understand what to do? | `[Make them look at the game, and the app and see if they recognize it. If not, and some signifiers to show what is to be done.]` |
| Is the interaction satisfying? | `[See if the players find the gameplay engaging]` |
| Do players want another turn? | `[Make a logic not directly understandable until played so that the player is curious as to how to win.]` |
| Is the challenge balanced? | `[Yes, players feel the game logic makes the challenge balanced.]` |
| Is the response clear and immediate? | `[The response of the neopixel makes the feedback loop complete and immediate.]` |

## 16.3 Testing and Debugging Log

| Date | Problem Found | Type | What You Tried | Result | Next Action |
|---|---|---|---|---|---|
| `[Date]` | `[Describe issue]` | `[Technical / Mechanical / UI / Gameplay]` | `[What you did]` | `[Worked / Partly / Failed]` | `[Next step]` |
| `[Date]` | `[Describe issue]` | `[Type]` | `[What you did]` | `[Result]` | `[Next step]` |

## 16.4 Playtesting Notes

| Tester | What They Did | What Confused Them | What They Enjoyed | What You Will Change |
|---|---|---|---|---|
| `[Teammate]` | `[Tested out the workings of the servos and the response mechanism]` | `[Why the servos weren't moving as intended]` | `[The overall flow of the game and the celevrations. They also liked how the game play was]` | `[The servo angles to match the max tension point to pull the pin out]` |
| `[Teammate and peer]` | `[They played the game but noticed the neopixel going off before time]` | `[The neopixel was lighting up without even getting a win signal and resetting the game]` | `[They liked the animation of the LEDs but they needed to come onyl after the game was won - not after some amount of time]` | `[Change in code version]` |

---

# 17. Build Documentation

## 17.1 Fabrication Process
Describe how the project was physically made.

Include:
- cutting,
- 3D printing,
- assembly,
- fastening,
- wiring,
- finishing,
- revisions.

**Response:**  
The base structure was cut from pine wood to provide a sturdy foundation, while details and layered elements were made using coloured and transparent acrylic cut with a laser cutter. 3D printed parts were used for components like servo mounts and pin holders to ensure proper alignment. The system was assembled by fixing the servos onto the wooden frame and attaching threads from the servo arms to the pins.

Fastening was done using adhesives and cable ties to keep all parts secure while still allowing small adjustments. Wiring involved connecting the servos, ultrasonic sensor, and NeoPixel strip to the ESP32 along with an external power supply, with careful routing to avoid interference with moving parts. Finishing included smoothing edges, aligning acrylic layers, and cleaning up the overall build.

Several revisions were made to improve the pin mechanism—adjusting thread tension, servo angles, and alignment to reduce friction and prevent jamming during operation.

## 17.2 Build Photos
Add photos throughout the project.

Suggested images:
- early sketch,
- prototype,
- electronics testing,
- mechanism test,
- app screenshot,
- final build.

Example:
```md
```

<img width="900" height="1600" alt="Progess picture 1" src="https://github.com/user-attachments/assets/d1261fde-cecf-402f-8846-ae832fb6d367" />
<img width="900" height="1600" alt="Progress pic 2" src="https://github.com/user-attachments/assets/31b5ec32-08ae-4676-bff5-8300ac6c7ae2" />

## 17.3 Version History

| Version | Date | What Changed | Why |
|---|---|---|---|
| `v1` | `[10th april]` | `[Servos moving but with no calibration.Is able to pull the weight of the pin ]` | `[Weight testing in order to see if correct material was being used. ]` |
| `v2` | `[15th april]` | `[Physical model done with holes drilled for servos to sit in. Load sensor had to replaced with a ultrasonic sensor]` | `[Load sensor wasnt calibrating.The servo position was finalised ]` |
| `v3` | `[19th april]` | `[Fully assembled except for the top piece ]` | `[No changes can be made after top piece is attached.]` |

---

# 18. Final Outcome

## 18.1 Final Description
Describe the final version of your project.

**Response:**  
`[The final project is an interactive, app-controlled coin-release game that combines digital input with physical mechanics. A mobile app connects to the ESP32 via WiFi, allowing users to press buttons that trigger servo motors. Each servo pulls a pin using a thread-based mechanism, releasing coins into the system. The coins travel through a layered wooden and acrylic structure into a collection area. An ultrasonic sensor detects when enough coins reach the target, triggering a win condition. Throughout gameplay, a NeoPixel ring provides dynamic visual feedback, including continuous animations and a celebratory sequence upon winning. A continuously moving servo adds an additional layer of motion, making the system feel more alive and engaging.]`

## 18.2 What Works Well
`[Reliable WiFi communication between the app and ESP32 for real-time control]
[Smooth and responsive servo-triggered pin mechanism for coin release]
[Engaging visual feedback through NeoPixel animations and win celebration]`


## 18.3 What Still Needs Improvement
- `[To make the game reset automatically ]`
- `[Make the signal sensor more immediate]`
  

## 18.4 What Changed From the Original Plan
How did the project change from the initial idea?

**Response:**  
`[We had planned to use a load sensor that did not work out and was replaced by an ultrasonic sensor. A few of the placement of the obstacles changed.]`

---

# 19. Reflection

## 19.1 Team Reflection
What did your team do well?  
What slowed you down?  
How well did you manage time, tasks, and responsibilities?

**Response:**  
`[The team worked well in dividing tasks between coding, electronics, and mechanical design, which helped progress happen in parallel. We communicated ideas clearly and adapted quickly when something didn’t work. However, integration slowed us down, especially when combining the app, hardware, and mechanics. Time management was generally effective, but more structured testing and hardware planning early on could have reduced last-minute fixes. ]`

## 19.2 Technical Reflection
What did you learn about:
- electronics,
- coding,
- mechanisms,
- fabrication,
- integration?

**Response:**  
`[In electronics, we learned how to power and manage multiple components like servos, NeoPixels, and sensors using an ESP32, and the importance of a stable external power supply and common grounding. In coding, we understood how to handle real-time communication between the app and the ESP32. Mechanically, we explored how rotational motion from a servo can reliably translate into linear pin movement using threads, and how small alignment issues can cause failure. In fabrication, we learned that material choice and precision (especially with laser-cut acrylic and wood) directly affect performance and durability. Integration taught us that combining all systems is the most challenging part, requiring constant testing and adjustments to ensure everything works together smoothly in real time.
In hindsight, looking at the problems we faced on the way, most of them could have been avoided if we spent more time planning ou the structure and where the electronics would go, so it would work in its most efficient way. But overall, it worked smoothly in the end.]`

## 19.3 Design Reflection
What did you learn about:
- designing for play,
- delight,
- clarity,
- physical interaction,
- player understanding,
- iteration?

**Response:**  
`[We learned that designing for play requires immediate feedback, precise planning and simple interactions. Delight comes from combining physical movement, lights, and unpredictability. Clarity is important so users understand what each action does without explanation. Physical interaction made the experience more engaging compared to purely digital systems. Iteration was key, as small changes in timing, motion, or layout significantly improved usability and overall experience.]`

## 19.4 If You Had One More Week
What would you improve next?

**Response:**  
`[We learned how to connect and control multiple components like servos, sensors, and LEDs using the ESP32. In coding, we understood how to handle real-time inputs from an app and manage timing without blocking the system. Mechanically, we explored how motion from a servo can be translated into linear movement using threads and pins. In fabrication, precision and alignment were important to avoid jamming. Integration taught us that combining all systems is the most complex part and requires continuous testing and adjustment.]`

---

# 20. Final Submission Checklist

Before submission, confirm that:
- [YES] Team details are complete
- [YES] Project description is complete
- [YES] Inspiration sources are included
- [YES] Player journey is written
- [YES] Sketches are added
- [YES] BOM is complete
- [YES] Purchase list is complete
- [YES] Budget summary is complete
- [YES] Mechanical planning is documented if applicable
- [YES] App planning is documented if applicable
- [YES] Code flowchart is added
- [YES] Task breakdown is complete
- [ ] Weekly logs are updated
- [ ] Risk register is complete
- [ ] Testing log is updated
- [YES] Playtesting notes are included
- [YES] Build photos are included
- [YES] Final reflection is written

---

# 21. Suggested Repository Structure

```text
project-repo/
├── README.md
├── images/
│   ├── concept-sketch.jpg
│   ├── labeled-sketch.jpg
│   ├── circuit-diagram.jpg
│   ├── ui-mockup.jpg
│   ├── prototype-1.jpg
│   └── final-build.jpg
├── code/
│   ├── main.py
│   ├── test_code.py
│   └── notes.md
├── cad/
│   ├── models/
│   └── screenshots/
└── docs/
    ├── references.md
    └── extra-notes.md
```

---

# 22. Instructor Review

## 22.1 Proposal Approval
- [ ] Approved to proceed
- [ ] Approved with changes
- [ ] Rework required before proceeding

**Instructor comments:**  
`[Instructor fills this section]`

## 22.2 Midpoint Review
`[Instructor fills this section]`

## 22.3 Final Review Notes
`[Instructor fills this section]`
