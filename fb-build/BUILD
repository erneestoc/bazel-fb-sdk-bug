load(
    "@build_bazel_rules_apple//apple:apple.bzl",
    "apple_static_xcframework_import"
)

apple_static_xcframework_import(
    name = "FBSDKLoginKit",
    xcframework_imports = glob(
        ["FBSDKLoginKit.xcframework/**"]
    ),
    visibility = ["//visibility:public"]
)
