load("//:rules.bzl", "runai_cc_auto_library", "runai_cc_test")

runai_cc_auto_library(
    name = "fdlimit",
    deps = [
        "//utils/logging",
    ],
)

runai_cc_test(
    name = "fdlimit_test",
    srcs = ["fdlimit_test.cc"],
    deps = [
        ":fdlimit",
        "//utils/random",
    ],
)
