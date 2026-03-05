# Vanguard

> Význam jména - *Předvoj* - strategický rámec pro dominanci v aréně.

## Odborný článek

Vanguard je komplexní metodika pro optimalizaci vašeho bojového stylu. Jejím účelem je systematický trénink mechanik, kategorizace taktik podle typu souboje (např. PotPvP, Nodebuff, Bedwars) a následná analytická zpětná vazba pro zlepšení vašich výsledků.

### Funkce

#### Tréninkový režim
Jednotlivé mechaniky jsou rozděleny podle klíčových dovedností:
* **Movement (Pohyb):** Ovládání *W-tap*, *S-tap* a *Strafe* pro udržení optimálního "combo" rytmu.
* **Aim & Click:** Trénink stability zaměřovače a konzistence CPS (Clicks Per Second) během pohybu.
* **Inventory Management:** Rychlost a přesnost práce s hotbarem (přepínání mezi mečem, prutem, lávou a gapplem).

#### Analytika
Každý uživatel je schopen nechat proběhnout analýzu svého výkonu. Ta prezentuje metriky, jako je efektivita hit-registrace, úspěšnost *rod-combos* a celková stabilita výkonu během vypjatých momentů.

#### Sdílení taktik
Uživatel může vygenerovat konfigurační profil, pomocí kterého může sdílet své nastavení (keybindy, sensitivity, crosshair design) se spoluhráči v klanu nebo trenérem.

### Role

#### Nováček (Novice)
Nováček nemá přístup k pokročilým analytickým grafům. Zaměřuje se na základní techniky pohybu a fixaci inventáře.

#### Soutěžící (Competitor)
Soutěžící využívá pokročilou analytiku pro ladění svého stylu. Je schopen definovat vlastní tréninkové rutiny a spravovat konfigurace, které jsou uloženy na lokální bázi.

#### Taktik (Coach)
Účet Taktika je určen pro lídry klanů. Může spravovat sdílené taktické dokumenty pro celý tým, definovat globální pravidla pro "hotbar" layouty a provádět týmové přehledy.

> [!CAUTION]
> V případě nekonzistentního chování myši nebo změn v nastavení FOV je třeba **provést rekalibraci svalové paměti**, aby nedošlo k degradaci přesnosti při soubojích.

## Nastavení a Konfigurace

Vanguard je koncipován jako soubor standardizovaných profilů pro rychlou aplikaci.

### CLI (Command Line Interface)

```bash
# Aplikace standardizovaného PvP profilu
vanguard apply --profile competitive --fov 90
vanguard verify --integrity --check-mouse-accel
Konfigurace prostředí
<details>
<summary><b>config.json (Standardizovaný layout)</b></summary>

JSON
{
  "pvp_settings": {
    "fov": 90,
    "sensitivity": 45,
    "dynamic_fov": false,
    "hotbar_layout": [
      "sword",
      "rod",
      "gapple",
      "lava_bucket",
      "blocks",
      "water_bucket",
      "pearl",
      "blocks",
      "potion"
    ]
  }
}
</details>

<details>
<summary><b>keybinds.yml (Efektivní přístup)</b></summary>

YAML
keybinds:
  - action: "slot_1"
    key: "1"
  - action: "slot_2"
    key: "R"
  - action: "slot_3"
    key: "F"
  - action: "slot_4"
    key: "V"
  - action: "toggle_sprint"
    key: "CTRL"
