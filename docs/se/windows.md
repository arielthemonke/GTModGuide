# Windows

När du moddar Gorilla Tag på Windows så har du två huvud val att göra:

---

## Val 1: Monke Mod Manager (MMM)
### Svårighetsgrad: Jävligt enkelt

MMM är det simplaste sättet att installera mods.

#### Steg 1: Installera MMM
[Installera Monke Mod Manager](https://github.com/arielthemonke/MonkeModManager/releases/latest/download/MonkeModManager.exe)

#### Step 2: Starta MMM
Det borde se ut ungefär såhär:  
![Game path selection](../images/game-path-select.png)

- Tryck på **OK** och skriv in din **Gorilla Tag spelväg**.
- Vet du inte var din spelväg är? [Tryck här för en guide](game-path.md)

#### Step 3: Installera Mods
- Tryck på **Install** vid sidan om de moddsen du vill installera.
- MMM tar hand om resten — jävligt enkelt, som jag sade.

#### Steg 4: Installera mods som inte finns på MMM (Optional)
Mods som inte är inkluderade i MMM kan installeras manuellt:

1. Ta mod filen (`.dll`  )
2. Dra den till din `plugins` mapp vid: `(Din spelväg)\BepInEx\plugins`

---

## Val 2: Installera BepInEx manuellt
### Svårighetsgrad: Varför vill du göra detta

Gör inte detta, jag vet ej varför Ariel lär ut detta.

#### Steg 1: Installera BepInEx
Installera den senaste `BepInEx_win_x64_*.zip` filen från [BepInEx utgåvor](https://github.com/BepInEx/BepInEx/releases/latest)


#### Steg 2: Extrahera BepInEx
- Extrahera zip innehållet i din Gorilla Tag mapp.
- Din mapp ska nu innehålla bl.a följande filer: `BepInEx`, `doorstop_config.ini`, etc.

#### Steg 3: Konfigurera & Installera Mods
1. **Fixa Konfigurering**
- Installera [denna BepInEx konfigurerings filen](https://github.com/The-Graze/MonkeModInfo/blob/master/BepInEx.cfg)
- Flytta den till:
  ```
  (Din spelväg)\BepInEx\config
  ```
*Skapa 'config' mappen om den inte finns.*

2. **Installera Mods**
- Ta mod filen (`.dll`  )
- Dra den till din `plugins` mapp vid: `(Din spelväg)\BepInEx\plugins`

*Skapa 'plugins' mappen om den inte finns.*

---

[Nästa sida >](the-end.md)

###### Svensk översättning av HanSolo1000Falcon