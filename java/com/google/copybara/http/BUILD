# Copyright 2023 Google LLC.
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

package(default_visibility = ["//visibility:public"])

java_library(
    name = "http",
    srcs = glob(["**/*.java"]),
    deps = [
        "//java/com/google/copybara:base",
        "//java/com/google/copybara/checks",
        "//java/com/google/copybara/config:base",
        "//java/com/google/copybara/credentials",
        "//java/com/google/copybara/exception",
        "//java/com/google/copybara/http/auth",
        "//java/com/google/copybara/http/endpoint",
        "//java/com/google/copybara/http/json",
        "//java/com/google/copybara/http/multipart",
        "//java/com/google/copybara/util/console",
        "//third_party:autovalue",
        "//third_party:google_http_client",
        "//third_party:guava",
        "//third_party:jsr305",
        "//third_party:starlark",
    ],
)
