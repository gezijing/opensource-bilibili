package(default_visibility = ["//visibility:public"])

load(
    "@io_bazel_rules_go//go:def.bzl",
    "go_library",
    "go_test",
)

filegroup(
    name = "package-srcs",
    srcs = glob(["**"]),
    tags = ["automanaged"],
    visibility = ["//visibility:private"],
)

filegroup(
    name = "all-srcs",
    srcs = [
        ":package-srcs",
        "//app/admin/main/point/cmd:all-srcs",
        "//app/admin/main/point/conf:all-srcs",
        "//app/admin/main/point/dao:all-srcs",
        "//app/admin/main/point/http:all-srcs",
        "//app/admin/main/point/model:all-srcs",
        "//app/admin/main/point/service:all-srcs",
    ],
    tags = ["automanaged"],
    visibility = ["//visibility:public"],
)
