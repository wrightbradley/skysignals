# Programming Guide

Step-by-step instructions for programming your Baofeng UV-5R using CHIRP
software.

## ⚠️ Safety Warning

**CRITICAL:** All SkySignals configurations include built-in transmission
protection, but **always exercise extreme caution** before pressing PTT:

- **🔒 Listen-only channels** use duplex `off` to prevent transmission
- **📖 Read channel comments** carefully—most are **[LISTEN ONLY]**
- **🔍 Verify your license** covers the frequency before transmitting
- **⚖️ Illegal transmission** can result in severe penalties

## Requirements

- **CHIRP Software** — [Download here](https://chirp.danplanet.com)
- **Programming Cable** — Baofeng USB cable (2-pin Kenwood-style)
- **Driver** — Prolific PL2303 or CH340 USB driver

## Installation

### 1. Install CHIRP

=== "Windows" 1. Download CHIRP installer for Windows 2. Run installer as
Administrator 3. Follow installation prompts

=== "macOS" 1. Download CHIRP disk image (.dmg) 2. Open and drag to Applications
folder 3. Allow in Security & Privacy if prompted

=== "Linux"

```bash
# Ubuntu/Debian
sudo apt install chirp
# Or download from website`
```

### 2. Install Cable Driver

Most cables require the Prolific PL2303 driver:

=== "Windows" 1. Download from
[Prolific website](http://www.prolific.com.tw/US/ShowProduct.aspx?p_id=225&pcid=41)
2. Install driver before connecting cable 3. Restart computer

=== "macOS" 1. Download macOS driver from Prolific 2. Install and restart 3.
Check System Preferences > Security

=== "Linux" Driver usually included in kernel—no action needed.

## Programming Steps

### 1. Backup Your Radio

<!-- dprint-ignore-start -->
!!! warning
    Always backup your radio before programming!
<!-- dprint-ignore-end -->

1. **Connect Cable**
   - Radio must be **OFF** when connecting
   - Connect USB to computer
   - Connect 2-pin connector to radio
2. **Open CHIRP**
   - Launch CHIRP application
   - Go to **Radio > Download From Radio**
3. **Select Settings**
   - **Port**: Select your cable's COM port
   - **Vendor**: Baofeng
   - **Model**: UV-5R
   - **Click OK**
4. **Download**
   - Wait for download to complete
   - **File > Save As** to backup your radio

### 2. Import Configuration

1. **Open Backup File**
   - **File > Open** your backup file
2. **Import Channels**
   - **File > Import**
   - Select `.csv` configuration file
   - Choose import format: "CSV"
3. **Review Channels**
   - Verify channels imported correctly
   - Check frequencies and tones
   - Modify if needed

### 3. Upload to Radio

1. **Connect Radio**
   - Ensure radio is OFF
   - Connect programming cable
2. **Upload**
   - **Radio > Upload To Radio**
   - Select same port and model
   - **Click OK**
3. **Wait for Completion**
   - Do not disconnect during upload
   - Radio will beep when complete

### 4. Test Channels

1. **Turn Radio On**
   - Press **MR** to enter memory mode
   - Use channel knob to scroll through
2. **Test Reception**
   - Listen to several channels
   - Verify proper operation
   - Check tones are working

## Troubleshooting

### Connection Issues

| Problem              | Solution                                       |
| -------------------- | ---------------------------------------------- |
| Port not found       | Install correct driver, try different USB port |
| Radio not responding | Ensure radio is OFF, check cable connection    |
| Upload fails         | Try again, check cable, restart CHIRP          |

### Import Errors

| Error                 | Solution                              |
| --------------------- | ------------------------------------- |
| Format not recognized | Use exact CSV file provided           |
| Invalid frequency     | Check frequency is within radio range |
| Missing columns       | Download fresh configuration file     |

### Driver Problems

=== "Windows" - Use Device Manager to check driver status - Try different USB
port - Download latest driver from manufacturer

=== "macOS" - Check System Information > USB - Verify driver is properly signed

- May need to disable SIP temporarily

=== "Linux" - Check `dmesg` for USB errors - Verify user permissions for serial
ports - Add user to `dialout` group if needed

## Tips

- **Always backup** before making changes
- **Radio OFF** when connecting cable
- **USB 2.0 ports** work better than USB 3.0
- **Close other programs** that might use serial ports
- **Try different cables** if persistent issues
