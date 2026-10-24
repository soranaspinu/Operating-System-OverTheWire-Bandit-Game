# Operating-System-OverTheWire-Bandit-Game
This repository contains walkthroughs, commands used, and concepts learned while solving the initial levels (0 to 11) of the **OverTheWire: Bandit** wargame. The focus is on practical Linux command-line operations, basic security concepts, file searching, filtering, and data decoding.

## Concepts & Tools Used
* **Remote Connections:** SSH (`ssh`)
* **File Operations & Navigation:** `ls`, `cd`, `cat`, handling filenames with spaces or leading dashes (`./-`, quotes)
* **File Searching & Inspection:** `find` (by size, user, permissions), `file`, hidden files (`ls -a`)
* **Text Processing & Data Filtering:** `grep`, `sort`, `uniq`, `strings`
* **Encoding/Decoding:** Base64 decoding (`base64 -d`)

## Levels Covered
- **Level 0 → 1:** SSH access & reading basic files.
- **Level 1 → 3:** Advanced file handling (special characters, spaces, leading dashes).
- **Level 3 → 6:** Finding hidden, nested, and specific attribute files (`find`, `file`).
- **Level 6 → 10:** Extracting data with `grep`, `sort`, `uniq`, and `strings`.
- **Level 10 → 11:** Base64 data decoding.
