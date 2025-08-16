# SkySignals

A comprehensive collection of radio frequency resources, signal intelligence
tools, software-defined radio configurations, amateur radio utilities, ADS-B
tracking, and electromagnetic spectrum analysis tools.

This repository contains professional-grade radio frequency programming files
for multiple radio manufacturers and models, featuring comprehensive regional
configurations with built-in safety features and legal compliance. All
configurations are CHIRP-compatible and organized by manufacturer, model, and
geographic region.

## 🚀 Quick Start

1. **[Download CHIRP](https://chirp.danplanet.com)** software
2. **Install programming cable drivers** (Prolific or CH340)
3. **Select your region** from available configurations below
4. **Follow our
   [Programming Guide](docs/radio-configs/baofeng-uv5r/programming.md)**

## 📻 Supported Radio Models

Currently available configurations:

### 🔵 Baofeng

- **UV-5R Series** - Complete regional configurations with enhanced safety
  features
  - UV-5R, UV-5RA, UV-5RB, UV-5RC, UV-5RD, UV-5RE, UV-5RTP, BF-F8HP
  - All firmware versions supported

_Additional manufacturers and models will be added as configurations become
available._

## 📍 Current Regional Coverage

All configurations are organized by geographic regions for easy navigation and
scalability.

### 🇺🇸 United States

#### Northeast Region

- **[Boston, MA](radios/baofeng/uv-5r/regions/us/northeast/boston-ma/)** -
  Complete Boston metropolitan area with MBHSR interoperability (📊 config.csv •
  💾 config.img • 📋 metadata.json)

#### Southeast Region

- **[Asheville, NC](radios/baofeng/uv-5r/regions/us/southeast/asheville-nc/)** -
  Complete Western NC mountain region with federal land coverage (📊 config.csv
  • 📋 metadata.json)
- **[Charlotte, NC](radios/baofeng/uv-5r/regions/us/southeast/charlotte-nc/)** -
  Complete Charlotte metropolitan area with regional coordination (📊 config.csv
  • 📋 metadata.json)
- **[Denver, NC](radios/baofeng/uv-5r/regions/us/southeast/denver-nc/)** -
  Complete multi-county Lake Norman area configuration (📊 config.csv • 📋
  metadata.json)
- **[Waxhaw, NC](radios/baofeng/uv-5r/regions/us/southeast/waxhaw-nc/)** -
  Complete Union County border region configuration (📊 config.csv • 📋
  metadata.json)

### 📁 Configuration Structure

Each regional directory contains:

- **`config.csv`** - CHIRP-compatible channel configuration with safety features
- **`config.img`** - Pre-programmed radio memory image (where available;
  currently only for Boston, MA)
- **`metadata.json`** - Configuration metadata, version info, and geographic
  data
- **`README.md`** - Comprehensive region-specific documentation and channel
  guides

## 🔗 Documentation & Resources

📖 **[Complete Documentation](docs/)** - Full guides, references, and technical
details

### Essential Guides

- **[FM Broadcast Guide](docs/radio-configs/baofeng-uv5r/fm-broadcast.md)** – FM
  radio programming details

- **[Programming Guide](docs/radio-configs/baofeng-uv5r/programming.md)** -
  Step-by-step CHIRP programming instructions
- **[Troubleshooting](docs/radio-configs/baofeng-uv5r/troubleshooting.md)** -
  Common issues and solutions
- **[Channel Organization](docs/reference/channel-organization.md)** - Standard
  frequency allocation patterns
- **[Service Abbreviations](docs/reference/service-abbreviations.md)** –
  Abbreviation key for channel lists

### Regional Documentation

- **[Boston Guide](docs/radio-configs/baofeng-uv5r/boston-ma.md)** - Detailed
  Boston metropolitan area information
- **[Asheville Guide](docs/radio-configs/baofeng-uv5r/asheville-nc.md)** -
  Western NC mountain region details
- **[Charlotte Guide](docs/radio-configs/baofeng-uv5r/charlotte-nc.md)** -
  Charlotte metropolitan area information
- **[Denver Guide](docs/radio-configs/baofeng-uv5r/denver-nc.md)** - Lake Norman
  multi-county details
- **[Waxhaw Guide](docs/radio-configs/baofeng-uv5r/waxhaw-nc.md)** - Union
  County border region information

### Legal & Compliance

- **[Legal, Licensing, and Regulatory Information](docs/legal/index.md)** -
  Important legal, licensing, and compliance information
- **[Frequency Resources](docs/reference/frequency-resources.md)** - Official
  frequency coordination sources

## ⚙️ Technical Specifications

- **🔧 Format**: CHIRP-compatible CSV with enhanced metadata
- **📻 Supported Radios**: Baofeng UV-5R series (all variants and firmware
  versions)
- **📡 Frequency Coverage**: VHF 136-174 MHz • UHF 400-520 MHz
- **📊 Channel Capacity**: Up to 128 programmable memory channels
- **🎛️ Features**: CTCSS/DCS tones, skip flags, proper duplex offsets, legal
  compliance
- **🗂️ Metadata**: JSON format with versioning, coordinates, coverage areas,
  safety info
- **🔄 Updates**: Version-controlled configurations with update tracking
- **🏗️ Expandable**: Structured for easy addition of new manufacturers and models

## 🔒 Built-in Safety Features

### Duplex Protection System

All configurations include **automatic transmission prevention** on restricted
frequencies:

- **✅ Listen-Only Channels**: All public safety, government, and commercial
  frequencies use duplex setting `off` to **prevent accidental transmission**
- **✅ Licensed Channels**: Ham radio repeaters and GMRS channels maintain
  proper duplex settings for authorized users
- **⚠️ User Responsibility**: Despite built-in protections, **always verify**
  channel authorization before transmitting

### Transmission Safety Guidelines

Even with duplex protection, **exercise extreme caution**:

- **🚨 NEVER** press PTT (Push-To-Talk) on unfamiliar channels
- **🔍 VERIFY** your license covers the frequency before transmitting
- **📖 READ** channel comments carefully - many are **[LISTEN ONLY]**
- **⚖️ UNDERSTAND** that illegal transmission can result in severe penalties

## 🤝 Contributing

We welcome contributions to expand regional coverage and improve configurations!

- **📍 New Regions**: Submit configurations for additional cities/regions
- **🔄 Updates**: Report frequency changes or corrections
- **📖 Documentation**: Improve guides and regional information
- **🐛 Issues**: Report bugs or configuration problems

See our **[Contributing Guidelines](docs/radio-configs/index.md#contributing)**
for detailed submission instructions.

---

## ⚖️ Legal Notice

**⚠️ IMPORTANT: Educational Use Only**

This repository is provided for **educational, informational, and lawful
monitoring purposes only**. Many frequencies are **listen-only** and require
proper licensing for transmission.

### Built-in Safety Features

- ✅ **Duplex Protection**: Listen-only channels use `duplex: off` to prevent
  accidental transmission
- ✅ **License Indicators**: Clear marking of license requirements in channel
  comments
- ✅ **Legal Compliance**: Configurations follow FCC regulations and best
  practices

### User Responsibilities

- 🔍 **Verify Authorization**: Always confirm you're licensed before
  transmitting
- 📖 **Read Channel Comments**: Pay attention to [LISTEN ONLY] and license
  requirements
- ⚖️ **Follow Laws**: Comply with all federal, state, and local regulations
- 🚨 **Emergency Use**: Understand legal exceptions for emergency communications

**Unauthorized transmission may result in significant penalties.** See our
complete **[Legal, Licensing, and Regulatory Information](docs/legal/index.md)**
for full terms and liability information.

---

**Part of SkySignals Repository** - Radio, SDR, Signal Intelligence & Spectrum
Analysis Tools\
**Last Updated**: August 15, 2025 • **Version**: 2025.1\
**Compatible with**: CHIRP (all recent versions) • Multiple radio manufacturers

📖 **[Documentation](docs/)** • ⚖️
**[Legal, Licensing, and Regulatory Information](docs/legal/index.md)** • 🤝
**[Contributing](docs/radio-configs/index.md#contributing)**
