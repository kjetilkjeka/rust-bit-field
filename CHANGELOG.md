# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Added
### Changed
 - `BitField` trait now has a `BIT_LENGTH` associated const instead of a `bit_length` associated function.
### Deprecated
### Removed
### Fixed
### Security

## [0.9.0] - 2017-10-15
### Changed
 - Bit indexes in `BitField` is now `usize` instead of `u8`.

## [0.8.0] - 2017-07-16
### Added
 - `BitArray` trait to make bit indexing possible with slices.
### Changed
 - `bit_length` in `BitField` is now an associated function instead of a method (`bit_length()` instead of `bit_length(&self)`)

## [0.7.0] - 2017-01-16
### Added
 - `BitField` was also implemented for: `i8`, `i16`, `i32`, `i64` and `isize`
### Changed
 - `length()` method in `BitField` is now called `bit_length()`
 - `get_range()` method in `BitField` is now called `get_bits()`
 - `set_range()` method in `BitField` is now called `set_bits()`
### Removed
 - `zero()` and `one()` constructor was removed from `BitField` trait.
