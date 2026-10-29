<!--
  Redstone AI — project README
  Status: active development / prototype stage
-->

<div align="center">

# REDSTONE AI

### One assistant. More natural ways to get things done.

An experimental AI-powered interactive companion designed to make everyday interactions simpler by bringing different ways of interacting with technology into one accessible experience.

<br/>

![Status](https://img.shields.io/badge/status-in%20development-orange?style=flat-square)
![Platform](https://img.shields.io/badge/platform-Raspberry%20Pi%20Zero%202%20W-red?style=flat-square&logo=raspberrypi&logoColor=white)
![Focus](https://img.shields.io/badge/focus-AI%20%7C%20Embedded%20Systems%20%7C%20Accessibility-2563EB?style=flat-square)

<br/>

**[Project Journal](JOURNAL.md) · [Repository](https://github.com/saadlgzkrnokia-cyber/Redstone-AI)**

</div>

---

## The idea

Technology is everywhere, but completing one simple task can still mean switching between several devices, apps, buttons and interfaces. This can be especially frustrating for people who have difficulty using conventional interfaces.

**Redstone AI explores a different approach:** a single interactive assistant that brings voice, touch and other natural forms of interaction together to help people accomplish everyday tasks more easily.

The goal is not to add another complicated gadget. It is to make interacting with technology feel more straightforward.

## What I'm building

Redstone AI is planned as a compact, interactive device with multiple ways to communicate with its user.

| Interaction | Purpose | Current status |
|---|---|---|
| Voice input | Give commands and interact naturally | Microphone tested; audio capture works, sensitivity needs improvement |
| Audio output | Receive spoken responses and feedback | Speaker acquired; integration in progress |
| Touchscreen | Use a visual, touch-friendly interface | Planned |
| Camera / gestures | Explore hand-gesture interaction | Planned |
| AI assistance | Understand requests and help with tasks | Under development |

*This is an evolving prototype. Planned capabilities are not presented as completed features.*

## Hardware

The current prototype is built around the **Raspberry Pi Zero 2 W**, chosen as the main computer for its compact size and low power consumption.

| Component | Role | Status |
|---|---|---|
| Raspberry Pi Zero 2 W | Main computing unit | Acquired |
| INMP441 I2S microphone | Voice input | Tested; input works, but is currently quiet |
| Speaker | Audio output | Acquired |
| Audio amplifier | Drive the speaker | To be integrated |
| 5-inch touchscreen | Visual and touch interface | Planned |
| Camera | Explore hand-gesture recognition | Planned |
| Battery and power management | Portable operation | Under consideration |

The hardware may change as testing, power requirements and the enclosure design progress.

## System approach

The project is exploring a split-computing architecture instead of forcing every task to run on the Raspberry Pi.

- **Raspberry Pi:** device-side interaction, audio hardware and lightweight control.
- **Laptop:** development, testing and potentially heavier local processing.
- **Online services:** optional capabilities that may benefit from network access.

The final division of responsibilities is still being evaluated. The aim is to keep the device responsive while respecting the Pi Zero 2 W's limited resources.

## Development roadmap

- [x] Define the project concept and choose the initial hardware direction.
- [x] Acquire the Raspberry Pi Zero 2 W, INMP441 microphone and speaker.
- [x] Get microphone audio capture working.
- [x] Start the functional analysis and define the project's service functions.
- [ ] Improve microphone input quality and integrate audio output.
- [ ] Select and integrate the touchscreen.
- [ ] Evaluate camera-based hand-gesture interaction.
- [ ] Design and assemble the portable enclosure.
- [ ] Develop and test the interaction software.
- [ ] Integrate the hardware and software into a working prototype.

Progress will be updated as features are actually tested and completed.

## Project journal

I keep a development journal documenting decisions, experiments, progress and things that still need fixing.

**[Read JOURNAL.md →](JOURNAL.md)**

## About the project

Redstone AI is an independent student engineering project by **Saad Zakaria**, developed in Morocco.

It brings together interests in artificial intelligence, embedded systems, electronics and practical problem-solving.

---

<div align="center">

### Built step by step. Tested in the real world.

*Ideas are easy. Making them work is the project.*

</div>
