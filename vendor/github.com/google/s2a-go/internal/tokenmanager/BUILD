load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "tokenmanager",
    srcs = ["tokenmanager.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/github.com/google/s2a-go/internal/tokenmanager",
    importpath = "github.com/google/s2a-go/internal/tokenmanager",
    visibility = ["//vendor/github.com/google/s2a-go:__subpackages__"],
    deps = [
        "//vendor/github.com/google/s2a-go/internal/proto/common_go_proto",
        "//vendor/github.com/google/s2a-go/internal/proto/v2/common_go_proto",
    ],
)
