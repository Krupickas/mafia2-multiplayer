# Mafia II: Definitive Edition – Multiplayer (pro přátele)

Neoficiální multiplayerový mod pro **Mafia II: Definitive Edition (Steam)**. Hraje se jen s přáteli ze Steamu, přes Steam síť (bez otevírání portů).

## Jak začít

1. Stáhni **M2MP-Launcher.exe** z [posledního vydání](https://github.com/Krupickas/mafia2-multiplayer/releases/latest).
2. Spusť ho (musí běžet Steam). Launcher sám najde Mafii II.
3. Klikni **Nainstalovat / aktualizovat** a pak **Spustit Mafii II s modem**.
4. Ve hře klikni v hlavním menu na **Multiplayer**. Po načtení města se objeví panel:
   - **Založit hru** – hostuješ a přátelé tě uvidí v seznamu,
   - **Hry přátel → Připojit** – připojíš se ke kamarádovi.
5. **Launcher nech otevřený po celou dobu hraní** – přes něj jde spojení přes Steam. Ve Steamu se ti ukáže, že hraješ „Spacewar“, to je v pořádku.

Panel ve hře otevřeš/zavřeš klávesou **F10**. Mod odinstaluješ v launcheru tlačítkem **Odinstalovat** (vrátí původní soubory hry).

## Co mod mění

Do složky hry `pc` přidá ScriptHook (`dxgi.dll`), `plugins\Mafia2DEMP.dll`, skripty `scripts\*.lua`, přidá tlačítko Multiplayer do hlavního menu a 32 slotů pro NPC v `sdsconfig.bin`. Všechny původní soubory se předtím zálohují do `%LOCALAPPDATA%\M2MP\backup`.

Je to rozpracovaný prototyp – může padat a ne všechno je synchronizované. Hra musí být aktuální Steam verze.

## Licence třetích stran

- ScriptHook: [MartinJK/Mafia2-Definitive-Edition-ScriptHook](https://github.com/MartinJK/Mafia2-Definitive-Edition-ScriptHook) (GPLv2, zdrojový kód na odkazu)
- Dear ImGui, MinHook (MIT/BSD), Steamworks API (Valve)
