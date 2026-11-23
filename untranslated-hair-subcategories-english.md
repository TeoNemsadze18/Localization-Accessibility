# LOC-CAT-001 - Untranslated Subcategories Displayed Under "Beauty > Hair" When Language Is English

* **Severity:** Medium
* **Environment:** Production · macOS Sonoma 14.4 · MacBook Air (Apple M1) · Safari 17.4
* **Reproducibility:** 100%

## Summary
When the website language is set to English and the user navigates to the "Hair" section under "Beauty", three subcategories ("თმის ტონერი", "თმის ცვილი", "თმის ფიქსაციის პუდრი") remain untranslated and display in Georgian instead of English.

## Preconditions
Website language is set to English.

## Steps
1. Click on the "Beauty" category in the main navigation menu.
2. Navigate to the "Hair" section.
3. Observe the language of the displayed subcategories.

## Actual
Three subcategories ("თმის ტონერი", "თმის ცვილი", "თმის ფიქსაციის პუდრი") are displayed in Georgian instead of English.

## Expected
All subcategories under "Beauty > Hair" should be displayed in English (e.g., Hair Toner, Hair Wax, Hair Styling Powder / Volumizing Hair Powder).

## Notes
Subcategory: Localization. Missing or unmapped English localization strings for specific hair subcategories in Production.
