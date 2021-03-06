# Revision history for collection-json

## 1.3.1.3  -- 2019-02-21

* Update cabal.config.
* Integrate cloudbuild fixes from network-arbitrary.
* Update sdist path for new-sdist.

## 1.3.1.2  -- 2018-02-05

* Change sdist to new-sdist.

## 1.3.1.1  -- 2019-01-31

* Change TAG to TAG_NAME in cloudbuild configuration.

## 1.3.1.0  -- 2019-01-22

* Update hspec-discover.
* Update hspec.

## 1.3.0.0  -- 2019-01-02

* Update travis configuration.
* Update network-uri-json.

## 1.2.0.0  -- 2018-12-28

* Update base, network-uri-json, network-arbitrary, hspec, aeson, QuickCheck,
  hspec-discover
* Add disclaimer to README.
* Add envrc to autoload environment.
* add cloudbuild configuration to publish to hackage

## 1.1.2.1  -- 2018-01-20

* Bump network-arbitrary dependency

## 1.1.2.0  -- 2018-01-06

* Externalize network-arbitrary dependency

## 1.1.1.0  -- 2017-12-21

* Bump dependencies on aeson and QuickCheck

## 1.1.0.2  -- 2017-11-17

* use network-uri-json package

## 1.1.0.1  -- 2017-11-11

* reduce prop usage by using it correctly
* add shrink methods to Arbitrary instances
* move Internal module to External
* fix git URL
* remove broken travis deployment

## 1.1.0.0  -- 2017-11-05

* minimize produced JSON in ToJSON instances
* attempt to ensure RFC compliance with hspec
* add more robust URI testing
* add nix development environment (shell.nix, default.nix, collection-json.nix)
* change test suite to hspec

## 1.0.1.0  -- 2017-08-08

* increase aeson upper bound to 1.2
* increase base upper bound to 4.11
* reduce maxSize in quickcheck tests
* cleanup unused pragmas
* update travis configuration
* add travis deployemnt section

## 1.0.0.0  -- 2017-08-05

* Add Property Test Suite
* Add Code of Conduct
* Update README
* Add Travis CI Configuration
* Other Package Updates
