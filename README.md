### OpenGL intergrate with FFmpeg API

This is a useful tool generated when doing project Pixel Stream. We use read pixels api of OpenGL to read buffer, and use this buffer to generate h.264 video. This demo will updated when we upgrade the project pixel stream.

1. Build

   Please make sure you have **ffmpeg** installed first. So we recommended to use macOs or CentOS. Or if not borther you can use Windows to set up the environment variables. 

   ```sh
   mkdir cmake-build-debug
   cd cmake-build-debug
   cd cmake-build-debug
   cmake ..
   make -j9
   ```

2. Usage

   The main drawing program is in main, you can draw whatever you like. And just press WASD or move your mouse to move around. I use c++ api to count down 10 seconds. You can modify what ever you like. Multi-thread is not supported yet. Finally, an output.mp4 vedio will generate in your working directory.

3. Promotion

   - [ ] CUDA
   - [ ] Multi-Thread
   - [ ] Read frame(we use read pixels now.)



Any question you can contract me with songty404@gmail.com.