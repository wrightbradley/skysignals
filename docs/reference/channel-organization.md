# Channel Organization

Standard channel allocation scheme used across SkySignals radio configurations.

## Channel Ranges

### 1-9: Amateur Radio

**License Required**: FCC Amateur Radio License

| Range | Purpose       | Examples                            |
| ----- | ------------- | ----------------------------------- |
| 1-5   | VHF Repeaters | 2M repeaters with offsets and tones |
| 6-7   | UHF Repeaters | 70cm repeaters, DMR, digital modes  |
| 8-9   | Simplex       | National calling frequencies        |

**Features**:

- Proper repeater offsets configured
- CTCSS/DCS tones where required
- Power levels optimized for coverage

### 11-24: Emergency Services

**Listen Only** - No transmission permitted

| Range | Service       | Description                             |
| ----- | ------------- | --------------------------------------- |
| 11-17 | Fire Services | Dispatch, tactical, mutual aid          |
| 18-20 | Special Ops   | Hazmat, rescue, air operations          |
| 21-24 | EMS           | Emergency medical dispatch and tactical |

**Coverage**:

- Primary dispatch channels
- Tactical/fireground operations
- Mutual aid coordination
- Air medical services

### 31-47: Law Enforcement & Emergency Management

**Listen Only** - No transmission permitted

| Range | Service        | Description                              |
| ----- | -------------- | ---------------------------------------- |
| 31-39 | Police         | Municipal, county, state law enforcement |
| 40-43 | Transportation | MBTA, highway, transit police            |
| 44-47 | Federal/State  | Emergency management, federal agencies   |

**Systems**:

- BAPERN (Boston Area Police Emergency Radio Network)
- State police networks
- Federal interoperability channels
- Emergency management coordination

### 51-54: Weather Services

**Listen Only** - Skip flagged for scanning

| Channel | Service         | Purpose                   |
| ------- | --------------- | ------------------------- |
| 51      | Primary Weather | Main NOAA weather radio   |
| 52      | Secondary       | Backup weather service    |
| 53      | Regional        | Regional weather coverage |
| 54      | Extended        | Additional coverage area  |

**Features**:

- Skip flag enabled (S) for scanner operation
- 24/7 weather broadcasts
- Emergency alert capability

### 61-83: Regional Interoperability

**Listen Only** - Specialized coordination channels

| Range | Purpose             | Examples                         |
| ----- | ------------------- | -------------------------------- |
| 61-65 | Primary Interop     | UCALL, UTAC channels             |
| 66-70 | Police Coordination | BAPERN extended channels         |
| 71-75 | Fire Coordination   | Metro fire mutual aid            |
| 76-83 | Regional Services   | Marine, aviation, public service |

**Interoperability Standards**:

- MBHSR (Metro Boston Homeland Security Region)
- Unified Tactical Channels (UTAC)
- Universal Calling Channel (UCALL)
- Cross-agency coordination

### 91-92: Personal Radio Services

**License Status Varies**

| Channel | Service | License       | Power |
| ------- | ------- | ------------- | ----- |
| 91      | FRS     | None Required | 2W    |
| 92      | GMRS    | GMRS License  | 5-50W |

**Usage**:

- Family communications
- Short-range coordination
- Emergency backup
- Business use (GMRS only)

## Tone Systems

### CTCSS (Continuous Tone-Coded Squelch)

**Analog tones** - Prevent interference from other users

Common tones: 88.5, 100.0, 123.0, 131.8, 136.5, 203.5 Hz

### DCS (Digital-Coded Squelch)

**Digital codes** - More tones available, better interference rejection

Common codes: 023, 047, 125, 223, 654

### Tone Usage

- **TX Tone**: Required to access repeater
- **RX Tone**: Squelch only opens for matching tone
- **Split Tones**: Different TX and RX tones

## Power Levels

### Optimization by Service Type

| Service           | Power Setting | Reason                  |
| ----------------- | ------------- | ----------------------- |
| Amateur Repeaters | High (5W)     | Maximum coverage        |
| Amateur Simplex   | Low (1W)      | Battery conservation    |
| Emergency Monitor | Low (1W)      | Extended listening      |
| Weather           | Low (1W)      | Strong local signals    |
| Personal Radio    | Variable      | Depends on range needed |

### Battery Conservation

- Monitor channels: Low power
- Strong local signals: Low power
- Weak/distant signals: High power
- Repeater access: As needed for reliable connection

## Scanning Configuration

### Skip Flags

**S (Skip)**: Weather channels - prevents stopping on weather broadcasts during
scan **P (Priority)**: Emergency channels - checked more frequently during scan

### Scan Lists

Groups of related channels for focused monitoring:

- **Fire/EMS**: Channels 11-24
- **Police**: Channels 31-43
- **Amateur**: Channels 1-9
- **Interop**: Channels 61-83

## Regional Variations

### Frequency Coordination

Different regions use different frequencies for similar services:

- Boston area uses BAPERN for police coordination
- Other areas may use different networks
- Amateur repeater frequencies vary by region

### Channel Numbering

While service types remain consistent, specific channels may vary:

- Local repeater availability
- Regional frequency coordination
- Interference considerations

## Best Practices

### Channel Programming

1. **Consistent Organization** - Same service types in same ranges
2. **Clear Names** - Descriptive channel names (8 characters max)
3. **Proper Tones** - Verify with local repeater directories
4. **Power Optimization** - Test and adjust for your area

### Monitoring Ethics

1. **Listen Only** on emergency services
2. **Don't Retransmit** sensitive information
3. **Respect Privacy** of communications
4. **Emergency Use** - Don't interfere with operations

<!-- dprint-ignore-start -->
!!! tip
    Adapt channel assignments to your local area while maintaining the organizational structure.
<!-- dprint-ignore-end -->
