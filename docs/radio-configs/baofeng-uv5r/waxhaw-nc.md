# Waxhaw, NC Configuration

Complete Baofeng UV-5R configuration for Waxhaw, North Carolina and surrounding
Union County area.

## Files

- [config.csv](https://github.com/wrightbradley/skysignals/blob/main/radios/baofeng/uv-5r/regions/us/southeast/waxhaw-nc/latest/config.csv)
  — CHIRP-compatible channel list
- [metadata.json](https://github.com/wrightbradley/skysignals/blob/main/radios/baofeng/uv-5r/regions/us/southeast/waxhaw-nc/latest/metadata.json)
  — Configuration metadata

## Channel Overview

| Range   | Service Type            | Channels | License              |
| ------- | ----------------------- | -------- | -------------------- |
| 1-9     | Amateur Radio Repeaters | 9        | Ham License Required |
| 20-23   | Amateur Radio Simplex   | 4        | Ham License Required |
| 30-52   | Emergency Services      | 23       | Listen Only          |
| 53-57   | Aviation                | 5        | Listen Only          |
| 58-68   | Interoperability        | 11       | Listen Only          |
| 70-73   | Weather Services        | 4        | Listen Only (Skip)   |
| 80-82   | Public Service          | 3        | Listen Only          |
| 90-91   | Personal Radio          | 2        | FRS/GMRS             |
| 100-106 | Legacy Amateur          | 7        | Ham License Required |

---

<!-- dprint-ignore-start -->
!!! warning
    Most frequencies are for monitoring only. Transmitting on these channels without proper authorization is illegal and subject to significant penalties. Amateur radio channels require a valid FCC license to transmit.
<!-- dprint-ignore-end -->

## Key Services

### Emergency Services

- Union County Fire, EMS, and Sheriff communications (listen-only, duplex off
  for safety)

### Weather Services

NOAA Weather Radio frequencies for the Charlotte/Waxhaw area:

- **162.400 MHz** – Primary weather frequency
- **162.475 MHz** – Secondary weather frequency
- **162.425 MHz** – Backup weather frequency
- **162.550 MHz** – Regional weather frequency

### Amateur Radio

Ham repeaters covering the Union County area:

- 2-meter band repeaters for local coverage
- 70cm band repeaters for wide-area coverage
- Emergency backup frequencies
- Simplex frequencies for local coordination

## Coverage Area

**Primary**: Waxhaw, Monroe, Indian Trail

**Extended**: Marvin, Wesley Chapel, Mineral Springs

## Download

Configuration files are located in the `Waxhaw-NC/` directory of the repository:

```bash
radios/baofeng/uv-5r/regions/us/southeast/waxhaw-nc/latest/
├── config.csv      # CHIRP-compatible CSV file
└── metadata.json   # Configuration metadata
```

## Safety Notices

<!-- dprint-ignore-start -->
!!! warning
    All public safety and commercial channels use `duplex = off` for safety. Transmitting on these frequencies without proper authorization is illegal.
<!-- dprint-ignore-end -->

<!-- dprint-ignore-start -->
!!! info
    Amateur radio channels (1-9, 20-23, 100-106) require a valid FCC Amateur Radio License to transmit. Listening is permitted for all.
<!-- dprint-ignore-end -->
