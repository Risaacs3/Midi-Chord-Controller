# Midi-Chord-Controller
Teensy 4.0 MIDI chord controller with STL case files and full build video

Overview
This is a custom USB MIDI chord controller built with a Teensy 4.0 and a 3D-printed enclosure. It lets you play full chord progressions with simple button presses instead of traditional piano fingerings. Perfect for producers who want fast, intuitive chord ideas.

How it works
Each arcade button triggers a diatonic chord based on the current musical key and major/minor mode.
The Teensy reads all inputs, calculates the correct chord intervals, sends MIDI note-on messages over USB, and shuts notes off cleanly when the button is released.
The device appears as a standard USB MIDI input in any DAW.

Controls
Arcade Buttons
Eight buttons for diatonic chords (I through vii° depending on mode)

Key Selector Knob
Rotary encoder or key-select control
Changes the musical key in real time
Shifts all chord buttons to the correct scale tones

Octave Up / Down Buttons
Move all chord outputs up or down entire octaves
Useful for bass voicings or high-register pads

Major / Minor Mode Switch
Instantly swaps between major scale chords and natural minor scale chords
All button intervals update automatically

Files Included
Midi chord controller 1 — Teensy 4.0 code (.ino)
Midi Box.stl — main enclosure
Midi Top Plate.stl — top control plate for buttons, knob, and switches

Usage
Load the .ino file onto a Teensy 4.0 using Arduino IDE or Teensy Loader
Plug into your computer — shows up as a USB MIDI device
Pick a key, choose major or minor, set octave, and start playing chords

Full Build Video
[PASTE YOUR YOUTUBE LINK HERE]
