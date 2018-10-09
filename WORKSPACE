http_archive(
    name = "io_bazel_rules_go",
    strip_prefix = "rules_go-436452edc29a2f1e0edc22d180fbb57c27e6d0af",
    urls = [
        "https://github.com/bazelbuild/rules_go/archive/436452edc29a2f1e0edc22d180fbb57c27e6d0af.tar.gz",
    ],
)

load("@io_bazel_rules_go//go:def.bzl", "go_rules_dependencies", "go_register_toolchains")
go_rules_dependencies()
go_register_toolchains()
