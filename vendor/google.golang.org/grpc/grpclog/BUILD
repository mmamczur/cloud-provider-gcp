load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "grpclog",
    srcs = [
        "component.go",
        "grpclog.go",
        "logger.go",
        "loggerv2.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/google.golang.org/grpc/grpclog",
    importpath = "google.golang.org/grpc/grpclog",
    visibility = ["//visibility:public"],
    deps = ["//vendor/google.golang.org/grpc/grpclog/internal"],
)
