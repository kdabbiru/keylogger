# Keylogger Using `pynput`

## Project Overview
This Python script logs keyboard inputs using the `pynput` library. It captures keypresses, including special keys, and records them into a file (`log.txt`). The script supports key recognition for regular characters, special keys, and key combinations like `Ctrl + A`.

---

## Features
- **Logs All Keypresses**: Tracks standard keys, function keys, special keys, and key combinations.
- **Key Mappings**: Provides clear, human-readable labels for special keys and combinations.
- **Customizable Output**: Writes logged keystrokes to a file (`log.txt`), preserving formatting for spaces, newlines, and special key labels.
- **Real-Time Logging**: Captures and writes keys as they are pressed.

---

## File Structure
```plaintext
├── keylogger.py   # The main script containing the keylogging logic.
├── log.txt        # File where key logs are stored.
```

---

## Prerequisites
1. **Python 3.x**: Ensure Python is installed.
2. **pynput Library**: Install the library by running:
   ```bash
   pip install pynput
   ```

---

## How to Use
1. Clone the repository or copy the script into a Python file (e.g., `keylogger.py`).
2. Run the script:
   ```bash
   python keylogger.py
   ```
3. To stop the logger:
   - Use `Page Down` key (as implemented in the script) or terminate the script manually.

---

## Key Mappings
### Recognized Special Keys
- **Modifier Keys**: `Ctrl`, `Shift`, `Alt`, `Cmd`, `Caps Lock`
- **Navigation Keys**: `Arrow Keys`, `Page Up`, `Page Down`, `Home`, `End`
- **Function Keys**: `F1` to `F24`
- **Media Keys**: `Volume Up`, `Volume Down`, `Mute`, `Pause`
- **Editing Keys**: `Backspace`, `Delete`
- **Others**: `Space`, `Enter`, `Tab`, `Esc`, `Print Screen`

### Example Mappings
- `Key.space` → ` ` (Space)
- `Key.enter` → `\n` (Newline)
- `Key.ctrl_l` → `(Left Ctrl)`
- `Key.f1` → `(F1)`
- `Ctrl + C` → `(Ctrl + C)`

---

## Security & Ethical Use
**Disclaimer**: This script is for educational purposes only. Unauthorized keylogging is illegal and unethical. Use this project responsibly and only on systems you own or have explicit permission to monitor.

---

## Contribution
Contributions to enhance functionality or add features are welcome. Please fork the repository and submit a pull request.

---
