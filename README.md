<p align="center"><img src="/assets/img/Javascript_Drum_Kit.png" alt="Javascript Drum Kit"></p>

## About This Project

![GitHub last commit](https://img.shields.io/github/last-commit/crashbug01/30DaysJSChallenge-Day1)<br>

This project is an interactive web-based drum kit developed using Vanilla JavaScript. It serves as the Day 1 entry for the "30 Days of JavaScript" challenge by Wes Bos.

The primary objective of this project is to practice DOM manipulation by dynamically updating the user interface in response to keyboard events and audio triggers.

### Key Learning Objectives

The development of this application focused on the following technical concepts:

- DOM Manipulation: Accessing and modifying HTML elements in real-time to provide visual feedback.

- Event Listeners: Capturing user input via keyboard events to trigger specific functions.

- Data Attributes: Using data-key attributes to link keyboard keys with their respective audio files and visual elements.

### How It Works

- Input Detection: The application listens for a keydown event on the window.

- Element Selection: JavaScript identifies the audio element and the visual key element associated with the pressed key.

- State Update: The script adds a CSS class to the element to trigger an animation and plays the corresponding audio file.

- Cleanup: Transition events are used to automatically remove the visual styling once the animation completes.

### Usage

To play the drum kit, press the key displayed on the screen that corresponds to the desired sound. The interface will highlight the active key and play the associated drum sample instantly.
