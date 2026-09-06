# BAI – BastiAI

**Homunculus AI configurator for Ragnarok Zero Global**

BAI (BastiAI) is a Windows application for creating and managing custom Homunculus AI configurations for **Ragnarok Zero Global**.

The goal of BAI is to provide an easy-to-use graphical interface for configuring Homunculus behavior without manually editing Lua files.

> **Beta / Pre-release**
>
> BAI is currently in active development.  
> Features, settings and AI behavior may change, and bugs are still possible.

---

## Languages

BAI currently supports:

- English
- Deutsch

On the first launch, BAI asks which language you want to use.

The language can be changed later in **Settings**.

Monster names, skill names and Ragnarok Online terminology use their common English names.

---

## Features

BAI currently includes configuration for:

- Multiple Homunculus profiles
- Aggressive and passive behavior
- Automatic combat
- Kill Steal prevention
- Owner protection
- Homunculus self-defense
- Combat distance and return behavior
- Automatic Homunculus skills
- Skill conditions and priorities
- Monster-specific rules
- Custom Monster IDs
- PvP behavior
- PvP class/job rules
- Movement and idle behavior
- Hidden debug tools
- Automatic AI installation into the Ragnarok `USER_AI` folder

BAI generates the configuration used by the included Homunculus AI.

---

## Monster Rules

Individual behavior can be configured for specific monsters.

The included monster database provides monster names and IDs for convenient selection.

Custom Monster IDs can also be entered manually if a monster is not included in the bundled catalog.

---

## Homunculus Skills

BAI supports the skills of:

- Lif
- Amistr
- Filir
- Vanilmirth

Multiple skill rules can be created and configured with conditions such as:

- Skill Level
- Minimum SP
- HP conditions
- Usage interval
- Combat distance

---

## Kill Steal Protection

BAI includes Kill Steal prevention logic.

A monster can still be considered a valid target when, for example:

- it attacks the owner,
- it attacks the Homunculus,
- the owner attacks it,
- or the Homunculus was manually ordered to attack it.

### Party limitation

Ragnarok's Homunculus AI interface does not provide reliable information about party membership.

Because of this, a monster being tanked by another party member may sometimes be treated as belonging to another player.

---

## Updates

BAI contains its own update system.

It can:

- Check GitHub for BAI versions
- Download updates
- Verify downloads using SHA-256
- Install updates
- Show release notes in the selected language
- Install an older supported version

The minimum supported version for downgrades is:

**v0.1.16**

Downgrading may cause settings or features introduced by newer versions to become unavailable.

Automatic update checks and update notifications can be configured in **Settings**.

---

## Installation

1. Download the latest BAI ZIP from the **Releases** section.
2. Extract the ZIP into a folder of your choice.
3. Start `BAI.exe`.
4. Select your language.
5. Open **Settings** and select your Ragnarok `USER_AI` folder.
6. Configure your Homunculus.
7. Click **Install**.

BAI profiles and application settings are stored separately from the application files.

---

## Windows / SmartScreen

BAI is currently distributed as an **unsigned beta application**.

Because the executable is not digitally signed, Microsoft Defender SmartScreen or other antivirus software may display a warning when BAI is downloaded or started for the first time.

BAI updates are downloaded from this GitHub repository and verified using a SHA-256 checksum before installation.

---

## Beta Notice

BAI is still under development.

Please keep in mind:

- Bugs may occur.
- AI behavior may still require adjustments.
- Settings can change between versions.
- Downgrading can make newer settings unavailable.

Bug reports and feedback are welcome.

---

## Disclaimer

BAI is an independent fan-made project.

It is not affiliated with, endorsed by, or associated with Gravity, Ragnarok Online, or the operators of Ragnarok Zero Global.

Ragnarok Online and related names and trademarks belong to their respective owners.

---

## Author

**Basti**

Contact: `dropdownsplash@web.de`

---

# Deutsch

**Homunculus-AI-Konfigurator für Ragnarok Zero Global**

BAI (BastiAI) ist eine Windows-Anwendung zum Erstellen und Verwalten eigener Homunculus-AI-Konfigurationen für **Ragnarok Zero Global**.

Das Ziel von BAI ist es, die Konfiguration der Homunculus-AI über eine übersichtliche grafische Oberfläche zu ermöglichen, ohne Lua-Dateien von Hand bearbeiten zu müssen.

> **Beta / Pre-release**
>
> BAI befindet sich derzeit in aktiver Entwicklung.  
> Funktionen, Einstellungen und das Verhalten der AI können sich noch ändern und Fehler sind möglich.

---

## Sprachen

BAI unterstützt derzeit:

- Deutsch
- English

Beim ersten Start fragt BAI nach der gewünschten Sprache.

Die Sprache kann später jederzeit unter **Einstellungen** geändert werden.

Monster-, Skill- und typische Ragnarok-Online-Bezeichnungen verwenden ihre gebräuchlichen englischen Namen.

---

## Funktionen

BAI bietet derzeit unter anderem:

- Mehrere Homunculus-Profile
- Aggressives und passives Verhalten
- Automatischen Kampf
- Kill-Steal-Schutz
- Schutz des Spielers
- Selbstverteidigung des Homunculus
- Kampfentfernung und Rückkehrverhalten
- Automatische Homunculus-Skills
- Bedingungen und Regeln für Skills
- Monsterspezifische Regeln
- Eigene Monster-IDs
- PvP-Verhalten
- PvP-Klassenregeln
- Bewegungs- und Idle-Verhalten
- Versteckte Debug-Funktionen
- Automatische Installation der AI in den Ragnarok-`USER_AI`-Ordner

BAI erzeugt daraus die Konfiguration für die mitgelieferte Homunculus-AI.

---

## Monster-Regeln

Für einzelne Monster können eigene Verhaltensregeln festgelegt werden.

Die mitgelieferte Monster-Datenbank enthält Namen und IDs zur einfachen Auswahl.

Zusätzlich können eigene Monster-IDs manuell eingetragen werden, falls ein Monster nicht im mitgelieferten Katalog vorhanden ist.

---

## Homunculus-Skills

BAI unterstützt die Skills von:

- Lif
- Amistr
- Filir
- Vanilmirth

Für Skills können mehrere Regeln mit unterschiedlichen Bedingungen erstellt werden, beispielsweise:

- Skill Level
- Mindest-SP
- HP-Bedingungen
- Nutzungsintervall
- Kampfentfernung

---

## Kill-Steal-Schutz

BAI enthält eine eigene Logik zur Vermeidung von Kill Steals.

Bestimmte Situationen erlauben trotzdem einen Angriff, beispielsweise wenn ein Monster den Spieler oder Homunculus angreift oder der Angriff manuell angeordnet wurde.

### Einschränkung bei Partys

Die Homunculus-AI von Ragnarok liefert keine zuverlässigen Informationen über die Partyzugehörigkeit anderer Spieler.

Ein Monster, das beispielsweise von einem Partymitglied getankt wird, kann deshalb unter Umständen als fremdes Monster behandelt werden.

---

## Updates

BAI besitzt ein integriertes Update-System.

BAI kann:

- Verfügbare BAI-Versionen auf GitHub suchen
- Updates herunterladen
- Downloads per SHA-256 überprüfen
- Updates installieren
- Patch Notes in der ausgewählten Sprache anzeigen
- Eine ältere unterstützte Version installieren

Die älteste unterstützte Version für ein Downgrade ist:

**v0.1.16**

Beim Downgrade können Funktionen oder Einstellungen neuerer Versionen nicht mehr verfügbar sein.

Automatische Updateprüfungen und Update-Benachrichtigungen können unter **Einstellungen** angepasst werden.

---

## Installation

1. Aktuelle BAI-ZIP unter **Releases** herunterladen.
2. ZIP in einen beliebigen Ordner entpacken.
3. `BAI.exe` starten.
4. Sprache auswählen.
5. Unter **Einstellungen** den Ragnarok-`USER_AI`-Ordner auswählen.
6. Homunculus konfigurieren.
7. **Installieren** auswählen.

Profile und Einstellungen von BAI werden getrennt von den eigentlichen Programmdateien gespeichert.

---

## Windows / SmartScreen

BAI wird derzeit als **nicht digital signierte Beta-Anwendung** veröffentlicht.

Windows Defender SmartScreen oder andere Sicherheitsprogramme können deshalb beim Download oder beim ersten Start eine Warnung anzeigen.

BAI-Updates werden von diesem GitHub-Repository heruntergeladen und vor der Installation mit einer SHA-256-Prüfsumme überprüft.

---

## Beta-Hinweis

BAI befindet sich weiterhin in Entwicklung.

Daher gilt:

- Fehler können auftreten.
- Das Verhalten der AI kann noch angepasst werden.
- Einstellungen können sich zwischen Versionen ändern.
- Bei einem Downgrade können neuere Einstellungen nicht mehr verfügbar sein.

Fehlerberichte und Feedback sind ausdrücklich willkommen.

---

## Haftung / Hinweis

BAI ist ein unabhängiges Fanprojekt.

BAI steht in keiner offiziellen Verbindung zu Gravity, Ragnarok Online oder den Betreibern von Ragnarok Zero Global und wird von diesen nicht unterstützt.

Ragnarok Online sowie zugehörige Namen und Marken gehören den jeweiligen Rechteinhabern.

---

## Entwickler

**Basti**

Kontakt: `dropdownsplash@web.de`
