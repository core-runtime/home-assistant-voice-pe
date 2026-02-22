# Home Assistant Voice PE - PopCulture WakeWord Edition

[![Version](https://img.shields.io/badge/version-v1.1--dev-orange.svg)](https://github.com/core-runtime/home-assistant-voice-pe/tree/v1.1-dev)
[![ESPHome](https://img.shields.io/badge/ESPHome-2026.2.0+-green.svg)](https://esphome.io)

A custom fork of the [Home Assistant Voice: Preview Edition](https://www.home-assistant.io/voice-pe/) featuring pop culture-inspired wake words.

---

## Version 1.1-dev (Development)

**Branch:** `v1.1-dev`  
**Status:** Development / Testing

### Included Wake Words (18 Custom)

| Wake Word | Model ID | Added |
|-----------|----------|-------|
| **Alfred** | `alfred` | v1.0 |
| **Skynet** | `skynet` | v1.0 |
| **TARS** | `tars` | v1.0 |
| **Alexa** | `alexa` | v1.0 |
| **Claude** | `claude` | v1.0 |
| **Computer** | `computer` | v1.0 |
| **Cortana** | `cortana` | v1.0 |
| **Einstein** | `einstein` | v1.0 |
| **Gemini** | `gemini` | v1.0 |
| **Linus** | `linus` | v1.0 |
| **Isaac** | `isaac` | v1.0 |
| **Arnie** | `arnie` | v1.1 |
| **Axel** | `axel` | v1.1 |
| **Harley Quinn** | `harley_quinn` | v1.1 |
| **Hey Alexa** | `hey_alexa` | v1.1 |
| **Hey Alfred** | `hey_alfred` | v1.1 |
| **Hey Isaac** | `hey_isaac` | v1.1 |
| **House** | `house` | v1.1 |

### Built-in Wake Words (3)

- `okay_nabu` - Official Home Assistant wake word
- `hey_jarvis` - Built-in
- `hey_mycroft` - Built-in
- `stop` - Internal stop command

**Total:** 21 wake words

---

## Installation

### Stable (v1.0.0)

```yaml
packages:
  PopCulture WakeWord Edition: github://core-runtime/home-assistant-voice-pe/home-assistant-voice.yaml@v1.0.0
```

### Development (v1.1-dev)

```yaml
packages:
  PopCulture WakeWord Edition: github://core-runtime/home-assistant-voice-pe/home-assistant-voice.yaml@v1.1-dev
```

---

## Changelog

### v1.1-dev (In Progress)
- Added 7 new pop culture wake words:
  - arnie, axel, harley_quinn
  - hey_alexa, hey_alfred, hey_isaac
  - house
- Total: 18 custom + 3 built-in = 21 wake words

### v1.0.0 (2026-02-22)
- Initial stable release
- 11 custom pop culture wake words
- All models hosted on GitHub raw URLs
- Tested & compiles successfully
- Memory validated with headroom for expansion

---

## Memory Stats

| Version | Flash Used | DIRAM Used | Wake Words |
|---------|-----------|-----------|------------|
| v1.0.0 | 3.4 MB / 16 MB | 36% | 14 |
| v1.1-dev | TBD | TBD | 21 |

---

## Sources

- **Wake word models:** [TaterTotterson/microWakeWords](https://github.com/TaterTotterson/microWakeWords)
- **Original firmware:** [esphome/home-assistant-voice-pe](https://github.com/esphome/home-assistant-voice-pe)
- **Documentation:** [voice-pe.home-assistant.io](https://voice-pe.home-assistant.io/)

---

## Maintained By

[core-runtime](https://github.com/core-runtime)

*PopCulture WakeWord Edition - Because your home assistant should answer to the names you love.*
