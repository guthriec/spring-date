cc_library(
  name = "date",
  hdrs = [
    "include/date/date.h",
    #"include/date/tz.h",
    #"include/date/tz_private.h",
  ],
  #srcs = [
  #  "src/tz.cpp",
  #],
  strip_include_prefix = "include",
  copts = [
    "-fexceptions",
    "-pthread",
    "-DHAS_REMOTE_API=0",
  ],
  includes = ["."],
  visibility = ["//visibility:public"],
)
