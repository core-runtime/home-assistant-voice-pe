# Home Assistant Voice PE - PopCulture WakeWord Edition

[![Version](https://img.shields.io/badge/version-v1.0.0-blue.svg)](https://github.com/core-runtime/home-assistant-voice-pe/releases/tag/v1.0.0)
[![ESPHome](https://img.shields.io/badge/ESPHome-2026.2.0+-green.svg)](https://esphome.io)

A custom fork of the [Home Assistant Voice: Preview Edition](https://www.home-assistant.io/voice-pe/) featuring pop culture-inspired wake words.

---

## Version 1.0.0 (Stable)

**Release Date:** February 22, 2026

### Included Wake Words (11 Custom)

| Wake Word | Model ID | Type |
|-----------|----------|------|
| **Alfred** | `alfred` | Custom |
| **Skynet** | `skynet` | Custom |
| **TARS** | `tars` | Custom |
| **Alexa** | `alexa` | Custom |
| **Claude** | `claude` | Custom |
| **Computer** | `computer` | Custom |
| **Cortana** | `cortana` | Custom |
| **Einstein** | `einstein` | Custom |
| **Gemini** | `gemini` | Custom |
| **Linus** | `linus` | Custom |
| **Isaac** | `isaac` | Custom |

### Built-in Wake Words (3)

- `okay_nabu` - Official Home Assistant wake word
- `hey_jarvis` - Built-in
- `hey_mycroft` - Built-in
- `stop` - Internal stop command

**Total:** 14 wake words

---

## Memory Stats (v1.0.0)

| Section | Used | Free | Total |
|---------|------|------|-------|
| **Flash** | 3.4 MB | 12.6 MB | 16 MB |
| **DIRAM** | 123 KB (36%) | 218 KB (64%) | 342 KB |

---

## Installation

### Device YAML

Add this to your ESPHome device configuration:

```yaml
packages:
  PopCulture WakeWord Edition: github://core-runtime/home-assistant-voice-pe/home-assistant-voice.yaml@v1.0.0
```

Or use `main` branch for latest stable:

```yaml
packages:
  PopCulture WakeWord Edition: github://core-runtime/home-assistant-voice-pe/home-assistant-voice.yaml@main
```

### Building

```bash
esphome compile home-assistant-voice.yaml
```

---

## Changelog

### v1.0.0 (2026-02-22)
- Initial stable release
- 11 custom pop culture wake words
- All models hosted on GitHub raw URLs
- Tested & compiles successfully
- Memory validated with headroom for expansion

---

## Sources

- **Wake word models:** [TaterTotterson/microWakeWords](https://github.com/TaterTotterson/microWakeWords)
- **Original firmware:** [esphome/home-assistant-voice-pe](https://github.com/esphome/home-assistant-voice-pe)
- **Documentation:** [voice-pe.home-assistant.io](https://voice-pe.home-assistant.io/)

---

## Maintained By

[core-runtime](https://github.com/core-runtime)

*PopCulture WakeWord Edition - Because your home assistant should answer to the names you love.*
