package(default_visibility = ["//visibility:public"])

load("@io_bazel_rules_rust//rust:rust.bzl", "rust_library")

rust_library(
    name = "atta",
    edition = "2018",
    crate_type = "lib",
    srcs = [
        "lib.rs"
    ],
    deps = [
        "//cargo:serde",
    ],
)

