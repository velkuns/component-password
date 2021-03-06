# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).


## [4.0.0] - 2020-10-29
### Changed
 * New require PHP 7.4+
 * Move some code outside Password class
 * Generator parameters are now on generate method
 * Upgrade phpcodesniffer to v0.7 for composer 2.0
### Added
 * Added tests
 * Set up CI
 * Suggest eureka/component-console as complementary package for password script helper


## [3.x.y] Release v3.x.y
### Changed
 * Require PHP 7.2 min
 * Replace ircmaxell/randomLib generator by internal generator
 * Use php 7 random_int() method for randomization
 * Some clean

## [2.x.y] Release v2.x.y
### Added
 * Add Generator class
 * Add Script generator
### Changed
 * Password as service
 * Move code
 


## [1.0.0] - 2019-04-03
### Added
  * Add Breadcrumb item & controller aware trait
  * Add Flash notification service & controller aware trait
  * Add Menu item & controller aware trait
  * Add meta controller aware trait
  * Add Notification item