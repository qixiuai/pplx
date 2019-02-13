
package(
    default_visibility = ["//visibility:public"],
)

licenses(["notice"])

cc_library(
    name = "boost",
    hdrs = glob(["boost/**/*.hpp"]),
)

cc_import(
    name = "crypto",
    hdrs = glob(["openssl/openssl/*.h"]),
    shared_library = "openssl/libcrypto.so",
)

cc_import(
    name = "libssl",
    hdrs = glob(["openssl/openssl/*.h"]),
    shared_library = "openssl/libssl.so",
)
