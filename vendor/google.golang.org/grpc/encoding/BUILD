load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "encoding",
    srcs = [
        "encoding.go",
        "encoding_v2.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/google.golang.org/grpc/encoding",
    importpath = "google.golang.org/grpc/encoding",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/google.golang.org/grpc/internal/grpcutil",
        "//vendor/google.golang.org/grpc/mem",
    ],
)
