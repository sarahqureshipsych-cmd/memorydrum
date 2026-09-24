# Digital Memory Drum Simulator

An interactive, 3D web-based simulation of the Paired-Associate Learning (PAL) Memory Drum, a classic psychology research apparatus pioneered by American psychologist Dr. Mary Whiton Calkins in 1894.

## About the Project

The Memory Drum is a historical psychological testing device used to measure learning and memory retention through paired-association learning experiments. This upgraded digital simulation recreates the physical mechanics of the original laboratory equipment—complete with a 10-sided 3D rotating cylinder and interactive mechanical levers—allowing researchers and students to experience strict serial learning trials from home.

## Key Features

* **True 3D Cylinder Mechanics:** A mathematically accurate 10-sided polygon drum that physically rotates in 3D space, eliminating Ebbinghaus distraction errors by hiding upcoming words.
* **11 Unique Stimulus Sets:** Includes the original college laboratory list plus 10 additional randomized lists to reduce psychological bias and exposure manipulation between trials.
* **Interactive Mechanical Levers:** Realistic drag-and-pull UI levers to engage the different experimental phases.
* **Automated Recall Flaps:** Simulated metal casing and mechanical shutters that open and close to reveal or conceal the response variables based on the active trial phase.
* **Visual LED Timer:** Real-time digital display tracking the 2-second exposure durations and 0.5-second rotational pauses.
* **Responsive Design:** Optimized for both desktop laboratory environments and mobile devices.

## How It Works

### The Apparatus
The simulator houses 11 distinct stimulus sets. Each set contains 10 paired associations (e.g., a nonsense syllable like "ZEK" paired with a sensible word like "Apple"). To prevent the serial position effect, the active list is automatically shuffled via a Fisher-Yates algorithm at the start of every new phase.

### Experimental Phases

**1. Learning Phase**
* Activated by pulling the top lever.
* Both the stimulus (nonsense syllable) and response (word) are visible.
* Mechanical flaps open fully to reveal both sides of each pair.
* Each pair is exposed for exactly 2 seconds, followed by a 0.5-second mechanical rotation pause.

**2. Recall Phase**
* Activated by pulling the bottom lever.
* Only the stimulus (left side) is visible. The response side is physically concealed by the closed right shutter.
* Tests the participant's ability to recall the association before the drum steps forward.
* Maintains the strict 2-second exposure and 0.5-second rotation timing.

**3. Stop / Reset**
* Halts the current session, resets the mechanical levers, and returns the drum to the 0-degree "READY" state.

## Getting Started

Visit the live web application: [Digital Memory Drum](https://sarahqureshipsych-cmd.github.io/memorydrum/)

**Conducting a Trial:**
1. Select one of the 11 Stimulus Sets from the left module.
2. Click or pull the **"1. Learning Phase"** lever to begin initial memory encoding.
3. Once the list completes, click or pull the **"2. Recall Phase"** lever to test retention.
4. Click **"Stop / Reset"** at any time to abort the current trial.

## Repository Structure

```text
memorydrum/
├── README.md                          # Project documentation
├── index.html                         # Main application (HTML + CSS + 3D JavaScript logic)
├── sitemap.xml                        # SEO sitemap
├── favicon.png                        # Transparent site icon
└── googlee446513605abb7fb.html        # Google verification file
