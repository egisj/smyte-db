licenses(["notice"])

cc_library(
    name = "storage",
    srcs = [
        "google/storage_api/bucket.cc",
        "google/storage_api/bucket_access_control.cc",
        "google/storage_api/bucket_access_controls.cc",
        "google/storage_api/buckets.cc",
        "google/storage_api/channel.cc",
        "google/storage_api/compose_request.cc",
        "google/storage_api/object.cc",
        "google/storage_api/object_access_control.cc",
        "google/storage_api/object_access_controls.cc",
        "google/storage_api/objects.cc",
        "google/storage_api/rewrite_response.cc",
        "google/storage_api/storage_service.cc",
    ],
    hdrs = [
        "google/storage_api/bucket.h",
        "google/storage_api/buckets.h",
        "google/storage_api/bucket_access_control.h",
        "google/storage_api/bucket_access_controls.h",
        "google/storage_api/channel.h",
        "google/storage_api/compose_request.h",
        "google/storage_api/object.h",
        "google/storage_api/objects.h",
        "google/storage_api/object_access_control.h",
        "google/storage_api/object_access_controls.h",
        "google/storage_api/rewrite_response.h",
        "google/storage_api/storage_service.h",
    ],
    deps = [
        "//external:googleapis_curl_http",
        "//external:googleapis_http",
        "//external:googleapis_internal",
        "//external:googleapis_jsoncpp",
        "//external:googleapis_oauth2",
    ],
    visibility = ["//visibility:public"],
)