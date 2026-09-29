# Digital Memory Drum Simulator - Cognitive Psychology Apparatus

**Developer:** Sarah Qureshi | Undergraduate Psychology Researcher, Government College for Women M.A. Road

An interactive, free, 3D web-based simulation of the Memory Drum, a classic psychology research apparatus used for Paired-Associate Learning (PAL) experiments—a methodology pioneered by American psychologist Dr. Mary Whiton Calkins in 1894.

---

## Why This Project Exists

Physical memory drums are now largely confined to museum and archive collections. Most are fragile, scarce, or simply unavailable for hands-on laboratory use, which means most psychology students today only ever encounter this foundational apparatus as a textbook photo, never as something they can actually operate. This project was built to close that gap — giving students and researchers a way to experience the real mechanics of serial and paired-associate learning trials from any browser, at no cost.

---

## About the Project

The Memory Drum is a historical psychological testing device used to measure learning and memory retention through paired-association learning experiments. This upgraded digital simulation recreates the physical mechanics of the original laboratory equipment, complete with a 10-sided 3D rotating cylinder and interactive mechanical levers, allowing researchers and students to experience strict serial learning trials from home.

---

## Key Features

- **True 3D Cylinder Mechanics:** A mathematically accurate 10-sided polygon drum that physically rotates in 3D space, reducing distraction effects by hiding upcoming words.
- **11 Unique Stimulus Sets:** Includes the original college laboratory list plus 10 additional randomized lists to reduce psychological bias and exposure manipulation between trials.
- **Interactive Mechanical Levers:** Realistic drag-and-pull UI levers to engage the different experimental phases.
- **Automated Recall Flaps:** Simulated metal casing and mechanical shutters that open and close to reveal or conceal the response variables based on the active trial phase.
- **Visual LED Timer:** Real-time digital display tracking the 2-second exposure durations and 0.5-second rotational pauses.
- **Responsive Design:** Optimized for both desktop laboratory environments and mobile devices.

---

## How It Works

### The Apparatus

The simulator houses 11 distinct stimulus sets. Each set contains 10 paired associations (e.g., a nonsense syllable like "ZEK" paired with a sensible word like "Apple"). To prevent the serial position effect, the active list is automatically shuffled via a Fisher-Yates algorithm at the start of every new phase.

### Experimental Phases

#### Learning Phase

- Activated by pulling the top lever.
- Both the stimulus (nonsense syllable) and response (word) are visible.
- Mechanical flaps open fully to reveal both sides of each pair.
- Each pair is exposed for exactly 2 seconds, followed by a 0.5-second mechanical rotation pause.

#### Recall Phase

- Activated by pulling the bottom lever.
- Only the stimulus (left side) is visible. The response side is physically concealed by the closed right shutter.
- Tests the participant's ability to recall the association before the drum steps forward.
- Maintains the strict 2-second exposure and 0.5-second rotation timing.

#### Stop / Reset

- Halts the current session, resets the mechanical levers, and returns the drum to the 0-degree "READY" state.

---

## Getting Started

Visit the live web application: Digital Memory Drum Simulator

### Conducting a Trial

1. Select one of the 11 Stimulus Sets from the left module.
2. Click or pull the "1. Learning Phase" lever to begin initial memory encoding.
3. Once the list completes, click or pull the "2. Recall Phase" lever to test retention.
4. Click "Stop / Reset" at any time to abort the current trial.

---

## Acknowledgments

### Project Guide

This project was developed under the guidance of **Dr. Malik Roshan Ara**, Assistant Professor and Head, Department of Psychology, Government College for Women, M.A. Road, who reviewed the Simulator:

> "A commendable and creative attempt to translate a basic psychological concept into an interactive learning tool."
>
> "A promising and innovative student initiative."

### Endorsed By

**Dr. Joel Freund**, Professor Emeritus of Psychology at the University of Arkansas, who used Stowe memory drums throughout his own research career, reviewed the simulator:

> "I am impressed by your research and recreation of a memory drum."
>
> "Your interest in the history and seeing your project brought back pleasant memories and made me smile."

### Classroom Adoption

**Dr. Cathy Faye**, Margaret Clark Morgan Executive Director of the Cummings Center for the History of Psychology at The University of Akron, on using the Simulator in her teaching:

> "This is really wonderful! Thank you for sharing it. I'd love to share it in my history of psychology class."

---

## Repository Structure

`memorydrum/` (main project folder)

- `README.md`: Project documentation
- `index.html`: Main application (HTML + CSS + 3D JavaScript logic)
- `sitemap.xml`: SEO sitemap
- `favicon.png`: Transparent site icon
- `googlee446513605abb7fb.html`: Google verification file

---

## License & Copyright

© 2026 Sarah Qureshi. All Rights Reserved.

This software is the intellectual property of Sarah Qureshi. This project may not be monetized, sold, or distributed commercially.
