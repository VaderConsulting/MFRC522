# MFRC522

Arduino RFID Library for MFRC522 (SPI). Read/Write a RFID Card or Tag using the ISO/IEC 14443A/MIFARE interface. Original author: GithubCommunity. This is Dave Robinson's working copy from the Arduino `libraries` tree. Version recorded in `library.properties`: 1.4.10. Upstream: <https://github.com/miguelbalboa/rfid>.

**Language:** C++ / Arduino  
**Target:** Arduino (avr,megaavr,STM32F1,teensy,esp8266,esp32,samd,atmelsam)  
**Output:** Arduino library

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `MFRC522` | C++ / Arduino | library | Arduino RFID Library for MFRC522 (SPI) |
| `ChangeUID` | C++ / Arduino | example sketch | `examples/ChangeUID/ChangeUID.ino` |
| `DumpInfo` | C++ / Arduino | example sketch | `examples/DumpInfo/DumpInfo.ino` |
| `FixBrickedUID` | C++ / Arduino | example sketch | `examples/FixBrickedUID/FixBrickedUID.ino` |
| `MifareClassicValueBlock` | C++ / Arduino | example sketch | `examples/MifareClassicValueBlock/MifareClassicValueBlock.ino` |
| `MinimalInterrupt` | C++ / Arduino | example sketch | `examples/MinimalInterrupt/MinimalInterrupt.ino` |
| `Ntag216_AUTH` | C++ / Arduino | example sketch | `examples/Ntag216_AUTH/Ntag216_AUTH.ino` |
| `RFID-Cloner` | C++ / Arduino | example sketch | `examples/RFID-Cloner/RFID-Cloner.ino` |
| `ReadAndWrite` | C++ / Arduino | example sketch | `examples/ReadAndWrite/ReadAndWrite.ino` |

## How to open

Install this folder as an Arduino library (Sketch → Include Library → Add .ZIP Library, or copy into `libraries/MFRC522`). Open any `examples/*.ino` from the Arduino IDE.

## Attribution and provenance

- **Original author / maintainer:** GithubCommunity
- **library.properties name:** MFRC522
- **Version:** 1.4.10
- **Upstream URL:** <https://github.com/miguelbalboa/rfid>
- **Category:** Communication
- This repository is Dave Robinson's working copy for catalogue/reference; authorship stays with the original authors.

## License

Original upstream license terms in this tree (where recorded). This repository does not claim authorship of the upstream library. See `THIRD_PARTY_NOTICES.md`. The `LICENSE` file added at import is a VaderConsulting MIT wrapper and does not replace upstream terms.
