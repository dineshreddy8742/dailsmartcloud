# Dailsmart AI

**The ultimate open-source voice AI platform** - Dailsmart helps you build your own voice agents with an easy drag-and-drop workflow builder. It's the fastest way to build voice AI agents - from zero to working bot in under 2 minutes.

- **100% open source**, self-hostable platform - no vendor lock-in.
- **Full control & transparency** - every line of code is open, with built-in AI testing personas and flexible LLM/TTS/STT integration.

## 🚀 Get Started

##### Download and setup Dailsmart on your Local Machine

```bash
docker compose up --pull always
```

> **Note**
> First startup may take 2-3 minutes to download all images. Once running, open http://localhost:3010 to create your first AI voice assistant!

### 🎙️ Your First Voice Bot

1. **Open Dashboard**: Launch http://localhost:3010 on your browser
2. **Choose Call Type**: Select **Inbound** or **Outbound** calling.
3. **Name Your Bot**: Use a short two-word name (e.g., _Lead Qualification_).
4. **Describe Use Case**: In 5–10 words.
5. **Launch**: Your bot is ready! Open the bot and click **Web Call** to talk to it.

## Features

### Voice Capabilities

- Telephony: Built-in telephony integration like Twilio, Vonage, Vobiz, Cloudonix (easily add others)
- Languages: English support (expandable to other languages)
- Custom Models: Bring your own TTS/STT models
- Real-time Processing: Low-latency voice interactions

### Developer Experience

- Zero Config Start: Auto-generated API keys for instant testing
- Python-Based: Built on Python for easy customization
- Docker-First: Containerized for consistent deployments
- Modular Architecture: Swap components as needed

### Testing & Quality

- LoopTalk (Beta): Create AI personas to test your voice agents
- Workflow Testing: Test specific workflow IDs with automated calls
- Real-world Simulation: AI personas that mimic actual customer behavior

## Deployment Options

For self-hosted deployments, make sure to update the `docker-compose.yaml` and configure the environment variables as described in the documentation.

## 📄 License

Dailsmart AI is licensed under the BSD 2-Clause License.
