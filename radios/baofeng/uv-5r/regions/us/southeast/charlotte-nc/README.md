# Charlotte, NC - Baofeng UV-5R Configuration

Complete configuration for Charlotte, North Carolina and surrounding Mecklenburg
County area.

## 🔒 Built-in Safety Features

This configuration includes **automatic transmission prevention** on all
restricted frequencies:

- **✅ All listen-only channels** use duplex setting `off` to prevent accidental
  transmission
- **✅ Licensed channels** maintain proper duplex settings for authorized users
- **⚠️ Always verify** your authorization before transmitting on any channel

## Files

- **`Baofeng_UV-5R_CharlotteNC_Channels.csv`** - CHIRP-compatible channel list

## Quick Reference

| Service            | Channels   | License              | Notes                              |
| ------------------ | ---------- | -------------------- | ---------------------------------- |
| Amateur Radio      | 1-9, 20-23 | Ham License Required | VHF/UHF repeaters, simplex         |
| Fire Services      | 30-36      | Listen Only          | CFD, Mecklenburg County Fire       |
| EMS Services       | 37-40      | Listen Only          | MEDIC dispatch and tactical        |
| Police & Emergency | 41-52      | Listen Only          | CMPD, MCSO, State agencies         |
| Aviation           | 53-57      | Listen Only          | Charlotte Douglas Airport          |
| Interoperability   | 58-68      | Listen Only          | Regional coordination channels     |
| Weather Services   | 70-73      | Listen Only (Skip)   | NOAA weather radio                 |
| Public Service     | 80-82      | Listen Only          | Aviation, public service, railroad |
| Personal Radio     | 90-91      | FRS/GMRS             | Family/personal communications     |
| Legacy Repeaters   | 100-104    | Ham License Required | Additional amateur radio           |

## Coverage Area

**Primary**: Charlotte, Mecklenburg County\
**Extended**: Surrounding counties in greater Charlotte metro area

## Key Services

### Emergency Services

- **Charlotte Fire Department (CFD)** - Dispatch and tactical channels
- **MEDIC** - Emergency medical services
- **Charlotte-Mecklenburg Police (CMPD)** - Law enforcement
- **Mecklenburg County Sheriff (MCSO)** - County law enforcement
- **CATS** - Charlotte Area Transit System

### Amateur Radio

- **W4BFB** - Multiple repeaters (Charlotte area)
- **W4SCC** - SCARC (South Charlotte Amateur Radio Club)
- **W4QMQ** - Queens City Amateur Radio Club
- **N4VU** - UNC Charlotte repeater

### Interoperability

- **TACALL** (151.145) - Tactical calling frequency
- **VTAC/UTAC** - Tactical coordination channels
- **8-Call/8-Tac** - Regional interoperability
- **Regional/Mutual Aid** - Multi-agency coordination

### Aviation

- **Charlotte Douglas International Airport** - Complete aviation frequencies
- **Tower, Ground, Approach, ATIS** - Air traffic control
- **Emergency** (121.5) - Aviation emergency frequency

## Programming

See **[Programming Guide](../docs/radio-configs/baofeng-uv5r/programming.md)**
for step-by-step CHIRP instructions.

## Detailed Information

For technical specifications and additional details, see
**[SkySignals Documentation](../docs/)**.

---

⚠️ **Listen Only** - Emergency service frequencies are for monitoring only. See
**[Legal, Licensing, and Regulatory Information](../../../../../../docs/legal/index.md)**
for complete terms.
