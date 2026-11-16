# Warhammer 40,000 5th Edition — New Recruit/BattleScribe work-in-progress repository

## Status: NOT PLAYABLE

This archive contains a `.gst` game-system scaffold and 16 `.cat` faction scaffolds. It also contains two archival catalogues. The initial Black Templars catalogue has one previously entered unit. **This is not a complete New Recruit repository and is not validated as importable or usable for army construction.** No points or rules have been invented in this release.

## Source registration

`references/source-register.csv` records 27 locally supplied source PDFs, their eligibility decisions, byte sizes, and SHA-256 fingerprints. **The PDFs are not redistributed in this archive.** Source registration does not imply that rules, points, options, FAQs or restrictions have been transcribed or verified.

The 2011 Sisters of Battle White Dwarf codex upload contains only the first part. Its second part is still missing. Excluded 6th Edition and 2013 publications are listed for provenance but must not contribute game data.

## Importing

The root `.gst` is the game system and `catalogues/*.cat` are the faction catalogues. New Recruit generally consumes BattleScribe data via a repository distribution, not simply by uploading a ZIP as a playable army. A repository URL/index and an import test remain outstanding. Do not represent this package as a finished, playable dataset.

## Next steps

Transcribe and verify individual army-list entries, options, profiles, points and restrictions against the approved sources, then implement constraints and test against the target New Recruit importer. Forge World additions require their own eligibility and points audit.
