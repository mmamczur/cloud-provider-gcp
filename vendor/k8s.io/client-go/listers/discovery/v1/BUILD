load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "discovery",
    srcs = [
        "endpointslice.go",
        "expansion_generated.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/listers/discovery/v1",
    importpath = "k8s.io/client-go/listers/discovery/v1",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/api/discovery/v1:discovery",
        "//vendor/k8s.io/apimachinery/pkg/labels",
        "//vendor/k8s.io/client-go/listers",
        "//vendor/k8s.io/client-go/tools/cache",
    ],
)
