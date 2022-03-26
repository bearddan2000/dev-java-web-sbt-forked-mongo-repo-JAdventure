load("@rules_java//java:defs.bzl", "java_binary")

java_binary (
    name = "BazelApp",
    main_class = "example.Main",
    srcs = glob(["java/**/*.java"]),
    deps = [
      "@maven//:org_springframework_spring_core",
      "@maven//:org_springframework_boot_spring_boot",
      "@maven//:org_projectlombok_lombok",
      "@maven//:org_springframework_boot_spring_boot_starter_web",
      "@maven//:org_springframework_boot_spring_boot_starter_data_mongodb"
    ],
    resources = ["//src/main/resources:app"],
)
