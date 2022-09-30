# Graphics-DRM-KMS_Display_Linux

### Context: How to display things in the Linux world
 * Different solutions, provided by different subsystems:
 * FBDEV: Framebuffer Device
 * DRM/KMS: Direct Rendering Manager / Kernel Mode Setting
 * V4L2: Video For Linux 2
### How to choose one: it depends on your needs
 * Each subsytem provides its own set of features
 * Different levels of complexity
 * Different levels of activity
### DRM/KMS Components: CRTC (display timings)
 * HSYNC pulse is used to inform the display it should go to the
   next pixel line.
 * VSYNC pulse is used to inform the display it should start to
   display a new frame and thus go back to the first line.
 * CRTC = CRT controller (Cathod Ray Tube Controller)
   legacy name of Display controller controller 
## Ref
  * https://wiki.st.com/stm32mpu/wiki/DRM_KMS_overview
  * https://dri.freedesktop.org/docs/drm/gpu/introduction.html
  * http://moi.vonos.net/linux/drm-and-kms/ (KMS/DRM conept)
  * http://moi.vonos.net/linux/graphics-card-interfaces/
  * http://landley.net/kdocs/htmldocs/drm.html
  * http://moi.vonos.net/linux/graphics-stack/
