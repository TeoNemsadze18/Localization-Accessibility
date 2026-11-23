# LOC-LNG-001 - Automatic Language Switch to Georgian When Selecting Another Policy Category

* **Severity:** Medium
* **Environment:** Production · macOS Sonoma 14.4 · MacBook Air (Apple M1) · Safari 17.4
* **Reproducibility:** 100%

## Summary
When viewing the "Exchange and Return Policy in Stores" page with the website language set to English, selecting another policy category from the left sidebar switches the entire page and navigation to Georgian, and returning to the initial policy category keeps the content in Georgian.

## Preconditions
Website language is set to English.

## Steps
1. Scroll down to the footer.
2. Under the policy/group section in the footer, click on "Exchange and Return Policy in Stores".
3. Click on a different policy category on the left sidebar (e.g., another product exchange and return policy).
4. Observe the language of the page and navigation, then return to the initial policy category.

## Actual
The website language automatically switches from English to Georgian, and returning to the initial category keeps the page in Georgian.

## Expected
The selected website language (English) should remain preserved across all policy categories and navigation states.

## Notes
Subcategory: Localization. Selected language state is lost or overridden when navigating between policy categories on policy pages in Production.
