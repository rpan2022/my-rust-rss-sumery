<!DOCTYPE html>

<html>
<head>
  <meta charset="UTF-8" />
  <title>RSS LOG FROM RUST</title>
</head>
<body>
  <div class="container">
    <h1>This is an H1 heading</h1>
    <h2>This is an H2 heading</h2>
    <p>Here are the key points from the two Rust articles:

1. **Rust Foundation Maintainers Fund (RFMF)**: A new fund has been launched to financially support Rust project maintainers. The RFC #3931 established a Funding team and a "Maintainer in Residence" program, which will fund existing maintainers to work full-time (or near full-time) on critical parts of Rust (compiler, std library, Cargo, Clippy, etc.). Donations from individuals and companies are accepted via GitHub Sponsors, with all proceeds directly supporting maintainers. The goal is stable, long-term funding to counter industry budget shifts.

2. **Rust 1.96.0**: The latest stable release includes:
   - New `core::range` types (`Range`, `RangeFrom`, `RangeInclusive`) that are `Copy` (unlike the legacy `Range` types which implement `Iterator`).
   - New `assert_matches!` and `debug_assert_matches!` macros for pattern-matching assertions.
   - WebAssembly targets now default to linking without `--allow-undefined`, making undefined symbols a link error (old behavior can be re-enabled).
   - Stabilized APIs: see the list above.
   - Two Cargo security advisories (CVE-2026-5223 and CVE-2026-5222) affecting third-party registries only; crates.io users are not impacted.
   - You can update via `rustup update stable`.</p>
  </div>
</body>
</html>

<style>
.container {
  background-color: #ffffff;
  text-align: center;
  padding: 16px;
  border-radius: 8px;
}

h1 {
  color: #ff6d5a;
  font-size: 24px;
  font-weight: bold;
  padding: 8px;
}

h2 {
  color: #909399;
  font-size: 18px;
  font-weight: bold;
  padding: 8px;
}
</style>

<script>
console.log("Hello World!");
</script>