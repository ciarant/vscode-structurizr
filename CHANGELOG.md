# Change Log

## [v0.0.5] - 2020-07-09
### Fixed
-  '!include' and 'include' highlighting [#2]

## [v0.0.3] - 2020-07-05
### Changed
- Limit 'keyword.control' to workspace, model, views, and !include, use 'support.type' for other Structurizr nouns.
- Type names support both upper and lowercase forms (e.g. System, system, Landscape, landscape)
- autoLayout, filtered now treated as attributes rather than keywords

### Added
- Keywords: enterprise
- Types: infrastructureNode, styles, branding, element
- Properties: icon, width, height, stroke, border, opacity, metadata, description, thickness, dashed, routing, position

### Fixed
- Relationship arrows now highlight correctly

## [v0.0.2] - 2020-07-04
### Changed
- Use `dsl` file extension

## [v0.0.1] - 2020-07-04
- Initial release with comment, keyword, and string literal highlighting
