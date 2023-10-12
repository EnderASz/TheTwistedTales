---
title: Timeline
---
W tym miejscu przedstawiony jest timeline, z perspektywy każdego z bohaterów.
Całość wydarzeń dzieje się w jednej tej samej rzeczywistości, natomiast każdy z bohaterów uczestniczy w innych wydarzeniach nie raz dziejących się równolegle do innych.

Powoduje to, problem w prostym przedstawieniu chronologii wydarzeń na pojedynczej osi czasu czy diagramie przy wykorzystaniu obecnie dostępnych narzędzi.
## Legenda diagramów

- **Wydarzenia następujące bezpośrednio po sobie**
```mermaid
flowchart TB
	A --> B
```
- **Wydarzenia z bliżej nieokreślonym dystansem czasowym**
```mermaid
flowchart TB
	A -.-> B
```

## Timeline'y
### [[Aldakor Esku]]
```mermaid
flowchart TB
	Kostur(Kradzież Kosturu Redcliffa)
	Jaja(Zaginięcie egzotycznych jaj)
	Joe(Zabójstwo Krwawego Joe)
	Fantastyczny(Podróż do fantastycznego świata)
	Mapa(Czarna mapa - Baronat Rubbitonów)
	Vaskala(Podróż do Vaskalii)
	Fałszywy(Fałszywy Bóg)
	Spotkanie(Ponowne spotkanie)

	Kostur-.->Jaja
	Jaja-->Joe
	Joe-->Fantastyczny
	Fantastyczny-.->Mapa
	Mapa-->Vaskala
	Vaskala-->Fałszywy
	Fałszywy --> Spotkanie

class Kostur internal-link;
class Jaja internal-link; 
class Joe internal-link;
class Fantastyczny internal-link;
class Mapa internal-link;
class Vaskala internal-link;
class Fałszywy internal-link;
class Spotkanie internal-link;
```
### [[Alvira z Wieczornych Gwiazd]]
```mermaid
flowchart TB
	Vaskala(Podróż do Vaskalii)
	Trio(Królik, Wilk i Debil)
	Fałszywy(Fałszywy Bóg)
	Spotkanie(Ponowne spotkanie)

	Vaskala --> Trio
	Trio --> Fałszywy
	Fałszywy --> Spotkanie

class Vaskala internal-link;
class Trio internal-link;
class Fałszywy internal-link;
class Spotkanie internal-link;
```
### [[Ichada]]
```mermaid
flowchart TB
	Jaja(Zaginięcie egzotycznych jaj)
	Joe(Zabójstwo Krwawego Joe)
	Fantastyczny(Podróż do fantastycznego świata)
	Duo(Królik i Debil)
	Trio(Królik, Wilk i Debil)
	Fałszywy(Fałszywy Bóg)

	Jaja-->Joe
	Joe-->Fantastyczny
	Fantastyczny-.->Duo
	Duo-->Trio
	Trio-->Fałszywy


class Jaja internal-link; 
class Joe internal-link;
class Fantastyczny internal-link;
class Duo internal-link;
class Trio internal-link;
class Fałszywy internal-link;
```
### [[Myhones Ray Aktonn]]
```mermaid
flowchart TB
	Mapa(Czarna mapa - Baronat Rubbitonów)
	Duo(Królik i Debil)
	Trio(Królik, Wilk i Debil)
	Fałszywy(Fałszywy Bóg)
	
	Mapa-.->Duo
	Duo-->Trio
	Trio-->Fałszywy

class Mapa internal-link;
class Duo internal-link;
class Trio internal-link;
class Fałszywy internal-link;
```
### [[Kian'Verion]]
```mermaid
flowchart TB
	Kostur(Kradzież Kosturu Redcliffa)
	Fałszywy(Fałszywy Bóg)

	Kostur -.-> Fałszywy

class Kostur internal-link;
class Fałszywy internal-link;
```