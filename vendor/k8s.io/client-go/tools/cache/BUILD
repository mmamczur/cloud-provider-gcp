load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "cache",
    srcs = [
        "controller.go",
        "delta_fifo.go",
        "doc.go",
        "expiration_cache.go",
        "expiration_cache_fakes.go",
        "fake_custom_store.go",
        "fifo.go",
        "heap.go",
        "index.go",
        "listers.go",
        "listwatch.go",
        "mutation_cache.go",
        "mutation_detector.go",
        "object-names.go",
        "reflector.go",
        "reflector_data_consistency_detector.go",
        "reflector_metrics.go",
        "retry_with_deadline.go",
        "shared_informer.go",
        "store.go",
        "thread_safe_store.go",
        "undelta_store.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/tools/cache",
    importpath = "k8s.io/client-go/tools/cache",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/apimachinery/pkg/api/errors",
        "//vendor/k8s.io/apimachinery/pkg/api/meta",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:meta",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1/unstructured",
        "//vendor/k8s.io/apimachinery/pkg/fields",
        "//vendor/k8s.io/apimachinery/pkg/labels",
        "//vendor/k8s.io/apimachinery/pkg/runtime",
        "//vendor/k8s.io/apimachinery/pkg/runtime/schema",
        "//vendor/k8s.io/apimachinery/pkg/types",
        "//vendor/k8s.io/apimachinery/pkg/util/cache",
        "//vendor/k8s.io/apimachinery/pkg/util/diff",
        "//vendor/k8s.io/apimachinery/pkg/util/naming",
        "//vendor/k8s.io/apimachinery/pkg/util/net",
        "//vendor/k8s.io/apimachinery/pkg/util/runtime",
        "//vendor/k8s.io/apimachinery/pkg/util/sets",
        "//vendor/k8s.io/apimachinery/pkg/util/wait",
        "//vendor/k8s.io/apimachinery/pkg/watch",
        "//vendor/k8s.io/client-go/features",
        "//vendor/k8s.io/client-go/rest",
        "//vendor/k8s.io/client-go/tools/cache/synctrack",
        "//vendor/k8s.io/client-go/tools/pager",
        "//vendor/k8s.io/client-go/util/consistencydetector",
        "//vendor/k8s.io/klog/v2:klog",
        "//vendor/k8s.io/utils/buffer",
        "//vendor/k8s.io/utils/clock",
        "//vendor/k8s.io/utils/pointer",
        "//vendor/k8s.io/utils/ptr",
        "//vendor/k8s.io/utils/trace",
    ],
)
