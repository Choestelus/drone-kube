package(default_visibility = ["//visibility:public"])

licenses(["notice"])

load(
    "@io_bazel_rules_go//go:def.bzl",
    "go_library",
    "go_test",
)

go_library(
    name = "go_default_library",
    srcs = ["editor.go"],
    tags = ["automanaged"],
    deps = [
        "//pkg/util/term:go_default_library",
        "//vendor:github.com/golang/glog",
    ],
)

go_test(
    name = "go_default_test",
    srcs = ["editor_test.go"],
    library = "go_default_library",
    tags = ["automanaged"],
    deps = [],
)
