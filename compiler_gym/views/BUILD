# Copyright (c) Facebook, Inc. and its affiliates.
#
# This source code is licensed under the MIT license found in the
# LICENSE file in the root directory of this source tree.

py_library(
    name = "views",
    srcs = ["__init__.py"],
    visibility = ["//visibility:public"],
    deps = [
        ":observation",
        ":reward",
    ],
)

py_library(
    name = "observation",
    srcs = ["observation.py"],
    deps = [
        "//compiler_gym/service",
        "//compiler_gym/service/proto",
        "//compiler_gym/spaces",
    ],
)

py_library(
    name = "reward",
    srcs = ["reward.py"],
    visibility = ["//compiler_gym:__subpackages__"],
    deps = [
        "//compiler_gym/service",
        "//compiler_gym/service/proto",
    ],
)
