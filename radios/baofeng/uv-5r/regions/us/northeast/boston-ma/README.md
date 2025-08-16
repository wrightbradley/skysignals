# Boston, MA - Baofeng UV-5R Configuration

Complete 50-channel configuration for Boston, Massachusetts and the Metro Boston
Homeland Security Region (MBHSR).

## 🔒 Built-in Safety Features

This configuration includes **automatic transmission prevention** on all
restricted frequencies:

- **✅ All listen-only channels** use duplex setting `off` to prevent accidental
  transmission
- **✅ Licensed channels** maintain proper duplex settings for authorized users
- **⚠️ Always verify** your authorization before transmitting on any channel

## Files

- **`Baofeng_UV-5R_BostonMA_Channels.csv`** - CHIRP-compatible channel list
- **`Baofeng_UV-5R_BostonMA.img`** - Complete radio memory image

## Quick Reference

| Service            | Channels | License              | Notes                              |
| ------------------ | -------- | -------------------- | ---------------------------------- |
| Amateur Radio      | 1-9      | Ham License Required | VHF/UHF repeaters, simplex         |
| Fire Services      | 11-17    | Listen Only          | BFD dispatch, tactical, mutual aid |
| EMS Services       | 21-24    | Listen Only          | Boston EMS dispatch and tactical   |
| Police & Emergency | 31-47    | Listen Only          | BAPERN, MBTA, federal agencies     |
| Weather Services   | 51-54    | Listen Only (Skip)   | NOAA weather radio                 |
| MBHSR Interop      | 61-73    | Listen Only          | Regional coordination channels     |
| Additional MBHSR   | 81-83    | Listen Only          | Extended regional channels         |
| Personal Radio     | 91-92    | FRS/GMRS             | Family/personal communications     |

## Coverage Area

**Primary**: Boston, Cambridge, Somerville, Brookline\
**Extended**: Chelsea, Everett, Quincy, Revere, Winthrop

## Key Interoperability Channels

- **UCALL** (453.2125) - MBHSR primary calling channel
- **UTAC 1-3** - Unified tactical channels
- **Metro Fire Coordination** - Regional fire mutual aid
- **BAPERN** - Boston Area Police Emergency Radio Network

## Programming

See **[Programming Guide](../docs/radio-configs/baofeng-uv5r/programming.md)**
for step-by-step CHIRP instructions.

## Detailed Information

For complete channel tables, frequencies, and technical details, see
**[Boston Configuration Documentation](../docs/radio-configs/baofeng-uv5r/boston-ma.md)**.

---

⚠️ **Listen Only** - Emergency service frequencies are for monitoring only. See
**[Legal, Licensing, and Regulatory Information](../../../../../../docs/legal/index.md)**
for complete terms.
