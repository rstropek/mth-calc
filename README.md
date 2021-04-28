[![Build and publish crate](https://github.com/rstropek/mth-calc/actions/workflows/build-and-publish.yaml/badge.svg)](https://github.com/rstropek/mth-calc/actions/workflows/build-and-publish.yaml)
![Crates.io](https://img.shields.io/crates/d/mth_calc)

# Multi-Threaded Calculation

## Introduction

This crate contains helper functions that execute given closures in parallel on all available processors.

Note that this crate's main purpose is to demonstrate certain features of Cargo. If you find it useful, feel free to grab whatever you need. However, do not expect that this crate will be functionally extended or maintained on a regular basis. As said, its mainly used during Cargo trainings for demonstrating the following aspects of Cargo:

* Basics of crate documentation (including samples)
* `cargo doc`
* `cargo test` and `cargo test --doc`
* `cargo publish` (with and without `--dry-run`)
* Dependency types (*crates.io*, GitHub, folder)

## Links

* [Session material (e.g. slides, samples)](https://github.com/rstropek/CargoIntro)
* This example has been created for a session for the [Rust Linz Meetup](https://rust-linz.at)
