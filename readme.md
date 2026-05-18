# Mario Kart 64 — Battle Mode Item Curve Patch

## Patch Info

| Field | Value |
|-------|-------|
| Patch file | `mk64_eu_battle_curve.ips` |
| Base ROM | Mario Kart 64 (Europe) PAL (extracted from Wii WAD) |
| ROM size | 12 MB (12,582,912 bytes) |
| Apply with | Lunar IPS, RomPatcher.js, UniPatcher |

---

## What This Patch Does

Modifies the battle mode item probability curve stored in the common data MIO0-compressed block (`ROM 0x132C70`, segment offset `0x8B14`). The 100-slot item table determines the likelihood of each item appearing from an item box.

---

## Item Probabilities

| ID | Item | Vanilla | Patched | Change |
|----|------|--------:|--------:|--------|
| `01` | Single Banana | 10% | 10% | — |
| `02` | Banana Bunch | 5% | 5% | — |
| `03` | Single Green Shell | 5% | 10% | +5% |
| `04` | Triple Green Shell | 20% | 21% | +1% |
| `05` | Single Red Shell | 20% | 16% | −4% |
| `06` | Triple Red Shell | 0% | 10% | ✅ added |
| `08` | Lightning | 0% | 3% | ✅ added (rare) |
| `09` | Fake Item Box | 15% | 10% | −5% |
| `0A` | Invincible Star | 20% | 10% | −10% |
| `0B` | Ghost | 5% | 5% | — |


---

## Screenshots
![Beschreibung](Screenshot1.png)
![Beschreibung](Screenshot2.png)
![Beschreibung](Screenshot3.png)

---

