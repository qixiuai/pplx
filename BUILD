cc_library(
    name = "pplx",
    srcs = glob(["pplx/**/*.cpp", "pplx/**/*.h"]),
    hdrs = glob(["pplx/**/*.h"]),
    copts = ["-std=c++17"],
    linkopts = ["-lboost_system", "-lcrypto", "-lssl"],
)
