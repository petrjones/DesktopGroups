# PJSoft Desktop Groups

Launch your everyday set of applications with one click and restore the saved positions of their windows.

Desktop Groups is a free Windows utility for anyone who regularly opens the same applications and arranges their windows across one or more monitors. You can keep applications, documents, PDF manuals, shortcuts, and web links together in named, color-coded panels on the Windows desktop.

[Český popis](#pjsoft-skupiny-na-ploše)

## Download

[Download the latest release](https://github.com/petrjones/DesktopGroups/releases/latest)

On the release page, expand **Assets** and download the `PJSoft-Desktop-Groups-Setup-1.6.0.exe` installer. You can use it for a new installation or to update an existing one. An update carries over your saved groups, settings, and window layouts.

## What's new in 1.6.0

This release improves window layout restoration and desktop panel stability compared with version 1.5.1.

- **Physical monitor recognition.** Where a monitor can be identified, Desktop Groups remembers which physical display a window belongs on. If Windows renumbers that display or you rearrange your monitors in Display settings, the app uses the monitor’s current position to restore the window.
- **Clearer display labels.** The layout dialog shows the current Windows display number, the monitor’s position, and its model when available.
- **Temporary monitor replacement.** If a saved monitor is missing or cannot be identified reliably, you can choose a temporary replacement or cancel the restore. The saved assignment is available when the original monitor returns.
- **More reliable window placement.** After moving a window, Desktop Groups checks its position and maximized state. It can retry if the application changes its own position during startup.
- **Stable desktop panel sizes.** Desktop Groups restores the saved dimensions if Windows unexpectedly resizes a panel. The minimum height adapts to the rows of tiles to reduce unnecessary scrollbars.
- **Updated offline help.** The guide explains monitor recognition and layout restoration in English, Czech, Spanish, and German.

When you first restore a layout saved with version 1.5.1 or earlier, confirm the monitor assignments if prompted. You can also arrange the windows where you want them and save the layout again.

## Main features

- Create named, color-coded desktop groups and launch a whole group with one click.
- Save and restore window positions, sizes, monitor assignments, and maximized states. Layout operations respect the active Windows virtual desktop.
- Keep separate layouts for different monitor counts. Desktop Groups selects a matching layout automatically and can offer the closest saved variant.
- Resize group panels by dragging their edges. Tiles reflow to fit the available width, and the group name and controls stay visible while the content scrolls.
- Reorder tiles in **Edit** mode to set the order used by **Launch all**. Temporarily hide groups from the desktop whenever you need more space.
- Set how each item starts. Launch it immediately, apply a delay, wait for its window to appear, or wait for the previous application’s window before launching. A configurable timeout lets the sequence continue if a window cannot be found.
- Keep manuals and reference files in a group and optionally exclude them from **Launch all** so they can be opened individually.
- Use **Close all** to ask recognized group windows to close. Applications can still prompt you to save your work.
- Open **Diagnostics** from an item’s settings to see its process name and path, window title and class, monitor, and whether the match is unambiguous.
- Export, import, or restore the configuration from the **Data** menu. Automatic backups help recover previous settings.
- Open the offline guide with **F1** or **?**. The interface and guide are available in English, Czech, Spanish, and German.
- Use **About** to check for a stable GitHub release manually or enable an automatic check at most once every 24 hours. You choose when to download and run the installer.

## Quick start

1. Install Desktop Groups and click **+ Group** to create a group.
2. Enable **Edit** mode and add the applications, documents, shortcuts, or web links you need.
3. Drag tiles into the desired launch order. Use the gear button on a tile to configure how that item starts.
4. Open the applications and arrange their windows across your monitors.
5. Click **Save window layout**, select the windows that belong to the group, and confirm.
6. Next time, click **Launch all** to open the applications and restore their saved layout.

## Requirements and installation

- Windows 10 or Windows 11, 64-bit.
- The installer runs with standard user permissions.
- Desktop Groups works independently of Microsoft PowerToys.

To show groups automatically after signing in to Windows, select the corresponding option in the installer.

## License and support

Desktop Groups is freeware. All features are available free of charge, without advertisements or bundled offers. If the app saves you time, you can make a voluntary contribution through its support window. Contributions help cover the time and costs of development, testing, and maintenance.

**Publisher** · PJSoft

---

# PJSoft Skupiny na ploše

Spusť svou obvyklou sadu aplikací jedním kliknutím a obnov uložené rozmístění jejich oken.

Skupiny na ploše jsou bezplatná aplikace pro Windows určená lidem, kteří pravidelně otevírají stejné programy a rozmísťují jejich okna na jednom či více monitorech. Aplikace, dokumenty, příručky ve formátu PDF, zástupce i webové odkazy můžeš mít pohromadě v pojmenovaných a barevně odlišených panelech na ploše Windows.

## Stažení

[Stáhnout nejnovější vydání](https://github.com/petrjones/DesktopGroups/releases/latest)

Na stránce vydání rozbal část **Assets** a stáhni instalátor `PJSoft-Desktop-Groups-Setup-1.6.0.exe`. Slouží k nové instalaci i k aktualizaci stávající. Při aktualizaci převezme uložené skupiny, nastavení a rozložení oken.

## Co je nového ve verzi 1.6.0

Oproti verzi 1.5.1 se zlepšilo obnovení rozložení oken a stabilita rozměrů panelů na ploše.

- **Rozpoznávání fyzických monitorů.** Pokud lze monitor rozpoznat, aplikace si zapamatuje, na kterou fyzickou obrazovku okno patří. Když Windows monitor přečísluje nebo změníš uspořádání obrazovek, program při obnově použije jeho aktuální polohu.
- **Přehlednější označení obrazovek.** Dialog rozložení ukazuje aktuální číslo obrazovky podle Windows, polohu monitoru a název modelu, pokud je dostupný.
- **Dočasná náhrada monitoru.** Pokud uložený monitor chybí nebo ho nelze spolehlivě rozpoznat, můžeš vybrat dočasnou náhradu nebo obnovu zrušit. Po opětovném připojení je k dispozici původní přiřazení.
- **Spolehlivější rozmístění oken.** Program po přesunu zkontroluje polohu okna i stav maximalizace. Pokud si aplikace při startu změní polohu, může přesun zopakovat.
- **Stabilní velikost panelů skupin.** Pokud Windows samovolně změní velikost panelu, program obnoví uložené rozměry. Minimální výška se přizpůsobuje řádkům dlaždic, aby se zbytečně neobjevovaly posuvníky.
- **Aktualizovaná nápověda bez internetu.** Rozpoznávání monitorů a obnovu rozložení popisuje v češtině, angličtině, španělštině a němčině.

Při prvním obnovení rozložení uloženého ve verzi 1.5.1 nebo starší potvrď přiřazení monitorů, pokud se program zeptá. Okna můžeš také rozmístit podle potřeby a rozložení znovu uložit.

## Hlavní funkce

- Vytvářej pojmenované a barevně odlišené skupiny na ploše a spouštěj celé pracovní sady jedním kliknutím.
- Ukládej a obnovuj polohu, velikost, přiřazení k monitoru a stav maximalizace oken. Práce s rozložením respektuje aktivní virtuální plochu Windows.
- Ukládej samostatná rozložení pro různé počty monitorů. Program automaticky vybere odpovídající variantu a podle potřeby nabídne nejbližší uložené rozložení.
- Upravuj šířku i výšku panelů tažením za okraj. Dlaždice se přeskupí podle dostupné šířky a název skupiny i tlačítka zůstávají při posouvání obsahu viditelné.
- Přetahuj dlaždice v režimu **Upravit** a nastav jejich pořadí pro **Spustit vše**. Skupiny můžeš také dočasně skrýt z plochy.
- Nastav způsob spuštění každé položky. Aplikaci můžeš spustit okamžitě nebo po prodlevě, počkat na její okno po spuštění nebo se spuštěním vyčkat na okno předchozí aplikace. Po vypršení nastavitelného časového limitu může spouštění pokračovat.
- Měj ve skupině i příručky a pomocné dokumenty. Podle potřeby je vynech ze **Spustit vše** a otevírej je samostatně.
- Použij **Zavřít vše** k vyžádání zavření rozpoznaných oken skupiny. Jednotlivé aplikace mohou zobrazit výzvu k uložení práce.
- V nastavení položky otevři **Diagnostiku** a zkontroluj název a cestu procesu, titulek a třídu okna, monitor a jednoznačnost rozpoznání.
- V nabídce **Data** můžeš konfiguraci exportovat, importovat nebo obnovit. Automatické zálohy pomáhají vrátit se k předchozímu nastavení.
- Otevři nápovědu klávesou **F1** nebo tlačítkem **?** i bez internetu. Rozhraní i nápověda jsou dostupné v češtině, angličtině, španělštině a němčině.
- V okně **O aplikaci** můžeš ručně ověřit dostupnost nového stabilního vydání na GitHubu nebo zapnout automatickou kontrolu nejvýše jednou za 24 hodin. Kdy instalátor stáhneš a spustíš, určuješ sám.

## Rychlý začátek

1. Nainstaluj Skupiny na ploše a kliknutím na **+ Skupina** vytvoř skupinu.
2. Zapni režim **Upravit** a přidej potřebné aplikace, dokumenty, zástupce nebo webové odkazy.
3. Přetáhni dlaždice do požadovaného pořadí. Tlačítkem s ozubeným kolem na dlaždici nastavíš způsob spuštění konkrétní položky.
4. Otevři aplikace a rozmísti jejich okna na monitorech.
5. Klikni na **Uložit rozložení oken**, vyber okna patřící do skupiny a potvrď.
6. Příště klikni na **Spustit vše**. Program otevře aplikace a obnoví uložené rozložení jejich oken.

## Požadavky a instalace

- Windows 10 nebo Windows 11, 64bitový systém.
- Instalátor funguje s běžným uživatelským oprávněním.
- Skupiny na ploše fungují samostatně, bez Microsoft PowerToys.

Pokud chceš skupiny zobrazovat automaticky po přihlášení do Windows, vyber odpovídající možnost v instalátoru.

## Licence a podpora vývoje

Skupiny na ploše jsou zdarma. Všechny funkce jsou dostupné bezplatně, bez reklam a přibalených nabídek. Pokud ti aplikace šetří čas, můžeš její další vývoj podpořit dobrovolným příspěvkem prostřednictvím okna podpory v aplikaci. Příspěvky pomáhají pokrýt čas i náklady spojené s vývojem, testováním a údržbou.

**Vydavatel** · PJSoft
