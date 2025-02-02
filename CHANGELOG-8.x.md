# Change for 8.x

This changelog references the relevant changes (bug and security fixes) done to `orchestra/testbench-dusk`.

## 8.6.6

Released: 2023-07-22

### Changes

* Update `orchestra/dusk-updater` to support ChromeDriver `115`+.

## 8.6.5

Released: 2023-07-12

### Changes

* Update minimum support for Laravel Dusk v7.8.0+. ([v7.7.1...v7.8.0](https://github.com/laravel/dusk/compare/v7.7.1...v7.8.0))
* Update skeleton to match v10.2.5.

## 8.6.4

Released: 2023-06-13

### Changes

* Update minimum support for Testbench v8.5.7+. ([v8.5.0...v8.5.7](https://github.com/orchestral/testbench/compare/v8.5.0...v8.5.7))

## 8.6.3

Released: 2023-05-26

### Changes

* Update skeleton to match v10.2.2.

## 8.6.2

Released: 2023-05-17

### Changes

* Update skeleton to match v10.2.1.

## 8.6.1

Released: 2023-05-09

### Changes

* Update skeleton to match v10.2.0.
* Update minimum support for Laravel Dusk v7.7.1+. ([v7.7.0...v7.7.1](https://github.com/laravel/dusk/compare/v7.7.0...v7.7.1))

## 8.6.0

Released: 2023-04-18

### Changes

* Update minimum support for Testbench v8.5.0+. ([v8.4.0...v8.5.0](https://github.com/orchestral/testbench/compare/v8.4.0...v8.5.0))

## 8.5.0

Released: 2023-04-14

### Changes

* Update minimum support for Testbench v8.4.0+. ([v8.3.0...v8.4.0](https://github.com/orchestral/testbench/compare/v8.3.0...v8.4.0))
* Supports PHPUnit 10.1.

## 8.4.1

Released: 2023-04-12

### Changes

* Update skeleton to match v10.0.6.

## 8.4.0

Released: 2023-04-05

### Changes

* Update minimum support for Testbench v8.3.0+. ([v8.2.1...v8.3.0](https://github.com/orchestral/testbench/compare/v8.2.1...v8.3.0))
* Add `setUpTheTestEnvironmentTraitToBeIgnored()` method to determine `setup<Concern>` and `teardown<Concern>` with imported traits that should be used on a given trait.

## 8.3.1

Released: 2023-04-03

### Changes

* Update minimum support for Testbench v8.2.1+. ([v8.2.0...v8.2.1](https://github.com/orchestral/testbench/compare/v8.2.0...v8.2.1))

## 8.3.0

Released: 2023-04-01

### Changes

* Update minimum support for Testbench v8.2.0+. ([v8.1.0...v8.2.0](https://github.com/orchestral/testbench/compare/v8.1.0...v8.2.0))

## 8.2.0

Released: 2023-03-27

### Changes

* Update minimum support for Testbench v8.1.0+. ([v8.0.8...v8.1.0](https://github.com/orchestral/testbench/compare/v8.0.8...v8.1.0))

## 8.1.3

Released: 2023-03-10

### Changes

* Update minimum support for Testbench v8.0.8+. ([v8.0.7...v8.0.8](https://github.com/orchestral/testbench/compare/v8.0.7...v8.0.8))

## 8.1.2

Released: 2023-03-09

### Changes

* Update minimum support for Testbench v8.0.7+. ([v8.0.3...v8.0.7](https://github.com/orchestral/testbench/compare/v8.0.3...v8.0.7))


## 8.1.1

Released: 2023-03-03

### Changes

* Allow using environment variable `DUSK_HEADLESS_MODE` value (when available).

## 8.1.0

Released: 2023-03-02

### Added

* Allow using `--headless=new` available from Chrome v109.

### Changes

* Update minimum support for Laravel Dusk v7.7.0+. ([v7.6.0...v7.7.0](https://github.com/laravel/dusk/compare/v7.6.0...v7.7.0))

## 8.0.3

Released: 2023-02-24

### Changes

* Update minimum support for Testbench v8.0.3+. ([v8.0.1...v8.0.3](https://github.com/orchestral/testbench/compare/v8.0.1...v8.0.3))

## 8.0.2

Released: 2023-02-17

### Changes

* Update minimum support for Testbench v8.0.1+. ([v8.0.0...v8.0.1](https://github.com/orchestral/testbench/compare/v8.0.0...v8.0.1))

## 8.0.1

Released: 2023-02-16

### Fixes

* Fixes generating `phpunit.dusk.xml` when executing `package:dusk` command on PHPUnit 10.

## 8.0.0

Released: 2023-02-14

### Changes

* Update support for Laravel Framework v10.
* Increase minimum PHP version to 8.1 and above (tested with 8.1 and 8.2).
