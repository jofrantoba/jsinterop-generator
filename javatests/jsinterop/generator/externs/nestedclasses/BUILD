# Description:
#   Tests conversion of nested class
#

load(
    "//javatests/jsinterop/generator:jsinterop_generator_test.bzl",
    "jsinterop_generator_test",
)

package(
    default_visibility = ["//:__subpackages__"],
    # Apache2
    licenses = ["notice"],
)

jsinterop_generator_test(
    name = "nestedclasses",
    srcs = ["nestedclasses.js"],
    expected_output = [
        "Foo.java.txt",
        "foo/Bar.java.txt",
    ],
)
