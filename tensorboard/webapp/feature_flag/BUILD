load("@npm_angular_bazel//:index.bzl", "ng_module")

package(default_visibility = ["//tensorboard:internal"])

ng_module(
    name = "feature_flag",
    srcs = [
        "feature_flag_module.ts",
    ],
    deps = [
        "//tensorboard/webapp/feature_flag/effects",
        "//tensorboard/webapp/feature_flag/store",
        "//tensorboard/webapp/feature_flag/store:types",
        "//tensorboard/webapp/webapp_data_source:feature_flag",
        "@npm//@angular/core",
        "@npm//@ngrx/effects",
        "@npm//@ngrx/store",
    ],
)

ng_module(
    name = "types",
    srcs = [
        "types.ts",
    ],
    deps = [
        "//tensorboard/webapp/webapp_data_source:feature_flag",
    ],
)
