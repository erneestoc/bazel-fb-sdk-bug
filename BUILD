load(
    "@rules_swift//swift:swift.bzl",
    "swift_library"
)

swift_library(
    name = "FbExample",
    deps = ["@facebook-ios-sdk//:FBSDKLoginKit"],
    srcs = glob([
        "Sources/**/*.swift"
    ]),
    linkstatic = True,
    visibility = ["//visibility:public"],
)
