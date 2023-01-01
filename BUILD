load("@io_bazel_rules_closure//closure:defs.bzl", "closure_js_binary", "closure_js_library")

closure_js_binary(
    name = "eventcontract_bin",
    deps = [
        ":eventcontract",
    ],
    entry_points = [
        "jsaction.eventContractAuto",
    ],
)

closure_js_library(
    name = "eventcontract",
    srcs = [
        "eventcontract.js",
        "eventcontract_auto.js",
        "event.js",
        "cache.js",
        "jsaction.js",
        "replay.js",
        "generator.js",
        "syntax.js",
        "dom.js",
        "customeventdetail.js",
    ],
    deps = [
        "@com_google_javascript_closure_library//closure/goog/dom:dom",
        "@com_google_javascript_closure_library//closure/goog/dom:tagname",
        "@com_google_javascript_closure_library//closure/goog/functions:functions",
        "@com_google_javascript_closure_library//closure/goog/asserts:asserts",
    ],
    suppress = [
        "useOfGoogProvide",
        "reportUnknownTypes",
    ],
)
