java_binary(name = "scalac",
  main_class = "io.bazel.rulesscala.scalac.ScalaCInvoker",
  srcs = ["ScalaCInvoker.java", "CompileOptions.java"],

  deps = [
    "@scala//:lib/scala-library.jar",
    "@scala//:lib/scala-reflect.jar",
    "@scala//:lib/scala-compiler.jar",
    "@scala//:lib/scala-xml_2.12-1.0.6.jar",
    "//src/java/io/bazel/rulesscala/jar",
    "//src/java/com/google/devtools/build/lib:worker",
    "@scalac_rules_guava//jar",
  ],
  visibility = ["//visibility:public"],
)
