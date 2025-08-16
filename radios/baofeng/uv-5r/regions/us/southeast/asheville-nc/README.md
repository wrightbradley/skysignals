# Asheville, NC - Baofeng UV-5R Configuration

Complete configuration for Asheville, North Carolina and the Western North
Carolina Blue Ridge Mountain region, covering Buncombe County and surrounding
areas.

## 🔒 Built-in Safety Features

This configuration includes **automatic transmission prevention** on all
restricted frequencies:

- **✅ All listen-only channels** use duplex setting `off` to prevent accidental
  transmission
- **✅ Licensed channels** maintain proper duplex settings for authorized users
- **⚠️ Always verify** your authorization before transmitting on any channel

## Files

- **`Baofeng_UV-5R_AshevilleNC_Channels.csv`** - CHIRP-compatible channel list

## Quick Reference

| Service            | Channels   | License              | Notes                                   |
| ------------------ | ---------- | -------------------- | --------------------------------------- |
| Amateur Radio      | 1-9, 20-23 | Ham License Required | Mountain repeaters, emergency nets      |
| Fire Services      | 30-36      | Listen Only          | AFD, Buncombe County, US Forest Service |
| EMS Services       | 37-40      | Listen Only          | Mission Hospital, Buncombe County EMS   |
| Police & Emergency | 41-52      | Listen Only          | APD, BCSO, state/federal agencies       |
| Aviation           | 53-57      | Listen Only          | Asheville Regional Airport              |
| Interoperability   | 58-68      | Listen Only          | Regional coordination, SKYWARN          |
| Weather Services   | 70-73      | Listen Only (Skip)   | NOAA weather radio                      |
| Public Service     | 80-82      | Listen Only          | Aviation, public service, railroad      |
| Personal Radio     | 90-91      | FRS/GMRS             | Family/personal communications          |
| Legacy Repeaters   | 100-104    | Ham License Required | Emergency/weather nets                  |

## Coverage Area

**Primary**: Asheville, Buncombe County\
**Extended**: Western North Carolina mountains, Blue Ridge Parkway\
**Federal**: Pisgah National Forest, Blue Ridge Parkway

## Key Services

### Emergency Services

- **Asheville Fire Department (AFD)** - Dispatch and tactical channels (30-32)
- **Buncombe County Fire** - County fire dispatch and tactical (33-34)
- **WNC Fire Mutual Aid** - Regional fire coordination (35)
- **US Forest Service** - Federal forest fire protection (36)
- **Mission Hospital EMS** - Hospital-based emergency medical (37)
- **Buncombe County EMS** - County medical services (38-39)
- **WNC EMS Coordination** - Regional medical coordination (40)

### Law Enforcement

- **Asheville Police (APD)** - City police operations (41-43)
- **Buncombe County Sheriff (BCSO)** - County law enforcement (44-46)
- **NC State Highway Patrol** - State law enforcement (47)
- **NC Wildlife Resources** - Conservation enforcement (48)

### Federal Agencies

- **Blue Ridge Parkway** - National Park Service (49)
- **National Forest Service** - Pisgah National Forest (50)
- **US Forest Service** - Fire suppression and management (36)

### Amateur Radio

- **W4AMC** - Asheville Medical Corps repeater
- **W4SKY** - Skyland (Blue Ridge Parkway) repeater
- **W4MOX** - Mount Mitchell repeater
- **W4BRB** - Blue Ridge Parkway repeater
- **NC4AB** - Appalachian Backbone network
- **K4WNC** - Western NC link repeater
- **NC4DMR** - Western NC DMR network

## Mountain Emergency Services

### Fire Protection

- **Asheville FD Dispatch** (154.070) - Tone: 179.9
- **Asheville FD Tactical** (154.130/175) - Tone: 179.9
- **Buncombe County Fire** (453.125/175) - Tone: 203.5
- **WNC Fire Mutual Aid** (453.300) - Tone: 127.3
- **US Forest Service** (168.625) - Tone: 156.7

### Emergency Medical

- **Mission Hospital EMS** (453.500) - Tone: 167.9
- **Buncombe County EMS** (453.550/600) - Tone: 162.2
- **WNC EMS Coordination** (453.650) - Tone: 136.5

### Law Enforcement

- **Asheville PD** (460.125/175/225) - DCS: 174
- **Buncombe County SO** (453.900/950) - Tone: 192.8
- **NC State Highway Patrol** (155.475) - Tone: 156.7

## Federal Land Management

### National Park Service

- **Blue Ridge Parkway** (168.050) - Tone: 167.9
- Covers 469-mile scenic parkway through NC/VA

### US Forest Service

- **Pisgah National Forest** (170.775) - Tone: 156.7
- **Fire Suppression** (168.625) - Tone: 156.7
- Covers extensive mountain wilderness areas

## Aviation Services

### Asheville Regional Airport (AVL)

- **Tower** (121.700) - AM mode
- **Ground** (121.900) - AM mode
- **Approach** (134.050) - AM mode
- **ATIS** (119.425) - AM mode
- **UNICOM** (122.950) - AM mode

## Emergency Communications

### Weather Networks

- **SKYWARN Spotter Net** (147.045) - Tone: 94.8
- Critical for mountain weather reporting
- Severe weather and flash flood warnings

### Emergency Management

- **Buncombe County EM** (155.175) - Tone: 203.5
- **WNC Emergency Management** (155.280) - Tone: 136.5

## Mountain Amateur Radio

### High-Altitude Repeaters

- **Mount Mitchell** (W4MOX 146.760) - Highest peak east of Mississippi
- **Blue Ridge Parkway** (W4BRB 147.000) - Scenic parkway coverage
- **Skyland** (W4SKY 145.370) - Blue Ridge mountain site

### Emergency Networks

- **Asheville Medical Corps** (W4AMC 145.190) - Medical emergency support
- **Appalachian Backbone** (NC4AB 147.360) - Regional connectivity
- **WNC DMR Network** (NC4DMR 444.000) - Digital emergency communications

## Interoperability Systems

### Tactical Channels

- **TACALL** (151.145) - Tactical calling frequency
- **VTAC 11/12** (151.1375/154.4525) - VHF tactical
- **UTAC 41/42** (453.2125/458.2125) - UHF tactical
- **8-Call/8-Tac** (154.755/775.000/800.000) - Regional coordination

### Regional Coordination

- **WNC Regional Coord** (453.700) - Western NC coordination
- **WNC Mutual Aid** (453.750) - Multi-county assistance

## Weather Services

NOAA Weather Radio with skip flags for scanner operation:

- **162.400** - Primary Asheville weather
- **162.475** - Secondary mountain coverage
- **162.500** - Regional weather broadcasts
- **162.525** - Extended mountain coverage

## Transportation

### Railroad

- **Norfolk Southern** (161.010) - Freight operations through Asheville

## Programming Features

1. **Mountain Terrain Optimized** - Repeaters selected for mountain coverage
2. **Federal Land Coverage** - National Forest and Park Service frequencies
3. **Weather Emergency** - SKYWARN spotter network included
4. **Medical Emergency** - Hospital and county EMS systems
5. **Tourism Support** - Blue Ridge Parkway and airport frequencies
6. **Multi-County Coordination** - Western NC regional systems

!!! info "Mountain Considerations" Mountain terrain significantly affects radio
propagation. Repeaters are strategically located on high peaks for maximum
coverage.

## Download

Configuration files are located in the `Asheville-NC/` directory of the
repository.

---

⚠️ **Listen Only** - Emergency service frequencies are for monitoring only. See
**[Legal, Licensing, and Regulatory Information](../../../../../../docs/legal/index.md)**
for complete terms.
