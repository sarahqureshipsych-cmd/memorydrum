# Memory Drum Simulator

An interactive web-based simulation of the Paired Association Learning (PAL) Memory Drum, a classic psychology research apparatus pioneered by American psychologist Dr. Mary Whiton Calkins in 1894.

## About the Project

The Memory Drum is a historical psychological testing device used to measure learning and memory retention through paired-association learning experiments. This digital simulation recreates the mechanical experience of the original device, allowing researchers and students to understand how classic psychology experiments were conducted.

## Key Features

* **Interactive Learning Phase:** View both stimulus (nonsense syllable) and response (sensible word) pairs.
* **Recall Phase:** Test memory by hiding the response while showing the stimulus.
* **Mechanical Animation:** Simulated metal flaps that open and close to reveal/conceal information.
* **Visual Timer:** LED-style display showing exposure duration.
* **Responsive Design:** Works seamlessly on desktop and mobile devices.
* **Historical Accuracy:** Based on the original 1894 apparatus design.

## How It Works

### The Apparatus

The simulator displays 10 paired associations:

* ZEK → Apple
* TOR → Clock
* RIM → Table
* FUG → Book
* LEP → Tree
* DAX → Dog
* VEK → Lamp
* MIP → River
* JOR → Pen
* TUS → Star

### Learning Phases

**1. Learning Phase (All Up)**
* Both the stimulus (nonsense syllable) and response (word) are visible.
* Mechanical flaps open to reveal both sides of each pair.
* Helps establish initial memory associations.
* Each pair is displayed for 2 seconds.
* 0.5-second pause between pairs.

**2. Recall Phase (Right Closed)**
* Only the stimulus (left side) is visible.
* The response side is covered by closed flaps.
* Tests the participant's ability to recall the association.
* Participant attempts to recall the response before flaps open.
* Same timing as learning phase.

**3. Stop / Reset**
* Halts the current session and returns to ready state.

## Getting Started

### Using the Simulator

1. **Visit the Web Application:** Open the hosted version at https://sarahqureshipsych-cmd.github.io/memorydrum/
2. **Start a Session:** 
   * Click "1. Learning Phase (All Up)" to begin learning the pairs.
   * Click "2. Recall Phase (Right Closed)" to test your memory.
   * Click "Stop / Reset" to stop and reset the timer.
3. **Observe the Results:** 
   * The LED display shows elapsed time for each pair.
   * Pairs are presented in random order each session.
   * When all pairs are complete, the display shows "END".

## Repository Structure

```text
memorydrum/
├── README.md # This file
├── index.html # Main application (HTML + CSS + JavaScript)
├── sitemap.xml # SEO sitemap
└── googlee446513605abb7fb.html # Google verification file
