## 🐾 PetApp3‑Kuro Edition  
A lightweight, portable AI pet application featuring Kuro, a Netherland Dwarf rabbit.  
Supports English voice commands and face detection.

---

## 🎤 Voice Commands (English → State)

Kuro reacts to English voice commands through Whisper.  
Each command triggers one of the predefined states (n1–p12).

### Basic Commands

| Command | State | Description |
|--------|--------|-------------|
| **play** | p1 | playful reaction (smile) |
| **sit** | n2 | sitting |
| **sleep** | n3 | sleeping |
| **come here** | p1 | playful reaction / approach |
| **good boy / good girl** | p2 | joy (binky) |
| **I love you** | p12 | special affection |
| **fetch** | p8 | fetch behavior |
| **stand / stand up** | p10 | standing |
| **bath / groom / brush** | p11 | grooming |

### Other Commands

| Command | State |
|--------|--------|
| **meal / food / hungry / eat** | p5 |
| **water / drink / thirsty** | p6 |
| **toilet / bathroom / pee / poop** | p7 |
| **house / go home / your house** | p9 |

---

## 🐇 Name Call

Calling Kuro’s name triggers:

**p2 (joy / binky)**

---

## 😊 Face Detection

When your face appears on the camera,  
Kuro switches to:

**p1 (smile)**

※ This is **face detection**, not smile detection.

---

## 📦 Portable Edition

This edition includes:

- Whisper voice recognition  
- Face detection  
- Portable Python environment  
- No installation required  

