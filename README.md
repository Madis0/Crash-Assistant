# VulkanGPUDetectionAddon

This mod contains just Vulkan lib in a jar-in-jar format, required for cross-platform detection that shows a warning if Minecraft is
running on an integrated GPU while a dedicated GPU is available.

Currently, the core mod only has Windows-only DirectX GPU detection.

Vulkan-based GPU detection was split into a separate mod because the original implementation increased the mod size by ~5 MB, and some modpack creators were not happy
about this.

So we split the Vulkan lib into a separate mod and left the lightweight DirectX solution in the core mod.

The DirectX solution built into Crash Assistant 1.8.0+ will work perfectly on modern versions of Windows.

This addon is needed for the GPU detection feature to work on very old versions of Windows or Linux/MacOS platforms.

The mod does nothing on its own; it just provides the Vulkan lib for the Crash Assistant mod.
