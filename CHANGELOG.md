# Changelog

All notable changes in this fork are documented in this file.

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

## [Comparison Summary]

Compared against: https://github.com/mlamberts78/weather-chart-card (upstream/master)

Ahead by 3 commits:
- 3d2c771 Fixed Version
- 4421ec5 Add show_uv option
- f32226a Added UV Switch

Files changed in committed fork diff:
- README.md
- dist/weather-chart-card.js
- package.json
- src/main.js
- src/weather-chart-card-editor.js
