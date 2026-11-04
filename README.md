# FreeECU Tune Library

Ready-made tunes for [FreeECU](https://www.overtake.gg/downloads/freeecu-programmable-ecu-boost-torque-launch-pops-bangs.87975/), the programmable ECU app for Assetto Corsa (CSP) by GHOSTLANE.

In the game, open FreeECU, go to the **Maps** tab and click **Show tunes for this car** in the **Tune library** section. Pick a tune and click **Load**. Your current tune is saved as a map first, so you can always go back.

## Submit your tune

1. In FreeECU, **Maps** tab, click **Copy code**.
2. Post the code in the FreeECU thread on OverTake, together with the car, a name for the tune and a short description (what it does, which settings matter).
3. Good tunes get added here, with your name as the author.

## Format

One file per car in the `tunes` folder, named after the car's folder ID (the folder name in `content/cars`, also the part after `FECU1:` in a tune code), for example `tunes/bmw_m240_g42_tuned_mlz.json`:

```json
{
  "tunes": [
    {
      "name": "Stage 2 Street",
      "author": "GHOSTLANE",
      "description": "More boost, launch at 4500 rpm, pops and bangs on.",
      "code": "FECU1:bmw_m240_g42_tuned_mlz:..."
    }
  ]
}
```

FreeECU checks every code the same way as "Paste code": all values are limited to the ranges of the app's sliders, and codes for other cars are skipped.

## Privacy

FreeECU only downloads the list for the current car when you click the button. Nothing is uploaded, no account is needed.

---

**Deutsch:** Fertige Tunes für FreeECU. Im Spiel Tab **Maps**, Abschnitt **Tune-Bibliothek**, „Tunes für dieses Auto anzeigen“. Eigenes Tune einreichen: „Code kopieren“ und mit Auto, Name und kurzer Beschreibung im FreeECU-Thread auf OverTake posten.
