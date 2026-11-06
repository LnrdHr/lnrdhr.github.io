---
layout: default
title: Leonard Jedvaj | Embedded Systems & Software Developer
description: Embedded C, STM32 firmware, real-time audio DSP, AI automation, and web development.
---

# Leonard Jedvaj

**Embedded Systems & Software Developer**  
*STM32 firmware · Real-time DSP · AI automation*

I'm a Computer Engineering master's student at the University of Rijeka, Croatia. My main interests are embedded firmware, real-time systems, and signal processing, including applications in the space and aerospace industries. I also build AI-enabled software and web applications.

[GitHub](https://github.com/LnrdHr) · [Email](mailto:jedvajleonard@gmail.com) · [Upwork](https://www.upwork.com/freelancers/~015f01954465be138e) · [Freelancer](https://www.freelancer.com/u/lerojed)

## Selected Projects

### STM32 Polyphonic Sound Synthesizer

**Embedded C · STM32F411 (ARM Cortex-M4) · STM32CubeIDE · DSP · DMA · MIDI · I2S · I2C**

![STM32F411 synthesizer hardware prototype with LCD and control circuitry](assets/stm32-synthesizer-prototype.jpg)

Designed and built a real-time digital audio synthesizer for my 2026 bachelor's thesis.

- Implemented **6-voice polyphony**, with two wavetable oscillators per voice, using direct digital synthesis (DDS).
- Developed audio processing with ADSR envelopes, an additional fade-out state to reduce retrigger clicks, LFO modulation, and a first-order IIR low-pass filter.
- Integrated MIDI input over UART, analog controls via ADC/DMA, a 2×16 LCD over I2C, and a PCM5102 DAC over I2S.
- Used circular DMA and half-buffer processing for continuous **16-bit audio at approximately 44 kHz**; verified the audio output and I2S signals with an oscilloscope.

[Source code and project demos](https://github.com/LnrdHr/stm-synthesizer) · [Oscilloscope capture](assets/stm32-synthesizer-waveform.png)

### AI-Enhanced Polling Application

**Python · Django · LangGraph · OpenAI API · Tavily · Langfuse · JavaScript**

Built a web application combining polls and results tracking with an AI chatbot. Implemented LangGraph tool routing, web search, in-memory conversation context, and JSON endpoints for the web interface.

[Source code and demo](https://github.com/LnrdHr/django)

### Alternative Tic-Tac-Toe

**React · JavaScript · Vite**

Extended the classic game with custom rules, including freezing squares, overwriting moves, and move-history navigation.

[Source code and demo link](https://github.com/LnrdHr/my-first-react)

## Industry Experience

**AI Automation Engineer Intern — VivaDrive, Poland**  
*Aug–Dec 2025*

- Developed fleet/financial lead research workflows using **Django, n8n, and Selenium**, including LLM-assisted document analysis.
- Built an EV charging-site discovery and assessment tool using **Overpass API** and **OpenRouteService**.
- Evaluated an AI speech-to-text pipeline using **LangChain** and **Langfuse**.

**Game & Web Developer Intern — Extramus, Italy**  
*Jul–Sep 2024*

- Developed a visual novel with **Godot** and tested an HR platform built with **Laravel**.

## Technical Skills

**Embedded & DSP:** C, STM32CubeIDE, ARM Cortex-M4, DMA, UART, I2C, I2S, ADC, MIDI, digital signal processing, oscilloscope testing.  
**Software & AI:** Python, Django, LangGraph, LangChain, Langfuse, n8n, Selenium, JavaScript, React, Node.js, REST APIs, Godot.

## Education

**University of Rijeka — Faculty of Engineering**  
Master's studies in Computer Engineering (in progress). Bachelor's thesis (2026): *Sound Synthesizer Implemented on an STM32 Microcontroller*.

## Contact

For embedded systems, software development, or AI automation opportunities: **[jedvajleonard@gmail.com](mailto:jedvajleonard@gmail.com)**.
