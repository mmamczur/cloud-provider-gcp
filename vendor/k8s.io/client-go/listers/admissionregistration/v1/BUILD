load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "admissionregistration",
    srcs = [
        "expansion_generated.go",
        "mutatingwebhookconfiguration.go",
        "validatingadmissionpolicy.go",
        "validatingadmissionpolicybinding.go",
        "validatingwebhookconfiguration.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/listers/admissionregistration/v1",
    importpath = "k8s.io/client-go/listers/admissionregistration/v1",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/api/admissionregistration/v1:admissionregistration",
        "//vendor/k8s.io/apimachinery/pkg/labels",
        "//vendor/k8s.io/client-go/listers",
        "//vendor/k8s.io/client-go/tools/cache",
    ],
)
