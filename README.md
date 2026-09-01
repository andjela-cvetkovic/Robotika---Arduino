# Pametna kanta – Arduino projekat

Projekat predstavlja pametnu kantu koja se automatski otvara kada detektuje objekat u svojoj blizini.

## Komponente
- Arduino Uno
- HC-SR04 ultrazvučni senzor
- Servo motor
- Jumper žice
- Baterija za napajanje

## Kako radi
Ultrazvučni senzor meri udaljenost objekta od kante. Kada se objekat približi na zadatu udaljenost, Arduino šalje signal servo motoru koji podiže poklopac kante. Nakon određenog vremena poklopac se automatski zatvara.

## Povezivanje
- TRIG → Arduino pin 7
- ECHO → Arduino pin 6
- Servo signal → Arduino pin 5
- VCC → 5V
- GND → GND

## Demonstracija
U repozitorijumu se nalazi video snimak koji prikazuje rad pametne kante.

Radile:
Anđela Cvetković
Danica Kovačević
