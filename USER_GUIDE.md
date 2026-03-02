FAYG Recovery Engine — User Guide
⚠️ Important Safety Notice

FAYG Recovery Engine is designed for device diagnostics and recovery assistance.

Before using
Back up your data if possible
Use original USB cable
Ensure battery is above 40%
Use at your own risk
Do NOT use on devices managed by an organization without permission


🖥️ System Requirements

Windows 10 or newer
Python 3.9+ installed
USB debugging enabled on Android (if accessible)
ADB drivers installed


📦 What’s Included

The package contains:
engine.py — main recovery engine
adb_utils.py — ADB helper functions
gui.py — graphical interface
Required platform tools


🚀 Quick Start (Recommended)

Step 1 — Extract the ZIP
Right-click the downloaded ZIP
Click Extract All
Open the extracted folder


Step 2 — Connect your phone

Power on the phone
Connect via USB
If prompted, allow USB debugging


Step 3 — Launch the tool

Open terminal inside the folder and run:
<code>
python gui.py
If GUI fails:
<cose>
python engine.py


🔍 Basic Usage

Device Detection
Click Detect Device
Wait for status message
Confirm device appears


Dark Screen Recovery

Connect device
Click Screen Diagnostics
Follow on-screen instructions


ADB Diagnostics

Use when device is partially responsive.
Steps:

Enable USB debugging
Run diagnostics
Review results log


❗ Troubleshooting

Device not detected
Try different USB port
Install ADB drivers
Use original cable
Check USB debugging


ADB unauthorized

Reconnect phone
Accept RSA prompt on device
Restart ADB


Tool not opening

Make sure Python is installed:
python --version


🔐 Important Limitations

FAYG Recovery Engine cannot:

Bypass manufacturer security locks
Remove enterprise/MDM protections
Unlock bootloaders without authorization
Recover physically damaged hardware


🧑‍💻 Support

For updates and issues:

Check the GitHub repository
Submit an issue if problems occur

FAYG Recovery Engine — Safe. Smart. Diagnostic-first.