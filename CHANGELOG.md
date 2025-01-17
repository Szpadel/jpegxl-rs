# Change log

<a name="0.10.0"></a>
## 0.10.0 (2024-02-27)

### Changed

- ⬆️ Upgrade `libjxl` to v0.10.0

### Miscellaneous

- 👷 (deps): Bump codecov/codecov-action from 3 to 4

<a name="0.9.0"></a>
## 0.9.0 (2024-01-27)

### Changed

- ⬆️ Upgrade libjxl v0.9.0
- ♻️ Add back derived traits for `JxlBitDepth`

### Fixed

- 💚 Update coverage attribute

### Miscellaneous

- 👷 (deps): Bump actions/cache from 3 to 4
- ⚰️ Remove unused color encoding setup when encoding JPEG

<a name="0.8.3"></a>
## 0.8.3 (2023-10-13)

### Added

- ➕ Use lcms2 to validate ICC profiles

### Changed

- ⬆️ Upgrade lcms2
- ♻️ Remove type parameter from internal function
- ♻️ Refactor `PixelType`

### Fixed

- 🐛 Fix rare pixel type

### Miscellaneous

-  ️👷 (deps): Bump actions/checkout from 3 to 4
-  👷 Add dependabot
-  👷 Ignore `jpegxl-sys`` when doing code coverage


<a name="0.8.2"></a>

## 0.8.2 (2023-06-14)

### Added

- ✨ Add `uses_original_profile` to `JxlEncoderBuilder`

### Changed

- ⬆️ Upgrade `libjxl` to v0.8.2

### Removed

- 🔥 Remove unused intermediate structures

### Miscellaneous

- 📄 Add license notice to new files

<a name="0.8.0"></a>

## 0.8.0 (2023-01-19)

### Added

- ✨ Add utils for checking signature
- ✨ Add resizable threads parallel runner

### Changed

- 🚸 Don't return error if JPEG reconstruction fails
- ⬆️ Upgrade `libjxl` to 0.8.0

### Miscellaneous

- 📝 Update several docs

<a name="0.7.0"></a>

## 0.7.0 (2022-08-13)

### Changed

- ♻️ Separate source to a separate crate
- ⬆️ Upgrade `libjxl` to v0.7
- ♻️ Move `jpegxl-sys` into workspace
- 🏗️ Use system `libjxl` by default
- ⬆️ Update `image-rs` library

### Miscellaneous

- 📝 Update docs to the latest address

<a name="0.6.1"></a>

## 0.6.1 (2021-11-03)

### Changed

- ⬆️ Upgrade `libjxl` to v0.6.1

### Miscellaneous

- 📝 Add CHANGELOG.md

<a name="0.6.0"></a>

## 0.6.0 (2021-10-13)

### Added

- ✨ Add LUMA only color encoding
- ✨ Automatically figure out pixel types
- ✨ Remove size requirement for JPEG data

### Changed

- ⬆️ Upgrade `libjxl` to v0.6

### Fixed

- 💚 Fix memory leaks
- 🐛 Fix [#9](https://github.com/inflation/jpegxl-rs/issues/9)
- 🐛 Fix potential use-after-free

### Miscellaneous

- 📝 Update docs

<a name="0.3.7"></a>

## 0.3.7 (2021-04-13)

### Changed

- ⬆️ Bump to v0.3.7

### Miscellaneous

- 📝 Update docs

<a name="0.3.5"></a>

## 0.3.5 (2021-03-25)

### Added

- ✨ Check signature first

### Changed

- ⬆️ Upgrade `libjxl` to v0.3.5

<a name="0.3.3"></a>

## 0.3.3 (2021-03-13)

### Added

- ✨ Store JPEG reconstruction metadata
- ✨ Output ICC profile
- ✨ Allow reuse of parallel runner and memory manager

### Changed

- 🎨 Rename feature `without-build` to `system-jpegxl`
- ⬆️ Bump `libjxl` version
- 🎨 Move generic on `JxlDecoder` to decode()

<a name="0.3.2"></a>

## 0.3.2 (2021-02-16)

### Added

- ✨ Add color encoding option

### Changed

- ⬆️ Update `jpeg-xl` to 0.3.1

<a name="0.3.0"></a>

## 0.3.0 (2021-01-30)

### Miscellaneous

- Add API to encode from raw JPEG data lossless
- Update `libjxl` to v0.3

<a name="0.2.3"></a>

## 0.2.3 (2021-01-15)

### Miscellaneous

- Update dependency

<a name="0.2.2"></a>

## 0.2.2 (2021-01-10)

### Miscellaneous

- Add a simple thread pool
- Add encoder building options
- Add Encoder
- Add decoder builder for better API
- Add more `image` crate support
- Add benchmarks

<a name="0.1.4"></a>

## 0.1.4 (2020-08-25)

### Miscellaneous

- Add memory manager

<a name="0.1.2"></a>

## 0.1.2 (2020-08-19)

### Miscellaneous

- Add multithreading runner
- Add GPL-3.0 license and notices

<a name="0.1.0"></a>

## 0.1.0 (2020-08-16)

### Miscellaneous

- 🎉 Initial commit
