A static build of ffmpeg (built with [https://github.com/stvs/ffmpeg-static](https://github.com/stvs/ffmpeg-static))

FFmpeg output:

    ffmpeg version 1.2-static Copyright (c) 2000-2013 the FFmpeg developers
      built on Jan 26 2014 09:28:15 with gcc 4.6 (Ubuntu/Linaro 4.6.3-1ubuntu5)
      configuration: --prefix=/home/andrean/dev/tools/ffmpeg-static/target --extra-cflags='-I/home/andrean/dev/tools/ffmpeg-static/target/include -static' --extra-ldflags='-L/home/andrean/dev/tools/ffmpeg-static/target/lib -lm -static' --extra-version=static --disable-debug --disable-shared --enable-static --extra-cflags=--static --disable-ffplay --disable-ffserver --disable-doc --enable-gpl --enable-pthreads --enable-postproc --enable-gray --enable-runtime-cpudetect --enable-libfaac --enable-libmp3lame --enable-libtheora --enable-libvorbis --enable-libx264 --enable-libxvid --enable-bzlib --enable-zlib --enable-nonfree --enable-version3 --enable-libvpx --disable-devices
      libavutil      52. 18.100 / 52. 18.100
      libavcodec     54. 92.100 / 54. 92.100
      libavformat    54. 63.104 / 54. 63.104
      libavdevice    54.  3.103 / 54.  3.103
      libavfilter     3. 42.103 /  3. 42.103
      libswscale      2.  2.100 /  2.  2.100
      libswresample   0. 17.102 /  0. 17.102
      libpostproc    52.  2.100 / 52.  2.100
    Hyper fast Audio and Video encoder


Built for internal use by this custom [buildpack](https://github.com/integricho/heroku-buildpack-python-ffmpeg).
