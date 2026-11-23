# LOC-FLT-001 - Untranslated Color Filter Options Under "Lip Makeup" When Language Is Georgian

* **Severity:** Medium
* **Environment:** Production · macOS Sonoma 14.4 · MacBook Air (Apple M1) · Safari 17.4
* **Reproducibility:** 100%

## Summary
When the website language is set to Georgian and the user navigates to "თავის მოვლა -> დეკორატიული კოსმეტიკა -> ტუჩის მაკიაჟი", scrolling down the "ფერები" (colors) filter list shows none of the color options translated into Georgian.

## Preconditions
Website language is set to Georgian (ქართული).

## Steps
1. Ensure the website language is set to Georgian (ქართული).
2. Navigate to "თავის მოვლა -> დეკორატიული კოსმეტიკა -> ტუჩის მაკიაჟი".
3. Locate the colors filter ("ფერები") and scroll down through the available color options.

## Actual
None of the color options under the filter are displayed in Georgian after scrolling down.

## Expected
All color filter options under "ტუჩის მაკიაჟი" should be properly translated into Georgian when Georgian is selected.

## Notes
Subcategory: Localization. Missing or untranslated Georgian localization strings for color filter values in Production.
