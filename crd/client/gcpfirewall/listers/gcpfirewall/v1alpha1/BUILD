load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "expansion_generated.go",
        "gcpfirewall.go",
    ],
    importpath = "k8s.io/cloud-provider-gcp/crd/client/gcpfirewall/listers/gcpfirewall/v1alpha1",
    visibility = ["//visibility:public"],
    deps = [
        "//crd/apis/gcpfirewall/v1alpha1:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/api/errors:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/labels:go_default_library",
        "//vendor/k8s.io/client-go/tools/cache:go_default_library",
    ],
)
