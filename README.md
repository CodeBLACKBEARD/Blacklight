# Blacklight
*Illuminating Development, No Barriers*

![Blacklight Logo](logo.png)

**A free, open-source lighting preset manager for Roblox developers - built for the community, by the community.**

## What is Blacklight?

Blacklight is a lighting preset management tool that helps developers save, organize, and share lighting configurations in Roblox Studio. You create your lighting setups using Studio's native tools, then use Blacklight to preserve and share those configurations.

### Key Features

- **Preset Management**: Save your current lighting settings as reusable presets
- **Auto-Save System**: Never lose your configurations with intelligent background saving  
- **Code-String Sharing**: Share lighting setups instantly with simple copy-paste strings
- **Community-Driven**: No built-in bloat - import only the presets you want
- **Version Compatibility**: Backwards-compatible code-string system that evolves with the tool

## The Code-String System

Blacklight's sharing system uses compressed data strings:

```
1;Day (Bright);Kiro;0.8;35;62;100;...
```

Each semicolon separates data points: **generation version**, name, author, brightness, RGB values, etc.

**Generation System:**
- First number indicates code-string format version
- Ensures backwards compatibility as the plugin evolves
- Old presets always work with newer plugin versions
- New exports always use the latest format

**Benefits:**
- Share presets anywhere text can be pasted
- No file uploads or special platforms needed
- Transparent, readable format
- Future-proof compatibility system

## Quick Start

1. Install Blacklight in Roblox Studio
2. Set up your lighting using Studio's native lighting tools
3. Use Blacklight to save your configuration as a preset
4. Export and share your presets with others, or import community presets

### Importing Presets

Copy any Blacklight code-string and paste it into the import UI. Your lighting will instantly match the preset configuration.

### Creating Presets

Design your lighting setup in Studio, then use Blacklight to save and export it as a code-string to share.

## Why Free and Open Source?

> *"Every paywall, no matter how small, divides people between those who can access opportunity and those who can't."*

Blacklight was built on the principle that powerful development tools shouldn't be gatekept behind artificial barriers. Whether you're a hobbyist learning the ropes or a professional studio, you deserve access to quality tools.

This project represents a commitment to:
- **Equal Opportunity**: Everyone deserves access to professional-grade tools
- **Community Collaboration**: Better tools come from shared knowledge
- **Transparent Development**: Open source means no hidden agendas
- **Sustainable Growth**: Building together instead of competing apart

## Community & Preset Sharing

- **Share Presets**: Post your code-strings in discussions or community forums
- **Starter Collection**: Check our [preset repository](link-to-repo) for curated lighting setups
- **Community Contributions**: Contributors can add their presets to the community collection
- **Request Features**: Open an issue with your ideas
- **Contribute Code**: Pull requests welcome
- **Report Bugs**: Help us improve for everyone

## Preset Collection

Our [community preset repository](link-to-repo) includes:
- Basic lighting setups
- Time-of-day variations  
- Atmospheric effects
- Community-contributed configurations

## License

GPL-3.0 - This ensures Blacklight remains free and open for everyone, forever.

## From Kiro

Blacklight evolved from Luminos, a tool I used to charge for. After realizing I was creating the same barriers I criticized in others, I rebuilt it from the ground up as a purely community-focused project.

This isn't just about lighting tools - it's about building a development ecosystem where access isn't determined by wallet size. Every feature, every decision, every line of code serves that mission.

Use it, improve it, share it. Let's build something better together.
