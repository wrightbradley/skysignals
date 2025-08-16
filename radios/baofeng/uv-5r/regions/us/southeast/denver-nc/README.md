# Denver, NC - Baofeng UV-5R Configuration

Complete configuration for Denver, North Carolina and surrounding Lake Norman
area, covering Lincoln, Cabarrus, Iredell, and Gaston counties.

## 🔒 Built-in Safety Features

This configuration includes **automatic transmission prevention** on all
restricted frequencies:

- **✅ All listen-only channels** use duplex setting `off` to prevent accidental
  transmission
- **✅ Licensed channels** maintain proper duplex settings for authorized users
- **⚠️ Always verify** your authorization before transmitting on any channel

## Files

- **`Baofeng_UV-5R_DenverNC_Channels.csv`** - CHIRP-compatible channel list

## Quick Reference

| Service            | Channels   | License              | Notes                              |
| ------------------ | ---------- | -------------------- | ---------------------------------- |
| Amateur Radio      | 1-9, 20-23 | Ham License Required | VHF/UHF repeaters, simplex         |
| Fire Services      | 30-36      | Listen Only          | Multi-county fire departments      |
| EMS Services       | 37-40      | Listen Only          | Lincoln, Cabarrus County EMS       |
| Police & Emergency | 41-57      | Listen Only          | Multi-county law enforcement       |
| Interoperability   | 58-68      | Listen Only          | Regional coordination channels     |
| Weather Services   | 70-73      | Listen Only (Skip)   | NOAA weather radio                 |
| Public Service     | 80-82      | Listen Only          | Aviation, public service, railroad |
| Personal Radio     | 90-91      | FRS/GMRS             | Family/personal communications     |
| Legacy Repeaters   | 100-104    | Ham License Required | Additional amateur radio           |

## Coverage Area

**Primary**: Denver, Lincoln County, Lake Norman area\
**Extended**: Cabarrus, Iredell, Gaston counties\
**Regional**: Charlotte metro area periphery

## Key Services

### Emergency Services

- **Lincoln County Fire** - Dispatch and tactical channels (30-32)
- **Denver Fire Department** - Local fire services (33)
- **Multi-County Fire Coordination** - Cabarrus, Iredell, Lake Norman (34-36)
- **Lincoln County EMS** - Emergency medical services (37-39)
- **Cabarrus County EMS** - Regional medical services (40)

### Law Enforcement

- **Lincoln County Sheriff** - Primary and tactical channels (41-43)
- **Multi-County Sheriff** - Gaston, Iredell, Cabarrus (44-46)
- **NC State Highway Patrol** - State law enforcement (47)
- **NC Wildlife Resources** - Conservation enforcement (48)
- **Municipal Police** - Statesville, Mooresville, Huntersville, Cornelius,
  Davidson (53-57)

### Amateur Radio

- **W4CYA** - Cabarrus Amateur Radio Club
- **W4OAX** - Oak Ridge repeater
- **W4VEC** - Volunteer Examiner repeater
- **K4RDU** - Research Triangle link
- **K4LKN** - Lake Norman Amateur Radio Club
- **NC4EC** - Emergency Coordinator repeater

### Emergency Management

- **Multi-County Emergency Management** - Lincoln, Gaston, Iredell, Cabarrus
  (49-52)
- **NC State Agencies** - Highway Patrol, Wildlife Resources
- **Regional Interoperability** - VTAC, UTAC, 8-Call systems

## Regional Coverage

### Lincoln County

- **Fire/EMS Dispatch** - 154.280 (Tone: 203.5)
- **Sheriff Primary** - 453.100/150 (Tone: 100.0)
- **Emergency Management** - 155.160 (Tone: 203.5)

### Cabarrus County

- **Fire Coordination** - 460.550 (Tone: 107.2)
- **EMS Services** - 460.125 (Tone: 167.9)
- **Sheriff Operations** - 460.450 (Tone: 131.8)
- **Emergency Management** - 155.250 (Tone: 131.8)

### Iredell County

- **Fire/EMS** - 453.200 (Tone: 127.3)
- **Sheriff Operations** - 460.350 (Tone: 146.2)
- **Emergency Management** - 155.220 (Tone: 146.2)

### Gaston County

- **Sheriff Operations** - 460.200 (Tone: 141.3)
- **Emergency Management** - 155.190 (Tone: 141.3)

### Municipal Services

- **Statesville PD** - 154.860 (Tone: 146.2)
- **Mooresville PD** - 460.075 (Tone: 123.0)
- **Huntersville PD** - 453.775 (Tone: 127.3)
- **Cornelius PD** - 460.025 (Tone: 94.8)
- **Davidson PD** - 453.850 (Tone: 107.2)

## Interoperability Channels

### Tactical Coordination

- **TACALL** (151.145) - Tactical calling frequency
- **VTAC 11/12** - VHF tactical channels
- **UTAC 41/42** - UHF tactical channels
- **8-Call/8-Tac** - Regional interoperability system

### Regional Coordination

- **Regional** (453.550) - Multi-county coordination
- **Mutual Aid** (453.800) - Cross-jurisdictional assistance

## Aviation Services

- **Lake Norman Airpark** - 122.900 (AM mode)
- **Aviation Emergency** - 121.500 (AM mode)

## Weather Services

NOAA Weather Radio frequencies with skip flags:

- **162.475** - Primary Charlotte weather coverage
- **162.400** - Secondary coverage
- **162.500** - Regional weather
- **162.550** - Extended coverage area

## Transportation

- **Norfolk Southern Railroad** - 160.950 MHz

## Programming Notes

1. **Multi-County Tones**: Different CTCSS tones for each county system
2. **Interoperability**: Complete VTAC/UTAC and 8-Call systems programmed
3. **Municipal Coverage**: All Lake Norman area police departments
4. **Regional Coordination**: Cross-county mutual aid channels
5. **Amateur Radio**: Strong Lake Norman area amateur coverage

!!! warning "Legal Notice" Emergency service frequencies are **listen only**.
Transmission without authorization is illegal and subject to significant
penalties.

## Download

Configuration files are located in the `Denver-NC/` directory of the repository.

---

⚠️ **Listen Only** - Emergency service frequencies are for monitoring only. See
**[Legal, Licensing, and Regulatory Information](../../../../../../docs/legal/index.md)**
for complete terms.
