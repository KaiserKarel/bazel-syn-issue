"""
cargo-raze crate build file.

DO NOT EDIT! Replaced on runs of cargo-raze
"""
package(default_visibility = [
  # Public for visibility by "@raze__crate__version//" targets.
  #
  # Prefer access through "//cargo", which limits external
  # visibility to explicit Cargo.toml dependencies.
  "//visibility:public",
])

licenses([
  "restricted", # "MIT OR Apache-2.0"
])

load(
    "@io_bazel_rules_rust//rust:rust.bzl",
    "rust_library",
    "rust_binary",
    "rust_test",
)


# Unsupported target "build-script-build" with type "custom-build" omitted
# Unsupported target "file" with type "bench" omitted
# Unsupported target "rust" with type "bench" omitted

rust_library(
    name = "syn",
    crate_root = "src/lib.rs",
    crate_type = "lib",
    edition = "2018",
    srcs = glob(["**/*.rs"]),
    deps = [
        "//cargo/vendor/proc-macro2-1.0.9:proc_macro2",
        "//cargo/vendor/quote-1.0.2:quote",
        "//cargo/vendor/unicode-xid-0.2.0:unicode_xid",
    ],
    rustc_flags = [
        "--cap-lints=allow",
    ],
    version = "1.0.16",
    crate_features = [
        "clone-impls",
        "default",
        "derive",
        "parsing",
        "printing",
        "proc-macro",
        "quote",
        "visit",
    ],
)

# Unsupported target "test_asyncness" with type "test" omitted
# Unsupported target "test_attribute" with type "test" omitted
# Unsupported target "test_derive_input" with type "test" omitted
# Unsupported target "test_expr" with type "test" omitted
# Unsupported target "test_generics" with type "test" omitted
# Unsupported target "test_grouping" with type "test" omitted
# Unsupported target "test_ident" with type "test" omitted
# Unsupported target "test_iterators" with type "test" omitted
# Unsupported target "test_lit" with type "test" omitted
# Unsupported target "test_meta" with type "test" omitted
# Unsupported target "test_parse_buffer" with type "test" omitted
# Unsupported target "test_pat" with type "test" omitted
# Unsupported target "test_precedence" with type "test" omitted
# Unsupported target "test_receiver" with type "test" omitted
# Unsupported target "test_round_trip" with type "test" omitted
# Unsupported target "test_should_parse" with type "test" omitted
# Unsupported target "test_size" with type "test" omitted
# Unsupported target "test_stmt" with type "test" omitted
# Unsupported target "test_token_trees" with type "test" omitted
# Unsupported target "test_visibility" with type "test" omitted
# Unsupported target "zzz_stable" with type "test" omitted
