load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "trace",
    srcs = [
        "events.go",
        "histogram.go",
        "trace.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/golang.org/x/net/trace",
    importpath = "golang.org/x/net/trace",
    visibility = ["//visibility:public"],
    deps = ["//vendor/golang.org/x/net/internal/timeseries"],
)
