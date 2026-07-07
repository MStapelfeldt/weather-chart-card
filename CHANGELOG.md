# Changelog

All notable changes in this fork are documented in this file.

## [1.0.6] - Main forecast rendering fixes and locale translation pass

### Changed
- Updated main forecast summary rendering for tomorrow and day-after blocks to use robust conditional template sections.
- Switched forecast low-temperature label usage in the main summary from a generic minimum key to locale temperature labels.
- Added fallback display logic for forecast values when low temperature is unavailable.
- Updated package version to 1.0.6.

### Fixed
- Fixed malformed copied template conditions in main forecast markup that caused parser/compile failures.
- Corrected and standardized multiple locale translations in src/locale.js (including wording consistency and obvious phrasing errors).
- Corrected Greek cardinal direction mapping values in locale definitions.
- Regenerated dist bundle to reflect source and locale updates.

## [1.0.5] - Main forecast expansion and layout/translation refinements

### Added
- Extended the main weather area with forecast blocks for upcoming days (tomorrow/day-after flow).

### Changed
- Merged development branch changes for the extended main forecast view.
- Updated package versioning through the 1.0.5 pre-release cycle (1.0.5a/1.0.5b) before final 1.0.5f.
- Regenerated dist bundle after forecast feature updates.

### Fixed
- Improved main forecast presentation and overall card layout alignment.
- Fixed forecast temperature display issues in the new main forecast section.
- Updated translation text entries related to the forecast/main view updates.

## [1.0.4] - UI control fixes and repository asset/documentation cleanup

### Added
- Added previously missing images/assets required by README and card documentation.

### Changed
- Updated README content and image links for consistency and correctness.
- Updated package metadata/version to 1.0.4 at release point cccc044.

### Fixed
- Fixed button behavior in editor/UI interactions.
- Fixed radio button behavior in editor/UI interactions.

## [1.0.3] - Include unmerged Pull Requests from mlamberts78 (246, 252 and 262)

### Added
- Added chart style 3 option in the editor and chart rendering.
- Added forecast options for show_rainfall and disable_tooltips.
- Added precipitation label font size option (precip_labels_font_size).

### Changed
- Updated README wording and formatting for the fork.
- Updated README repository links, badges, and image URLs from mlamberts78/weather-chart-card to mstapelfeldt/weather-chart-card.
- Normalized markdown table spacing in README.
- Fixed supported-languages anchor link casing in README.
- Renamed visibility config key usage from visibility to visibility_entity in card data mapping.

### Breaking
- If your config used visibility, update it to visibility_entity.

## [1.0.2] - Fork changes vs upstream/master

### Added
- Added show_uv option to card stub configuration.
- Added Show UV toggle in the card editor.
- Added conditional rendering support for showing/hiding UV in attributes.

### Changed
- Fork metadata updates in package.json:
  - repository changed to git@github.com:mstapelfeldt/weather-chart-card.git
  - author changed to Moritz Stapelfeldt
- Lint script normalized from eslint 'src/**/*.js' to eslint src/**/*.js.
- README top section changed from unmaintained notice to active fork notice.
- Dist bundle regenerated to include source updates.
