# Copyright 2019 The MediaPipe Authors.
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#      http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.

licenses(["notice"])  # LGPL

exports_files(["LICENSE"])

cc_library(
    name = "libffmpeg",
    # hdrs = glob([
    #     "/usr/include/x86_64-linux-gnu/libavcodec/**/*.h",
    #     "/usr/include/x86_64-linux-gnu/libavformat/**/*.h",
    #     "/usr/include/x86_64-linux-gnu/libavutil/**/*.h",
    # ]),
    # includes = [
    #     "/usr/lib/x86_64-linux-gnu",
    # ]
    linkopts = [
        "-l:libavcodec.so",
        "-l:libavformat.so",
        "-l:libavutil.so",
    ],
    visibility = ["//visibility:public"],
)
