# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]

## [1.4.0] - 2018-03-01

### Added
- Version of MADR into [ADR-0000](template/0000-use-markdown-architectural-decision-records.md) of the template. Fixes [#5](https://github.com/adr/madr/issues/5)
- `README.md`: Added wints on the filenames.
- More ADRs on MADR
- Added`LICENSE` file

### Changed
- `README.md`: Removed section "Background Information" as the information is contained at <http://adr.github.io>, too. Fixes [#4](https://github.com/adr/madr/issues/4)

## [1.3.1] – 2018-02-13

### Fixed
- Replace "alternative" by "option" in all `md` files
- Update to new "Decision Outcome" format in all `md` files

## [1.3.0] – 2018-01-30

### Changed
- Changed template to be closer to the [Y-Statements](https://www.infoq.com/articles/sustainable-architectural-design-decisions).
  Especially rename "alternative" to "option".
- Restructured syntax of "Decision Outcome".
  Positive and negative consequences as separate bullet list.
- Rename "point" to "argument" (which reverts the change of version 1.2.0)
- Number "arguments" from a to c. Re-use "variables" a to c to guide the author that the same topic should be handled by the enumeration. e..g, performance, ...
- Exchange `+` and `-` by "Good, because ..." and "Bad, because ..."
- Remove emphasize of "User Story:"

## [1.2.0] – 2018-01-26

### Added
- Add installation instructions using `npm`.

### Changed
- Placeholders changed from `*[PLACEHOLDER]*` to `[PLACEHOLDER]` to have a single pair of enclosing characters (`[]`) instead of two (`*[]*`).
- Rename `argument 1 pro` to `pro point` and `argument 1 con` to `con point`

## [1.1.1] – 2017-12-05

### Changed
- Simplify `package.json` and fix name.

## [1.1.0] – 2017-12-04

### Changed
- No change in the template itself.
- Use [adr-log](https://adr.github.io/adr-log/) to generate links to the ADRs in `docs/adr/index.md`.
- `template.md` is not part of the log, but a separate text block in `docs/adr/index.md`.
- Link to new homepage of MADR: <https://adr.github.io/madr/>.
- Refined justification of [ADR-0000](docs/adr/0000-use-markdown-architectural-decision-records.md).
- Refined `README.md`.

### Fixed
- Fixed internal links in `docs/adr/index.md`.
- Fixed typo in `docs/adr/0000-use-markdown-architectural-decision-records.md`.

## [1.0.0] – 2017-09-09

First release of Markdown Architectural Decision Records.

[Unreleased]: https://github.com/adr/madr/compare/1.4.0...master
[1.4.0]: https://github.com/adr/madr/compare/1.3.1...1.4.0
[1.3.1]: https://github.com/adr/madr/compare/1.3.0...1.3.1
[1.3.0]: https://github.com/adr/madr/compare/1.2.0...1.3.0
[1.2.0]: https://github.com/adr/madr/compare/1.1.1...1.2.0
[1.1.1]: https://github.com/adr/madr/compare/1.1.0...1.1.1
[1.1.0]: https://github.com/adr/madr/compare/1.0.0...1.1.0
[1.0.0]: https://github.com/adr/madr/releases/tag/1.0.0
