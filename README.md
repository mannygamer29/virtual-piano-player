# Virtual Piano Stepper Pro

A high performance assistant for virtual pianos. This tool allows you to play complex musical sheets with precision using either manual stepping or a fully customizable autoplay engine.

# Features

- **Dual Modes:** Switch between manual "Performance Mode" and "Autoplay Mode."
- **Autoplay Engine:** Adjustable BPM (Tempo) with a 5-second countdown to allow window switching.
- **Visual Feedback:** - Scrolling note display with active note highlighting.
  - Visual Metronome (flashing cyan dot).
  - Real-time Progress Bar with percentage tracking.
- **Custom Keybinds:** Set your own Start, Pause, and Stop keys for the engine.
- **Master Toggle:** Enable or disable the engine globally to type normally in chats.

## Important: Antivirus & Administrator Rights

Because this program uses Global Keyboard Hooks to detect and send keypresses while you are in a different window (like a web browser or game), it is often flagged by Antivirus software (e.g., SentinelOne, Windows Defender) as a "False Positive."

1. **Run as Administrator:** The program **MUST** be run as an Administrator to send keystrokes to other applications.
2. **Exclusions:** If your antivirus removes the file, you may need to add the folder to your antivirus "Exclusions" or "Whitelist."

## Installation & Usage

### For Users (Fastest)
1. Go to the [Releases](https://github.com/mannygamer29/virtual-piano-player/releases/tag/Release) page.
2. Download the `VirtualPianoStepper.zip` file.
3. Extract the folder to your Desktop.
4. Right-click `main.exe` and select **Run as Administrator**.

### For Developers (Source Code)
If you want to run the script directly:
1. Ensure you have [Python 3.x](https://www.python.org/) installed.
2. Install the required library:
   ```bash
   pip install keyboard
