# RevealLine archive 20

Retain the exact original v0.60.5 and v0.60.6 releases while newer editions become current. This repository contains small original metadata and bounded publication tools. Hosted preparation fetches each published original ZIP, verifies every member against its original manifest, and deletes the temporary ZIP before the next cohort. It never rebuilds the game or commits expanded payload files.

The expected complete site is **1,390 files / 626,344,204 bytes**, leaving **173,655,796 bytes** under the unchanged **800,000,000-byte** cap. All 695 preceding paths / 313,159,164 bytes remain exact, including every v0.60.5 member, the root index and shared Release explorer bridge. The 690-member v0.60.6 site and its original metadata/qualification add 695 canonical files / 313,185,040 bytes. Source TARs and downloaded distribution ZIPs are not served as site members.

The preserved root still links to [v0.60.5](https://mekhovov.github.io/revealline-archive-20/releases/v0.60.5/site/game/); [v0.60.6](https://mekhovov.github.io/revealline-archive-20/releases/v0.60.6/site/game/) has its own immutable route. Release explorer uses the established immediate redirect plus visible fallback to the main live catalog. Metadata, source qualifications, annotated tags and frozen sources stay unchanged. See `source-lock.json`, original `input-authority.json` and additive `input-authority-v0606.json`. An authored inventory is an expectation, not evidence of deployment or archive admission.

## Review and publication

The original bootstrap was reviewed against a README-only seed and published through its normal source PR. The v0.60.6 append starts from accepted Archive20 main `861182677647a1678064b64b0d46c11999a0e731` on `codex/retain-v0606`. Review all related hunks and exact metadata; a normal guarded PR merge triggers one automatic main-push Pages run. Actions Pages, main-only `github-pages` policy and both main-only workflow jobs remain unchanged. Manual dispatch is only for a necessary separately recorded retry, never a duplicate running deployment. The workflow does not advertise PR CI or perform PR deployment.

The workflow checks out pinned source `a13ab970222498d7c5fa7f62f9fc04fe436979d5` only for the unchanged bounded ZIP extractor and corruption tests. It verifies both annotated tags, original source/metadata/qualification, every extracted member and the full final inventory. Preserve contents-read and deploy-only Pages/id-token permissions, the 3 GiB runner free-space floor, 800 MB/20,000-file limits and original failure receipts.

Run `python3 -B -m unittest discover -s tools -p 'test_*.py' -v` for small offline fixtures, and the pinned extractor's `test_extract_current.py` cohort separately. Those are synthetic checks, not a payload build or public acceptance. Never run full preparation on a nearly full local disk.

After successful hosted deployment, retain actual source/tree/run/deployment/status and only the small receipt artifact: complete expected inventory, preparation receipt and each original-ZIP receipt. Audit all 1,390 public files with fresh before/after authority checks and independent row reconciliation. Explicitly verify that all old 695 path/size/hash tuples are preserved.

Separately exercise both retained editions, real play/capture, Pause/explicit Resume, v0.60.6 Settings/quick Sound/Back preserving pause, focus return and Release explorer → current main catalog → Back in the actual UI. Only then may the main publisher admit the appended route. Main-origin v0.60.6 acceptance does not prove the new archive deployment. Archive-origin storage does not migrate main-origin saves. Preserve saving-lease warnings and observed limits; no offline, physical-device, BFCache or whole P03/P05/P18 acceptance follows.

Future appends must preserve all canonical rows and fit the same cap. Never overwrite original release assets, reuse stale admission evidence, repurpose existing URLs or raise the cap.
