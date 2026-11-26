
<div align="center">

# AIIO² Audio Stabilizer

### AS-1 | Dedicated Pre-Master Audio Processor

**STABILIZE. PRESERVE. REFINE.**

![AIIO² Audio Stabilizer](assets/product-render.png)

*Hardware-inspired software. Designed for sound.*

![Version](https://img.shields.io/badge/V1.00-PUBLIC_BETA-D98B35)
![Platform](https://img.shields.io/badge/macOS-14%2B-555555)
![Architecture](https://img.shields.io/badge/Apple_Silicon-Native-555555)
![License](https://img.shields.io/badge/License-Proprietary-555555)
![Price](https://img.shields.io/badge/Public_Beta-Free-39805A)

**Less Digital. More Music.**

<br>

[![Download AS-1](https://img.shields.io/badge/DOWNLOAD_AS--1-FREE_BETA-D98B35?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/AIIO2/AIIO2-Audio-Stabilizer/releases/download/v1.00-beta/AIIO2-AS-1-V1.00-BETA.zip)

**V1.00 BETA · macOS 14+ · Apple Silicon**

[User Manual (PDF)](https://github.com/AIIO2/AIIO2-Audio-Stabilizer/releases/download/v1.00-beta/AS-1-User-Manual.pdf) · [Release Notes](../../releases) · [SHA-256 Checksums](https://github.com/AIIO2/AIIO2-Audio-Stabilizer/releases/download/v1.00-beta/SHA256SUMS.txt)

[Bug Reports](../../issues) · [Community](../../discussions) · [Contact](mailto:RonnyK.1980@icloud.com)

<br>

</div>

---

## Overview

AIIO² Audio Stabilizer (AS-1) is a dedicated standalone 
pre-master audio processor for macOS, combining 
intelligent loudness stabilization, adaptive tempo 
correction, advanced signal analysis and a proprietary 
analog-inspired sound processing architecture.

Its purpose is not to master your music.

**Its purpose is to give your mastering chain a better 
starting point.**

Audio Stabilizer focuses on preserving musical dynamics, 
improving structural consistency and refining unwanted 
digital sound characteristics before the final 
mastering stage.

All audio processing takes place locally on your Mac.

---

## Development Philosophy

The development of Audio Stabilizer began with a 
practical problem encountered while producing music 
with modern generative audio systems.

Even musically impressive productions can contain 
inconsistent loudness, subtle tempo drift, unstable 
spectral textures and unwanted digital harshness.

Conventional mastering processors are not necessarily 
designed to address these problems at their source.

Audio Stabilizer was developed to approach them 
differently.

Rather than forcing audio into a predefined loudness 
target or applying conventional frequency correction, 
its processing architecture is designed to work with 
the existing musical material.

Although originally inspired by the challenges of 
AI-generated music, Audio Stabilizer is designed for 
both conventional and AI-assisted music production.

---

## The Analog Reconstruction Engine

### Beyond Equalization. Beyond Spectral Denoising.

The proprietary Analog Reconstruction Engine (ARE) 
is the sonic core of Audio Stabilizer.

It represents an independently developed processing 
architecture that approaches digital harshness, 
spectral instability and tonal refinement from a 
different perspective.

Conventional equalization primarily modifies the 
amplitude of selected frequency regions.

Many audio enhancement and restoration tools, on 
the other hand, rely on spectral denoising techniques 
that identify and attenuate unwanted spectral components.

While effective for their intended purposes, these 
approaches can also affect desirable musical information, 
particularly when unwanted digital textures are closely 
intertwined with the original sound.

**The ARE approaches this challenge differently.**

Rather than relying solely on frequency correction 
or spectral subtraction, it combines adaptive spectral 
refinement, nonlinear signal shaping, harmonic enrichment 
and analog-inspired processing.

Its algorithms respond to the structure, energy and 
dynamic behavior of the musical signal itself.

The objective is not simply to remove unwanted sound, 
but to refine its digital character while preserving 
musical substance, texture and detail.

Four complementary processors form its sonic 
architecture.

### VELVET

**Weight. Foundation. Substance.**

An analog-inspired nonlinear processing stage designed 
to enhance the perceived body and coherence of the 
low-frequency material.

- Nonlinear line-stage processing
- Push-pull bass architecture
- Subtle harmonic enrichment
- Enhancement of existing low-frequency content
- No synthetic sub-bass generation

VELVET is designed to add substance to the existing 
signal rather than simply boost a predefined 
frequency range.

### SATIN

**Texture. Balance. Character.**

A bipolar midrange refinement processor providing 
continuous control between two complementary sonic 
characteristics.

- Negative values: warmer, VELVET-inspired character
- Positive values: smoother, SILK-inspired character
- Neutral position: bypass
- Signal-dependent processing rather than conventional EQ

SATIN allows the user to refine the character of 
the midrange without relying on conventional 
equalization curves alone.

### SILK

**Clarity without unnecessary harshness.**

SILK uses adaptive, multi-stage spectral processing 
designed to address unwanted digital roughness, 
unstable spectral textures and excessive harshness.

Its approach differs from conventional noise-profile-based 
spectral denoising.

Rather than treating unwanted spectral components solely 
as noise to be removed, SILK evaluates the behavior 
and structure of the musical signal itself.

- Adaptive multi-stage spectral refinement
- Signal-dependent processing
- Transient and harmonic protection
- Reduction of perceived digital harshness
- Preservation of musical character
- No conventional noise profile required

This approach is particularly relevant when unwanted 
digital textures are embedded within the musical 
material itself rather than existing as a clearly 
separable noise source.

SILK is not intended to reconstruct missing original 
audio information or replace specialized audio 
restoration tools.

### THERMIONIC / TUBE

**Harmonics. Depth. Analog-inspired character.**

A dynamic nonlinear processing architecture inspired 
by the sonic characteristics of classic vacuum tube 
circuits.

Four distinct tube-inspired profiles are available:

| Profile | Description |
|---|---|
| 12AU7 | Original tube-inspired character profile |
| 12AX7 | Original tube-inspired character profile |
| 6SN7 | Original tube-inspired character profile |
| 300B | Original tube-inspired character profile |

The processing incorporates dynamic saturation, 
shared stereo energy behavior, sag-inspired response 
and adaptive mid/side characteristics.

These profiles are original digital interpretations, 
not measured reproductions of specific hardware units.

### Processing Architecture

The ARE incorporates:

- Adaptive spectral processing
- Nonlinear harmonic processing
- Residual-based processing architecture
- Signal-dependent processing
- Transient and harmonic protection
- 8x oversampling in designated nonlinear stages
- Double-precision calculations in relevant DSP stages
- Independent module activation
- Global ARE bypass

The ARE is neither a conventional equalizer nor a 
traditional spectral denoiser.

It represents a dedicated approach to musical 
signal refinement.

Specialized spectral denoising and restoration remain 
valuable when dealing with severe artifacts, persistent 
noise or heavily damaged recordings.

Where necessary, these processes can complement 
Audio Stabilizer within the wider production and 
mastering workflow.

**The goal is not simply to remove unwanted sound.**

**The goal is to preserve the music while refining 
its digital character.**

---

## Loudness Stabilizer

Unlike conventional loudness normalization or dynamic 
range compression, the Loudness Stabilizer is designed 
to reduce unwanted long-term level inconsistencies 
between comparable musical sections.

It does not force the entire track toward a fixed 
LUFS target.

Dedicated arrangement protection helps preserve 
intentional musical contrasts, including:

- Introductions
- Outros
- Breaks
- Beatless sections

Adjustable analysis, correction, smoothing and gain 
limits allow the stabilization behavior to be adapted 
to the individual production.

Musical dynamics remain an essential part of the 
production rather than an obstacle to be eliminated.

---

## BPM Stabilizer

Designed to address subtle tempo drift and unwanted 
timing inconsistencies while retaining musical movement.

- Automatic tempo analysis
- Automatic or manually selected target BPM
- Adjustable correction strength
- Tempo smoothing
- Groove preservation controls
- Transient protection
- Optional pitch preservation
- Manual timing curve editing

The BPM Stabilizer is not intended to quantize every 
musical event to a rigid timing grid.

Its purpose is to improve long-term tempo consistency 
while respecting the musical characteristics of 
the performance.

---

## Precision Audio Analysis

Audio Stabilizer provides an integrated environment 
for evaluating both the original and processed signal.

- Real-time spectrum analyzer
- Configurable spectrum resolution and display scales
- Stereo field visualization
- Stereo correlation analysis
- Momentary and short-term loudness
- Playback-integrated loudness
- True-peak metering
- Peak and RMS metering
- Interactive signal visualization
- Editable gain and timing curves
- Level-matched A/B monitoring

Monitoring tools allow processing decisions to be 
evaluated both visually and by listening.

The MATCH function is intended for monitoring only 
and does not affect the exported audio.

---

## Pre-Master Check

A dedicated offline analysis system evaluates the 
original mix or processed output before export.

The Pre-Master Check focuses on:

- Available headroom
- True-peak levels
- Typical signal peaks
- Potential overload conditions
- Mono compatibility
- Output gain recommendations

The processed output can be evaluated with the 
selected export sample rate taken into account.

The objective is to identify technical conditions 
that may affect subsequent mastering.

A successful check is not a guarantee of mastering 
quality or universal playback compatibility.

---

## User Interface

![Audio Stabilizer Interface](assets/interface.png)

A hardware-inspired rack interface brings all major 
processing and analysis modules together in a single 
workspace.

- Dedicated processing modules
- Independent module activation
- Interactive signal and correction curves
- Analog-inspired meters and controls
- Factory and user settings presets
- Integrated playback and export controls

No plugin chains. No unnecessary windows. 
No complex routing.

---

## Audio Export

| Feature | Specification |
|---|---|
| Output format | Stereo WAV |
| Integer PCM | 16-bit / 24-bit |
| Floating-point | 32-bit float |
| Sample rate | Original or selectable |
| Selectable sample rates | 44.1–192 kHz |
| Dithering | Optional TPDF for integer PCM |
| Output gain | Adjustable |
| Fade-in / Fade-out | Adjustable |
| Fade characteristics | Multiple selectable curves |

The exported audio is intended for further mastering 
or other subsequent production stages.

---

## Built for Pre-Mastering

Audio Stabilizer deliberately avoids conventional 
final-stage mastering processors.

It does not contain:

- A conventional mastering equalizer
- A multiband mastering compressor
- A loudness maximizer
- A brickwall limiter

These creative and technical decisions remain with 
the mastering engineer.

Audio Stabilizer is not a mastering suite.

It is designed to provide a more consistent, refined 
and musically coherent signal before the creative 
and technical decisions of mastering begin.

**Prepare the signal. Preserve the music. 
Let mastering do the rest.**

---

## System Requirements

| Requirement | Specification |
|---|---|
| Operating system | macOS 14 or later |
| Processor | Apple Silicon |
| Architecture | Native ARM64 |
| Application type | Standalone |
| Audio processing | Stereo |
| Export format | WAV |
| Internet connection for audio processing | Not required |
| Account or activation | Not required |

Intel Macs, Windows and Linux are not currently 
supported.

---

## Free Public Beta

### V1.00 PUBLIC BETA — Build 10001

The first public version of AIIO² Audio Stabilizer 
is provided free of charge under its proprietary 
beta license.

- Free for personal music production
- Free for professional and commercial music production
- No subscription
- No account required
- No online activation
- No scheduled beta expiration
- Proprietary, closed-source software
- Local audio processing
- Comprehensive English User Manual included

This is an early public release. Unexpected behavior 
and compatibility limitations may occur.

Please retain your original audio files and verify 
processed exports before using them in production.

Future versions may be offered under different 
licensing terms.

---

## Download

<div align="center">

[![Download AS-1](https://img.shields.io/badge/DOWNLOAD_AS--1-FREE_BETA-D98B35?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/AIIO2/AIIO2-Audio-Stabilizer/releases/download/v1.00-beta/AIIO2-AS-1-V1.00-BETA.zip)

**V1.00 PUBLIC BETA**

macOS 14+ · Apple Silicon · Build 10001

[User Manual (PDF)](https://github.com/AIIO2/AIIO2-Audio-Stabilizer/releases/download/v1.00-beta/AS-1-User-Manual.pdf) · [SHA-256 Checksums](https://github.com/AIIO2/AIIO2-Audio-Stabilizer/releases/download/v1.00-beta/SHA256SUMS.txt) · [All Releases](../../releases)

</div>

### Release Package Contents

- AS-1.app
- AS-1-User-Manual.pdf
- README.txt
- LICENSE.txt
- PRIVACY-NOTICE.txt
- RELEASE-NOTES.txt
- THIRD-PARTY-NOTICES.txt

### macOS Security Notice

The Public Beta is ad-hoc signed but is not currently 
notarized by Apple.

macOS may therefore display security warnings when 
opening the application for the first time.

Please consult the included installation instructions 
and only obtain the application from its official 
release page.

SHA-256 checksums are provided to verify download 
integrity. A matching checksum does not independently 
establish software safety.

Do not globally disable macOS security protections 
or override malware warnings.

---

## Documentation

The comprehensive English User Manual covers:

- Installation and initial setup
- Complete interface overview
- Individual processing modules
- Analog Reconstruction Engine
- Signal processing principles
- Audio analysis and metering
- Gain and timing curve editing
- Pre-Master Check
- Audio export
- Technical specifications
- Recommended production workflows

The manual is included in the official release package 
and is also available as a separate PDF download.

<div align="center">

[![User Manual](https://img.shields.io/badge/USER_MANUAL-PDF-D98B35?style=for-the-badge&logo=readthedocs&logoColor=white)](https://github.com/AIIO2/AIIO2-Audio-Stabilizer/releases/download/v1.00-beta/AS-1-User-Manual.pdf)

</div>

---

## Privacy

Audio processing is performed locally.

The application is designed to operate without:

- Cloud-based audio processing
- User registration
- Online activation
- Subscription requirements

Audio files do not need to be uploaded to an 
external service for processing.

Further information is provided in the Privacy Notice 
included in the release package.

---

## Feedback & Community

Audio Stabilizer is an independently developed 
audio software project.

Constructive feedback, listening experiences, 
compatibility reports and bug reports are welcome.

The Public Beta is an opportunity to evaluate the 
software across different musical styles, production 
workflows and listening environments.

### Bug Reports

Please use [GitHub Issues](../../issues) to report 
technical problems.

When reporting an issue, please include:

- Application version
- macOS version
- Mac model or processor
- Relevant processing settings
- A description of the unexpected behavior
- Steps to reproduce the issue, if possible

Please do not publicly upload copyrighted or 
confidential audio material without permission.

### Community Discussions

Use [GitHub Discussions](../../discussions) to share:

- Listening experiences
- Preferred ARE settings
- Production workflows
- Feature suggestions
- General questions
- Constructive feedback

---

## About This Repository

This is the official distribution, documentation 
and support repository for AIIO² Audio Stabilizer.

Audio Stabilizer is proprietary, closed-source 
software.

The application source code and proprietary DSP 
algorithms are not publicly distributed.

This repository provides official application releases, 
product documentation, release notes, bug reporting 
and community support.

The automatically generated source archives provided 
by GitHub contain only the public repository files, 
not the application source code.

The free Public Beta does not imply that future 
versions will necessarily be distributed free of charge.

---

## Developer & Contact

**Ronny Künniger**

Independent audio software development  
Germany

Contact: [RonnyK.1980@icloud.com](mailto:RonnyK.1980@icloud.com)

---

<div align="center">

**AIIO² AUDIO LAB**

**STABILIZE. PRESERVE. REFINE.**

*Less Digital. More Music.*

Copyright © 2026 Ronny Künniger.

</div>
