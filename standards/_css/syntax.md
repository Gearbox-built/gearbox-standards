---
order: 10
---

### Syntax

* Use soft tabs with two spaces—they're the only way to guarantee code renders the same in any environment.
* Use double-quotes (").
* When grouping selectors, keep individual selectors to a single line.
* Include one space before the opening brace of declaration blocks for legibility.
* Place closing braces of declaration blocks on a new line.
* Include one space after `:` for each declaration.
* Each declaration should appear on its own line for more accurate error reporting.
* End all declarations with a semi-colon, even the last one.
* Comma-separated property values should include a space after each comma (e.g., `box-shadow`).
* Don't include spaces after commas _within_ `rgb()`, `rgba()`, `hsl()`, `hsla()`, or `rect()` values. This helps differentiate multiple color values (comma, no space) from multiple property values (comma with space).
* Prefix property values or color parameters with a leading zero (e.g., `0.5` instead of `.5` and `-0.5px` instead of `-.5px`).
* Lowercase all hex values, e.g., `#fff`. Lowercase letters are much easier to discern when scanning a document as they tend to have more unique shapes.
* Use shorthand hex values where available, e.g., `#fff` instead of `#ffffff`.
* Quote attribute values in selectors, e.g., `input[type="text"]`. [They’re only optional in some cases](http://mathiasbynens.be/notes/unquoted-attribute-values#css), and it’s a good practice for consistency.
* Avoid specifying units for zero values, e.g., `margin: 0;` instead of `margin: 0px;`.

Questions on the terms used here? See the [syntax section of the Cascading Style Sheets article](http://en.wikipedia.org/wiki/Cascading_Style_Sheets#Syntax) on Wikipedia.