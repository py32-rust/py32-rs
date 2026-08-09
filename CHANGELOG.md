# Change Log

All notable changes to this project will be documented in this file.

## v0.2.2 2026-08-09

### Changed

 - Modified USART peripheral register `CR2` to restrict `STOP` field in all devices to be 1 bit instead of 2 (resolves github issue #11)

## v0.2.1 2025-01-28

### Added

 - Added array access to timer CCR registers
 - Added py32f040 device
 - `scripts/README.md` to show usage of scripts
 - modified scripts to handle `bitRange` vs `bitOffset` and `bitWidth` usage in svd files

### Changed

 - Renamed field `DBG_TIM14_STOP` to `DBG_TIMER14_STOP` in `DBG` peripheral for py32f002b to make it consistent with other devices

### Removed

 - Removed renaming of timer CCR registers

## v0.2.0 2024-12-28

### Added

 - Clustered DMA registers into channels
 - Added arrays to DMA registers
 - Add direct 8-bit access to USART data register

### Changed

 - Updated Repository url in `README.md` and `scripts/makecrates.py`
 - Renamed `DDF` field in spi CR1 register to `DFF` to match datasheet for device py32f002b
 - Updated form version from 0.10.0 to 0.12.1
 - Updated svdtools version from 0.3.0 to 0.3.14

## v0.1.1 2024-10-10

## V0.1.0 2024-09-27

## v0.0.1 2023-06-10

 - Original Release

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).
