# VulkanGPUDetectionAddon

This addon provides Vulkan libraries in a jar-in-jar format for cross-platform GPU detection with their types. It enables warnings when playing on an integrated GPU while a dedicated GPU is available.

The main Crash Assistant mod includes light weight DirectX-based detection for modern Windows, but this addon adds support for:
- Very old Windows versions
- Linux/MacOS platforms

This library was separated from the main mod to reduce its size (~5 MB), addressing concerns from some modpack creators.

This addon has no standalone functionality - it simply provides Vulkan libraries for the Crash Assistant mod.
