load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "hash",
    srcs = ["hash.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/kubernetes/pkg/util/hash",
    importpath = "k8s.io/kubernetes/pkg/util/hash",
    visibility = ["//visibility:public"],
    deps = ["//vendor/github.com/davecgh/go-spew/spew"],
)
