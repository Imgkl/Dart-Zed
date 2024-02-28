
<!-- BADGES_START -->
<!-- BUILD_FOR_ZED_START -->
<!-- BUILD_FOR_ZED_END -->
<!-- DOWNLOADS_BADGE_START -->
<!-- DOWNLOADS_BADGE_END -->
<!-- VERSION_BADGE_START -->
<!-- VERSION_BADGE_END -->
<!-- BADGES_END -->

![Build Status](https://img.shields.io/badge/Zed-8A2BE2?style=for-the-badge&label=Built%20For&color=e5c07b&labelColor=363a4f)

# Dart-zed
Syntax highlighting for Dart in [Zed](https://github.com/zed-industries/zed).

### Test locally

- Clone this repo: `git clone https://github.com/Imgkl/dart-zed dart`
- Clone the [tree-sitter-darrt](https://github.com/UserNobody14/tree-sitter-dart) repo: `https://github.com/UserNobody14/tree-sitter-dart`
- CD into the repo: `cd tree-sitter-dart`
- Build the WASM: `tree-sitter build-wasm` (might require docker-engine running)
- Rename the WASM file to `dart.wasm`
- Move the WASM file into `dart/grammars` (this repository)
- Move the `dart`repository to `~/Library/Application Support/Zed/extensions/installed`