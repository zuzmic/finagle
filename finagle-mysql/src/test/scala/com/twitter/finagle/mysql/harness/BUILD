scala_library(
    sources = [
        "*.scala",
    ],
    compiler_option_sets = ["fatal_warnings"],
    strict_deps = True,
    dependencies = [
        "3rdparty/jvm/org/scalatestplus:junit",
        "finagle/finagle-core/src/main",
        "finagle/finagle-mysql",
        "finagle/finagle-mysql/src/test/scala/com/twitter/finagle/mysql/harness/config",
        "util/util-core:util-core-util",
        "util/util-logging",
        "util/util-stats/src/main/scala/com/twitter/finagle/stats",
    ],
)
