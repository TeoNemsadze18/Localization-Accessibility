# LOC-FLT-002 - Untranslated Georgian Filter Option ("შერეული მასალები") Under "Composition" in "Bath" When Language Is English

* **Severity:** Medium
* **Environment:** Production · macOS Sonoma 14.4 · MacBook Air (Apple M1) · Safari 17.4
* **Reproducibility:** 100%

## Summary
Navigating to "Home -> Bath" with the website language set to English leaves one option under the "Composition" filter untranslated in Georgian ("შერეული მასალები") instead of displaying "Mixed materials".

## Preconditions
User is on the website with the full navigation menu set to English.

## Steps
1. Open the "Home" menu.
2. Select the "Bath" submenu.
3. Expand or inspect the "Composition" filter and review the available options.

## Actual
One option under the "Composition" filter is displayed in Georgian ("შერეული მასალები") instead of English.

## Expected
All options under the "Composition" filter in the "Bath" section should be translated into English when English is selected, displaying "Mixed materials" instead of "შერეული მასალები".

## Notes
Localization issue. Missing or unmapped English localization string for a specific filter option in Production.
