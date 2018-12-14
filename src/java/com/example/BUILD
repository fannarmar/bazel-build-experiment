java_binary(
    name = "ProjectRunner",
    srcs = ["ProjectRunner.java"],
    main_class = "com.example.ProjectRunner",
    deps = [":greeter"],
)

java_library(
    name = "greeter",
    srcs = ["Greeting.java"],
    visibility = ["//src/java/com/example/cmdline:__pkg__"],
)