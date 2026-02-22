# Home Assistant Voice: Preview Edition (Custom Fork)

This is a fork of the [Home Assistant Voice: Preview Edition](https://www.home-assistant.io/voice-pe/) ESPHome source code with additional custom wake words.

## Custom Wake Words

This fork includes three additional locally-hosted microWakeWord models:

| Wake Word | Model ID | Source |
|-----------|----------|--------|
| **Alfred** | `alfred` | `models/alfred.json` |
| **Skynet** | `skynet` | `models/skynet.json` |
| **TARS** | `tars` | `models/tars.json` |

Models sourced from [TaterTotterson/microWakeWords](https://github.com/TaterTotterson/microWakeWords).

### Default Wake Words (Still Included)

- `okay_nabu` - Official Home Assistant wake word
- `hey_jarvis` - Built-in
- `hey_mycroft` - Built-in
- `stop` - Internal stop command

## Setup

See [the official documentation](https://voice-pe.home-assistant.io/) for set up and troubleshooting.

If you need to re-install the firmware, [use this installer](https://esphome.github.io/home-assistant-voice-pe/).

## Building

To build this firmware with the custom wake words:

```bash
esphome compile home-assistant-voice.yaml
```

## Upstream

- **Original repo:** [esphome/home-assistant-voice-pe](https://github.com/esphome/home-assistant-voice-pe)
- **Fork maintained by:** [core-runtime](https://github.com/core-runtime)
