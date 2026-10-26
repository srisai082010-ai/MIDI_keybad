# MIDI_keyboard
his is my custom MIDI keypad PCB designed in KiCad 10. The goal is to build a compact controller for music software using an ESP32-S3-Zero microcontroller, physical switches, capacitive touch keys, and adjustable controls. I designed the schematic and PCB layout as a hands-on electronics project.

## How it is designed to work

- **ESP32-S3-Zero:** The main microcontroller, intended to read inputs and send MIDI messages over USB once firmware is developed.
- **Three Kailh Choc switches (SW1–SW3):** Physical keys for triggering MIDI actions.
- **Seven capacitive touch pads:** Custom copper electrodes that provide additional touch inputs.
- **Rotary encoder (SW5):** A turning control with a push-button function.
- **Two slide potentiometers (RV1 and RV2):** Intended for continuously adjustable MIDI controls.
- **Three RGB LEDs (D1–D3):** Planned visual feedback, placed on the back of the PCB.
 This is my fiishend screenshot of the board:
<img width="1097" height="810" alt="Screenshot 2026-10-25 211558" src="https://github.com/user-attachments/assets/040a378b-3c9b-4e13-9695-24d783228bf4" />

