http_archive(
    name = "io_bazel_rules_go",
    strip_prefix = "rules_go-43d7595b0123b5f0cc35bd45c084582b3eb3198b",
    urls = [
        "https://github.com/bazelbuild/rules_go/archive/43d7595b0123b5f0cc35bd45c084582b3eb3198b.tar.gz",
    ],
)

load("@io_bazel_rules_go//go:def.bzl", "go_rules_dependencies", "go_register_toolchains")
go_rules_dependencies()
go_register_toolchains()
