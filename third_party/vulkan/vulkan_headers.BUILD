load("@rules_cc//cc:defs.bzl", "cc_library")

VULKAN_HDRS = [
    "include/vulkan/vk_platform.h",
    "include/vulkan/vk_sdk_platform.h",
    "include/vulkan/vulkan.h",
    "include/vulkan/vulkan_core.h",
]

VULKAN_TEXTUAL_HDRS = [
    "include/vulkan/vulkan_android.h",
    "include/vulkan/vulkan_fuchsia.h",
    "include/vulkan/vulkan_ggp.h",
    "include/vulkan/vulkan_ios.h",
    "include/vulkan/vulkan_macos.h",
    "include/vulkan/vulkan_metal.h",
    "include/vulkan/vulkan_vi.h",
    "include/vulkan/vulkan_wayland.h",
    "include/vulkan/vulkan_win32.h",
    "include/vulkan/vulkan_xcb.h",
    "include/vulkan/vulkan_xlib.h",
    "include/vulkan/vulkan_xlib_xrandr.h",
]

cc_library(
    name = "vulkan_headers",
    hdrs = VULKAN_HDRS,
    includes = ["include"],
    textual_hdrs = VULKAN_TEXTUAL_HDRS,
    visibility = ["//visibility:public"],
)
