# Smartwatch band compatibility

Which band fits which smartwatch: attachment system and lug width for **313 Garmin, Apple Watch and Samsung Galaxy Watch models**, in one open table.

Maintained by [Clipz-it](https://clipz-it.com), a French store for replacement smartwatch bands. Updated 2026-10-27.

## Files

| File | Content |
|---|---|
| [`watch_band_compatibility.csv`](watch_band_compatibility.csv) | One row per watch model |
| [`watch_band_compatibility.json`](watch_band_compatibility.json) | Same rows, plus update date and licence |

## Columns

| Column | Meaning |
|---|---|
| `brand` | Garmin, Apple or Samsung |
| `model` | Watch model and case size when it changes the band |
| `attachment` | `QuickFit` (Garmin clip), `Quick Release (spring bar)` (standard pin with a lever), `Apple slot connector`, or a Samsung proprietary connector |
| `width_mm` | Band width at the lug, in millimetres (empty for Apple and Samsung proprietary connectors) |
| `apple_size_group` | Apple Watch only: `small` or `large` band family |
| `also_fits` | Other attachment the watch accepts, if any |
| `bands_url` | Page listing the bands that fit this model |

## Three things people get wrong

1. **QuickFit and Quick Release are not interchangeable, even at the same width.** A 22 mm QuickFit band will not mount on a 22 mm Quick Release watch, and the reverse. Check the `attachment` column first, then the width.
2. **Apple Watch "42 mm" means two different bands.** Series 1 to 3 in 42 mm take the large family (with 44/45/46/49 mm). Series 10 and later in 42 mm take the small family (with 38/40/41 mm).
3. **Galaxy Watch8 and Ultra use their own connector.** Standard 20 mm Samsung bands fit Galaxy Watch4 to Watch7 and FE, not Watch8 or Ultra.

## How the data is built

This is the compatibility reference Clipz-it uses to list bands on its store, built from the manufacturers' specifications (Garmin, Apple and Samsung support pages and manuals). Models whose fit is not yet confirmed are left out rather than guessed. Corrections are welcome as issues.

## Related study

[Are third-party smartwatch bands reliable? 157,216 Amazon ratings, 661 negative reviews and 303 Reddit discussions](https://doi.org/10.5281/zenodo.23698153) (Clipz-it, October 2026, open data on Zenodo).

## Licence

Data under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Reuse it freely, with a link to this repository or to [clipz-it.com](https://clipz-it.com).

---

### En français

Tableau ouvert de compatibilité des bracelets de montres connectées : système d'attache et largeur pour 313 modèles Garmin, Apple Watch et Samsung Galaxy Watch. Version lisible en ligne : [tableau de compatibilité des bracelets Garmin](https://clipz-it.com/pages/tableau-compatibilite-bracelets-garmin).
