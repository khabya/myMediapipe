# Copyright 2020 Lisandro Bravo.
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
#

licenses(["notice"])  # Apache 2.0

exports_files(["LICENSE"])

load("//mediapipe/framework/port:build_config.bzl", "mediapipe_cc_proto_library")

package(
    default_visibility = ["//visibility:private"],
    features = ["-layering_check"],
)

proto_library(
    name = "angles_proto",
    srcs = ["angles.proto"],
    visibility = ["//myMediapipe:__subpackages__"],
)

mediapipe_cc_proto_library(
    name = "angles_cc_proto",
    srcs = ["angles.proto"],
    visibility = ["//myMediapipe:__subpackages__"],
) 

proto_library(
    name = "mqtt_message_proto",
    srcs = ["mqtt_message.proto"],
    visibility = ["//myMediapipe:__subpackages__"],
)

mediapipe_cc_proto_library(
    name = "mqtt_message_cc_proto",
    srcs = ["mqtt_message.proto"],
    visibility = ["//myMediapipe:__subpackages__"],
) 