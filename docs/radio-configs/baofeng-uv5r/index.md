# Baofeng UV-5R Configuration

CHIRP-compatible programming files for the Baofeng UV-5R handheld radio series.

_For other supported radios, see the
[main Radio Configurations index](../index.md)._

## Overview

The Baofeng UV-5R is a popular dual-band (VHF/UHF) handheld radio that can be
programmed using CHIRP software. Our configurations provide comprehensive
channel lists organized by service type.

## Quick Start

1. **Download CHIRP** from [chirp.danplanet.com](https://chirp.danplanet.com)
2. **Install Cable Drivers** (Prolific or CH340)
3. **Download Configuration** for your region
4. **Program Radio** using our [Programming Guide](programming.md)

## Available Configurations

### Regional Configurations

- **[Boston, MA](boston-ma.md)** - 50 channels with MBHSR interoperability
- **[Charlotte, NC](charlotte-nc.md)** - 85 channels with regional coordination
- **[Denver, NC](denver-nc.md)** - 80 channels with multi-county coverage
- **[Asheville, NC](asheville-nc.md)** - 80 channels with mountain/federal
  coverage
- **[Waxhaw, NC](waxhaw-nc.md)** - 80 channels with Union County and regional
  coverage

### Other Features

- **[Receiving FM Broadcast Radio](fm-broadcast.md)** - How to use your Baofeng
  UV-5R to listen to FM music/news stations

## Technical Specifications

The Baofeng UV-5R supports VHF (136-174 MHz) and UHF (400-520 MHz) operation
with up to 128 programmable channels. FM broadcast reception is available in VFO
mode.

## File Types

- **`.csv`** - Channel list (importable to CHIRP)
- **`.img`** - Complete radio memory image

## General Programming Notes

- CTCSS/DCS tones are configured where required for repeater access.
- Weather channels are marked with skip flags for scanner operation.
- Power levels are optimized for service type and battery conservation.
- Aviation frequencies are set to AM mode where required.

## Requirements

- **CHIRP Software** (free download)
- **USB Programming Cable** (2-pin Kenwood-style)
- **Driver Installation** (Windows/Mac/Linux)

<!-- dprint-ignore-start -->
!!! info
    Compatible with all UV-5R variants including UV-5RA, UV-5RB, UV-5RC, UV-5RD, UV-5RE, UV-5R+
<!-- dprint-ignore-end -->

## Download

Configuration files for each region are located in their respective directories.
For example:

```bash
radios/baofeng/uv-5r/regions/us/northeast/boston-ma/latest/
radios/baofeng/uv-5r/regions/us/southeast/charlotte-nc/latest/
radios/baofeng/uv-5r/regions/us/southeast/denver-nc/latest/
radios/baofeng/uv-5r/regions/us/southeast/asheville-nc/latest/
radios/baofeng/uv-5r/regions/us/southeast/waxhaw-nc/latest/
```

Each directory contains a `config.csv` (CHIRP-compatible channel list) and
`metadata.json` (configuration metadata).
