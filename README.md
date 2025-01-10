# RBDoom3BFG on Flatpak

This project contains files to build [RBDoom3BFG](https://github.com/RobertBeckebans/RBDOOM-3-BFG) as a Flatpak app.

## Copy game files
Copy data files to folder `~/.var/app/io.github.RobertBeckebans.RBDoom3BFG/data/rbdoom3bfg/base`.

### This version (v1.5.1) doesn't work for me
Moving to Vulkan version gives me this error:

```
----- R_InitOpenGL -----
r_vidMode reset from 27 to 0.
Initializing Vulkan subsystem
Enabled Vulkan instance extensions:
    VK_EXT_debug_utils
    VK_KHR_xlib_surface
    VK_KHR_surface
    VK_KHR_get_physical_device_properties2
Enabled Vulkan layers:
Enabled Vulkan device extensions:
    VK_KHR_fragment_shading_rate
    VK_KHR_buffer_device_address
    VK_EXT_descriptor_indexing
    VK_KHR_maintenance1
    VK_KHR_synchronization2
    VK_KHR_swapchain
Unknown command 'vid_restart'
Sys_Error: Failed to create a Vulkan physical device, error code = VK_ERROR_FEATURE_NOT_PRESENT
```

But probably this issue is due to my poor Intel GPU.