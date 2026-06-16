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
    <p>Here is a summary of the two Rust-related articles in English:

1. **Rust Foundation Maintainers Fund (RFMF)** – The Rust Foundation launched a new fund to financially support Rust maintainers. The Funding team will manage donations and direct them via the new "Maintainer in Residence" program, which provides stable, long-term funding for critical Rust project work (compiler, std lib, Cargo, etc.). Individuals can donate via GitHub Sponsors; companies can also donate or contact the Foundation directly. The goal is to reduce dependency on volatile job market funding.

2. **Rust 1.96.0 released** – Key changes include:
   - New `core::range::Range`, `RangeFrom`, and `RangeInclusive` types that are `Copy` (unlike legacy ranges) and implement `IntoIterator` instead of `Iterator`.
   - New `assert_matches!` and `debug_assert_matches!` macros for pattern-matching assertions with better diagnostics (not in prelude; import from `core`/`std`).
   - WebAssembly targets now default to not passing `--allow-undefined`, making undefined symbols a linker error.
   - Stabilized APIs: `AssertUnwindSafe`, `LazyCell`, `LazyLock` conversions, and the new range types.
   - Two Cargo security fixes (CVE-2026-5223 and CVE-2026-5222) affecting third-party registries only; crates.io users not impacted.</p>
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