# Tone Forge

[![Community Edition: Free](https://img.shields.io/badge/Community_Edition-Free-16a34a?style=for-the-badge)](https://hannes-software.com/tone-forge/download/)
[![Linux](https://img.shields.io/badge/Linux-Desktop-f59e0b?style=flat-square&logo=linux)](https://hannes-software.com/tone-forge/download/) [![Windows](https://img.shields.io/badge/Windows-Desktop-2563eb?style=flat-square&logo=windows)](https://hannes-software.com/tone-forge/download/) [![Local first](https://img.shields.io/badge/Workflow-Local--first-7c3aed?style=flat-square)](https://hannes-software.com/tone-forge/)

> Patch, play, and refine a modular synthesizer in a live graph.

Free Community Edition of a modular software synthesizer with a patch graph, audio and modulation routing, filters, envelopes, and effects.

Wire oscillators, filters and modulators in an editable graph. Audition a note as you work, read the output waveform, and keep the effects chain visible beneath the patch.

**Tone Forge Community Edition is free to download and use.** Use the core workflow locally and decide from real output.

[Download Community Edition](https://hannes-software.com/tone-forge/download/) · [Product guide](https://hannes-software.com/tone-forge/) · [Help](https://hannes-software.com/tone-forge/help/) · [Report a bug](https://github.com/hannes-wan/tone-forge-official/issues/new?template=bug_report.yml)

## Download Tone Forge 0.1.1

| Platform | Package | Use it when |
| --- | --- | --- |
| Linux x64 (APPIMAGE) | [tone-forge-0.1.1-linux-x64.AppImage](https://github.com/hannes-wan/tone-forge-official/releases/download/v0.1.1/tone-forge-0.1.1-linux-x64.AppImage) | Portable Linux desktop package |
| Linux x64 (DEB) | [tone-forge-0.1.1-linux-x64.deb](https://github.com/hannes-wan/tone-forge-official/releases/download/v0.1.1/tone-forge-0.1.1-linux-x64.deb) | Debian, Ubuntu, Mint, and compatible systems |
| Linux x64 (RPM) | [tone-forge-0.1.1-linux-x64.rpm](https://github.com/hannes-wan/tone-forge-official/releases/download/v0.1.1/tone-forge-0.1.1-linux-x64.rpm) | Fedora, RHEL, openSUSE, and compatible systems |
| Windows x64 | [tone-forge-0.1.1-windows-x64-setup.exe](https://github.com/hannes-wan/tone-forge-official/releases/download/v0.1.1/tone-forge-0.1.1-windows-x64-setup.exe) | Guided Windows installer |

Checksums, installation notes, and the complete platform matrix live on the [official download page](https://hannes-software.com/tone-forge/download/).

## System requirements

- **Windows:** Windows 10 or Windows 11 on x64.
- **Linux:** a mainstream x64 distribution with glibc 2.35 or newer, such as Ubuntu 22.04+, Debian 12+, Fedora, or openSUSE (AppImage, DEB, and RPM packages).
- **Disk space:** a few hundred megabytes free for the application and its bundled resources.

## Why Tone Forge exists

Tone Forge is a desktop modular synthesizer for sound design, synthesis lessons and making your own patches on Windows x64 and Linux x64.

> **Edition boundary:** The technical sections below describe the complete product surface and can include optional licensed workflows. The exact free Community Edition scope is listed separately below.

### Build a patch for the sound you need

Three ways to use the graph, the parameter inspector and the output monitor together.

### Patch the signal path

Follow each oscillator through the mixer, filter and output. Inspect a module by selecting it in the graph.

### Design the motion

Edit the contour of a multisegment function generator and route it to a parameter such as filter cutoff.

### Audition while you edit

Hold C4 or play through a configured MIDI input. Compare parameter changes against the same note and watch the stereo monitor.

### Process the output

Add a stereo effect after the synth graph. Open its controls in the details panel and compare the sound with processing bypassed.

### Give a bass patch an audible attack

- Use a short rising segment on cutoff so the upper harmonics appear at the start of the note.
- Close the filter more slowly and hold the note long enough to check how much of its body stays audible.

### Create a wide sustained texture

- Mix two oscillators and use a small fine-tune offset to hear their interaction.
- Audition the patch by itself before placing reverb on the stereo output. Use the release tail to choose a decay.

### Teach signal flow from a working example

- Select a module and keep its details beside the cables so the class can trace where sound and modulation go.
- Make a single filter edit between two C4 auditions and ask students to describe which part of the spectrum changed.

## Try a first workflow

### Trace the audio path and establish a reference note

Find the source, mixer, filter, and output in the starting sound. Select the oscillator and open its controls while following the audio connections through the graph. Start the audio engine and audition C4 at a comfortable level. Check the output monitor as you hold and release the same note. If the output stays quiet, trace the route to the output and check the source and gain levels before making more edits.

### Hear a change in the source and filter

Change the selected oscillator's waveform and play C4 again. The notes used for the comparison stay the same, so you can hear how the harmonic content of the source changes. Try the filter cutoff next and compare a few positions. Choose a setting that gives you an audible change with a modest turn. Check the edges into and out of the filter so the selected module is in the audio path you are actually hearing.

### Audition an envelope and an output effect

Connect an envelope to a modulation input on the filter or gain control. Compare a short attack with a slow one on the same note, then vary the release separately. Check the envelope's destination and modulation amount if the comparison is hard to hear. Once the dry patch is playing correctly, add a single output effect and audition a short phrase. Leave space between notes so you can hear what the effect does after the note ends.

## Community Edition is genuinely useful


Expanded workflows require an effective license. See the official product page for current licensing availability.

## See the real desktop workflow

### Live filter audition

![Live filter audition — Tone Forge](https://hannes-software.com/assets/tone-forge/screenshots/live-filter-audition-01.webp)

Two saw oscillators feed a mixer and low-pass filter. The monitor on the right shows the output of a held C4.

### Oscillators and audio routing

![Oscillators and audio routing — Tone Forge](https://hannes-software.com/assets/tone-forge/screenshots/oscillator-graph-01.webp)

Signal starts at the oscillators, passes through the mixer and filter, and reaches the output module.

### Six-segment function generator

![Six-segment function generator — Tone Forge](https://hannes-software.com/assets/tone-forge/screenshots/function-envelope-01.webp)

The graph shows the modulation lead to the filter. The inspector shows the envelope and individual curve segments.

### Reverb on the output bus

![Reverb on the output bus — Tone Forge](https://hannes-software.com/assets/tone-forge/screenshots/output-reverb-01.webp)

A reverb block can sit after synthesis. The oscillator and filter connections remain visible above the effects lane.

## Local-first by design

Tone Forge is a desktop workflow. Your working files stay on the machine unless you deliberately export or share them. The product page documents the exact capability boundary so the focused workflow can be evaluated on real evidence.

## Documentation

- [Build and Audition Your First Modular Synth Patch](https://hannes-software.com/tone-forge/help/build-a-first-modular-patch/)
- [Compare dry and wet output in Tone Forge](https://hannes-software.com/tone-forge/help/compare-dry-and-wet-synth-effects/)
- [Hear filter cutoff and resonance in a modular synth](https://hannes-software.com/tone-forge/help/filter-cutoff-and-resonance/)
- [Shape a synth patch with an envelope](https://hannes-software.com/tone-forge/help/shape-a-patch-with-an-envelope/)

## Frequently asked questions

> **Community scope:** Community Edition includes patch editing and auditioning. Saving and opening sound files or working with a sound library require an effective license.

<details>
<summary><strong>What is Tone Forge?</strong></summary>

Tone Forge is a standalone desktop modular synthesizer. You connect oscillators, filters, gain stages and modulators in a graph and play the result through an output effects chain.

</details>

<details>
<summary><strong>Can I change the synth patch while audio is running?</strong></summary>

Yes. Start audio, select an oscillator or filter, and edit its controls in the details panel. Audition the same C4 before and after a change to hear what it did.

</details>

<details>
<summary><strong>Can I use a MIDI keyboard?</strong></summary>

The standalone editor has MIDI input controls under Perform. You can also use the Hold to audition C4 button without a keyboard.

</details>

<details>
<summary><strong>Which Tone Forge installer should I download?</strong></summary>

Download the Windows x64 setup (.exe) for Windows 10 or later. This direct installer is unsigned. On Linux x64, choose the DEB, RPM, or portable AppImage.

</details>

<details>
<summary><strong>Which Tone Forge installer includes the VST3 plugin?</strong></summary>

The Windows x64 installer can install the standalone synthesizer, the VST3 instrument, or both. The Linux AppImage, DEB and RPM contain the standalone synthesizer.

</details>

## Community, support, and security

- Bugs: [open a structured bug report](https://github.com/hannes-wan/tone-forge-official/issues/new?template=bug_report.yml)
- Ideas: [request a focused workflow improvement](https://github.com/hannes-wan/tone-forge-official/issues/new?template=feature_request.yml)
- Product help: [documentation and troubleshooting](https://hannes-software.com/tone-forge/help/)
- Private support: [support@hannes-software.com](mailto:support@hannes-software.com)
- Security reports: follow [SECURITY.md](SECURITY.md); do not post sensitive files, credentials, patient data, or private captures in public issues.

## Official repository

This is the official public distribution and community repository for Tone Forge: verified release links, current screenshots, documentation routes, issue intake, and security guidance. Product development happens in a private workspace; public issues here are the right place to report reproducible product behavior and request focused improvements.
