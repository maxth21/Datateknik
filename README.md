Detta projekt är en implementation av det klassiska spelet **Snake** för PIC32-mikrokontroller. Spelet körs på en OLED-display och styrs via knappar.

## 🛠 Funktioner
- **Ormens rörelser**: Ormen kan röra sig i fyra riktningar (upp, ner, vänster, höger).
- **Ätbara äpplen**: När ormen äter ett äpple växer den och poängen ökar.
- **Kollisioner**: Spelet tar slut om ormen kolliderar med väggen eller sin egen kropp.
- **OLED-grafik**: Spelet använder en 128x32 OLED-display för att visa spelets status.

## 📁 Filstruktur
- `main.c` – Initierar spelet och hanterar systeminställningar.
- `Spel.c` – Huvudlogiken för spelet, inklusive ormens rörelse och kollisioner.
- `display.c` – Hanterar rendering av spelet på OLED-displayen.
- `Orm.h` – Deklarationer för spelrelaterade funktioner och variabler.
- `Makefile` – Kompileringsinstruktioner för projektet.

## 🔧 Kompilering och Körning
Använd `make` för att kompilera koden:
```sh
make
