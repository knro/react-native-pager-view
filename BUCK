load("//ReactNative:DEFS", "rn_android_library", "react_native_dep", "react_native_target")

rn_android_library(
    name = "viewpager",
    srcs = glob(["**/*.java"]),
    provided_deps = [
        react_native_dep("third-party/android/support/v4:lib-support-v4"),
    ],
    required_for_source_only_abi = True,
    visibility = [
        "PUBLIC",
    ],
    deps = [
        react_native_dep("third-party/java/infer-annotations:infer-annotations"),
        react_native_dep("third-party/java/jsr-305:jsr-305"),
        react_native_target("java/com/facebook/react/bridge:bridge"),
        react_native_target("java/com/facebook/react/common:common"),
        react_native_target("java/com/facebook/react/module/annotations:annotations"),
        react_native_target("java/com/facebook/react/uimanager:uimanager"),
        react_native_target("java/com/facebook/react/uimanager/annotations:annotations"),
        react_native_target("java/com/facebook/react/views/scroll:scroll"),
    ],
)
