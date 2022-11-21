package(
    default_visibility = ["//src:__subpackages__"],
)

android_library(
    name = "greeter_activity",
    srcs = [
        "Greeter.java",
        "MainActivity.java",
    ],
    exports = [
        "@maven//:junit_junit",
        "@maven//:androidx_test_espresso_espresso_core",
    ],
    manifest = "AndroidManifest.xml",
    resource_files = glob(["res/**"]),
)


java_library(
    name = "java_test_deps",
    exports = [
        "@maven//:junit_junit",
        "@maven//:org_hamcrest_hamcrest_library",
    ],
)