load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "core",
    srcs = [
        "componentstatus.go",
        "configmap.go",
        "endpoints.go",
        "event.go",
        "expansion_generated.go",
        "limitrange.go",
        "namespace.go",
        "node.go",
        "persistentvolume.go",
        "persistentvolumeclaim.go",
        "pod.go",
        "podtemplate.go",
        "replicationcontroller.go",
        "replicationcontroller_expansion.go",
        "resourcequota.go",
        "secret.go",
        "service.go",
        "serviceaccount.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/listers/core/v1",
    importpath = "k8s.io/client-go/listers/core/v1",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/api/core/v1:core",
        "//vendor/k8s.io/apimachinery/pkg/labels",
        "//vendor/k8s.io/client-go/listers",
        "//vendor/k8s.io/client-go/tools/cache",
    ],
)
