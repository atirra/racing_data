# Change Log

All notable changes to this project will be documented in this file.

This project adheres to [Semantic Versioning](http://semver.org/).


## [1.0.0b11] - 2016-07-29

### Fixed
- Fix TypeError in Runner.at_distance (from @justjasongreen)


## [1.0.0b10] - 2016-07-29

### Fixed
- Fix TypeError in Runner.actual_distance (from @justjasongreen)


## [1.0.0b9] - 2016-07-29

### Fixed
- Fix TypeError in Performance.actual_distance (from @justjasongreen)


## [1.0.0b8] - 2016-07-29

### Fixed
- Fix ZeroDivisionError in Performance.speed (from @justjasongreen)


## [1.0.0b7] - 2016-07-29

### Fixed
- Fix TypeError when calculating actual_weight for performances without carried values (from @justjasongreen)


## [1.0.0b6] - 2016-07-29

### Fixed
- Fix TypeError when calculating actual_distance for runners in races without track_circ/straight values (from @justjasongreen)


## [1.0.0b5] - 2016-07-29

### Fixed
- Check for None values in Runner/Performance/PerformanceList calculations (from @justjasongreen)


## [1.0.0b4] - 2016-07-28

### Added
- constants.ALTERNATIVE_TRACK_NAMES (from @justjasongreen)

### Changed
- Runner.on_track property includes alternative track names in its filter (from @justjasongreen)


## [1.0.0b3] - 2016-07-26

### Added
- Implement calculated properties for Performance objects (from @justjasongreen)
- Implement performance lists via the PerformanceList class (from @justjasongreen)
- Implement calculated properties for Runner objects (from @justjasongreen)

### Changed
- Use flake8 instead of pytest-flake8 (from @justjasongreen)


## [1.0.0b2] - 2016-07-24

### Added
- Implement __str__ methods for all concrete entity types (from @justjasongreen)

### Fixed
- Fixed Coveralls integration (from @justjasongreen)


## [1.0.0b1] - 2016-07-24

### Changed
- Implement query locks to prevent duplicate data in multithreaded environments (from @justjasongreen)


## [1.0.0a2] - 2016-07-23

### Added
- Create database indexes (from @justjasongreen)

### Fixed
- Entity.get_property_cache method no longer shares cache across instances (from @justjasongreen)


## [1.0.0a1] - 2016-07-22

### Added
- Get meets by date (from @justjasongreen)
- Get races by meet (from @justjasongreen)
- Get meet by race (from @justjasongreen)
- Get runners by race (from @justjasongreen)
- Get race by runner (from @justjasongreen)
- Get horse by runner (from @justjasongreen)
- Get jockey by runner (from @justjasongreen)
- Get trainer by runner (from @justjasongreen)
- Get performances by horse (from @justjasongreen)
- Get horse by performance (from @justjasongreen)
- Get performances by jockey (from @justjasongreen)
- Get jockey by performance (from @justjasongreen)
- Automatically check manifest contents on Travis CI (from @justjasongreen)

## Changed
- Move from setuptools_scm to bumpversion for version management (from @justjasongreen)


## [1.0.0a0] - 2016-07-21

### Added
- Set up project (from @justjasongreen)


[1.0.0b11]: https://github.com/justjasongreen/racing_data/compare/1.0.0b10...1.0.0b11
[1.0.0b10]: https://github.com/justjasongreen/racing_data/compare/1.0.0b9...1.0.0b10
[1.0.0b9]: https://github.com/justjasongreen/racing_data/compare/1.0.0b8...1.0.0b9
[1.0.0b8]: https://github.com/justjasongreen/racing_data/compare/1.0.0b7...1.0.0b8
[1.0.0b7]: https://github.com/justjasongreen/racing_data/compare/1.0.0b6...1.0.0b7
[1.0.0b6]: https://github.com/justjasongreen/racing_data/compare/1.0.0b5...1.0.0b6
[1.0.0b5]: https://github.com/justjasongreen/racing_data/compare/1.0.0b4...1.0.0b5
[1.0.0b4]: https://github.com/justjasongreen/racing_data/compare/1.0.0b3...1.0.0b4
[1.0.0b3]: https://github.com/justjasongreen/racing_data/compare/1.0.0b2...1.0.0b3
[1.0.0b2]: https://github.com/justjasongreen/racing_data/compare/1.0.0b1...1.0.0b2
[1.0.0b1]: https://github.com/justjasongreen/racing_data/compare/1.0.0a2...1.0.0b1
[1.0.0a2]: https://github.com/justjasongreen/racing_data/compare/1.0.0a1...1.0.0a2
[1.0.0a1]: https://github.com/justjasongreen/racing_data/compare/1.0.0a0...1.0.0a1
[1.0.0a0]: https://github.com/justjasongreen/racing_data/tree/1.0.0a0
