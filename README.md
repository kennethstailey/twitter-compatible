Example invocation:

[ksta@lakshmi twitter-compatible]$ ./twitter-compatible master-speaking-completely.avi 
dear friend, you forgot to try it like: twitter-compatible video-in video-out
[ksta@lakshmi twitter-compatible]$ ./twitter-compatible master-speaking-completely.avi master-speaking-completely.mp4
ffmpeg version n6.1.1 Copyright (c) 2000-2023 the FFmpeg developers
  built with gcc 13.2.1 (GCC) 20230801
  configuration: --prefix=/usr --disable-debug --disable-static --disable-stripping --enable-amf --enable-avisynth --enable-cuda-llvm --enable-lto --enable-fontconfig --enable-frei0r --enable-gmp --enable-gnutls --enable-gpl --enable-ladspa --enable-libaom --enable-libass --enable-libbluray --enable-libbs2b --enable-libdav1d --enable-libdrm --enable-libfreetype --enable-libfribidi --enable-libgsm --enable-libharfbuzz --enable-libiec61883 --enable-libjack --enable-libjxl --enable-libmodplug --enable-libmp3lame --enable-libopencore_amrnb --enable-libopencore_amrwb --enable-libopenjpeg --enable-libopenmpt --enable-libopus --enable-libplacebo --enable-libpulse --enable-librav1e --enable-librsvg --enable-librubberband --enable-libsnappy --enable-libsoxr --enable-libspeex --enable-libsrt --enable-libssh --enable-libsvtav1 --enable-libtheora --enable-libv4l2 --enable-libvidstab --enable-libvmaf --enable-libvorbis --enable-libvpl --enable-libvpx --enable-libwebp --enable-libx264 --enable-libx265 --enable-libxcb --enable-libxml2 --enable-libxvid --enable-libzimg --enable-nvdec --enable-nvenc --enable-opencl --enable-opengl --enable-shared --enable-vapoursynth --enable-version3 --enable-vulkan
  libavutil      58. 29.100 / 58. 29.100
  libavcodec     60. 31.102 / 60. 31.102
  libavformat    60. 16.100 / 60. 16.100
  libavdevice    60.  3.100 / 60.  3.100
  libavfilter     9. 12.100 /  9. 12.100
  libswscale      7.  5.100 /  7.  5.100
  libswresample   4. 12.100 /  4. 12.100
  libpostproc    57.  3.100 / 57.  3.100
[aist#0:1/pcm_s16le @ 0x5b3961cca900] Guessed Channel Layout: stereo
Input #0, avi, from 'master-speaking-completely.avi':
  Duration: 00:01:26.85, start: 0.000000, bitrate: 3637 kb/s
  Stream #0:0: Video: mpeg4 (Advanced Simple Profile) (XVID / 0x44495658), yuv420p, 720x480 [SAR 22:25 DAR 33:25], 2097 kb/s, 29.97 fps, 29.97 tbr, 29.97 tbn
  Stream #0:1: Audio: pcm_s16le ([1][0][0][0] / 0x0001), 48000 Hz, 2 channels, s16, 1536 kb/s
Stream mapping:
  Stream #0:0 -> #0:0 (mpeg4 (native) -> h264 (libx264))
  Stream #0:1 -> #0:1 (pcm_s16le (native) -> aac (native))
Press [q] to stop, [?] for help
[libx264 @ 0x5b3961cd8d00] using SAR=22/25
[libx264 @ 0x5b3961cd8d00] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2
[libx264 @ 0x5b3961cd8d00] profile High, level 3.0, 4:2:0, 8-bit
[libx264 @ 0x5b3961cd8d00] 264 - core 164 r3108 31e19f9 - H.264/MPEG-4 AVC codec - Copyleft 2003-2023 - http://www.videolan.org/x264.html - options: cabac=1 ref=5 deblock=1:0:0 analyse=0x3:0x113 me=hex subme=8 psy=1 psy_rd=1.00:0.00 mixed_ref=1 me_range=16 chroma_me=1 trellis=2 8x8dct=1 cqm=0 deadzone=21,11 fast_pskip=1 chroma_qp_offset=-2 threads=15 lookahead_threads=2 sliced_threads=0 nr=0 decimate=1 interlaced=0 bluray_compat=0 constrained_intra=0 bframes=3 b_pyramid=2 b_adapt=1 b_bias=0 direct=3 weightb=1 open_gop=0 weightp=2 keyint=250 keyint_min=25 scenecut=40 intra_refresh=0 rc_lookahead=50 rc=crf mbtree=1 crf=19.0 qcomp=0.60 qpmin=0 qpmax=69 qpstep=4 ip_ratio=1.40 aq=1:1.00
Output #0, mp4, to 'master-speaking-completely.mp4':
  Metadata:
    encoder         : Lavf60.16.100
  Stream #0:0: Video: h264 (avc1 / 0x31637661), yuv420p(progressive), 720x480 [SAR 22:25 DAR 33:25], q=2-31, 29.97 fps, 29999 tbn
    Metadata:
      encoder         : Lavc60.31.102 libx264
    Side data:
      cpb: bitrate max/min/avg: 0/0/0 buffer size: 0 vbv_delay: N/A
  Stream #0:1: Audio: aac (LC) (mp4a / 0x6134706D), 48000 Hz, stereo, fltp, 192 kb/s
    Metadata:
      encoder         : Lavc60.31.102 aac
[out#0/mp4 @ 0x5b3961ccb4c0] video:12164kB audio:2052kB subtitle:0kB other streams:0kB global headers:0kB muxing overhead: 0.661405%
frame= 2604 fps=203 q=-1.0 Lsize=   14310kB time=00:01:26.78 bitrate=1350.7kbits/s dup=1 drop=0 speed=6.78x    
[libx264 @ 0x5b3961cd8d00] frame I:28    Avg QP:15.81  size: 25498
[libx264 @ 0x5b3961cd8d00] frame P:825   Avg QP:18.50  size:  9746
[libx264 @ 0x5b3961cd8d00] frame B:1751  Avg QP:19.93  size:  2114
[libx264 @ 0x5b3961cd8d00] consecutive B-frames:  3.6% 19.5%  1.7% 75.1%
[libx264 @ 0x5b3961cd8d00] mb I  I16..4:  8.6% 89.7%  1.6%
[libx264 @ 0x5b3961cd8d00] mb P  I16..4:  0.6% 12.5%  0.1%  P16..4: 45.7% 19.1%  9.3%  0.0%  0.0%    skip:12.6%
[libx264 @ 0x5b3961cd8d00] mb B  I16..4:  0.0%  2.0%  0.0%  B16..8: 44.8%  2.7%  0.4%  direct: 1.9%  skip:48.2%  L0:44.0% L1:43.3% BI:12.7%
[libx264 @ 0x5b3961cd8d00] 8x8 transform intra:94.6% inter:80.3%
[libx264 @ 0x5b3961cd8d00] direct mvs  spatial:99.5% temporal:0.5%
[libx264 @ 0x5b3961cd8d00] coded y,uvDC,uvAC intra: 86.8% 56.2% 12.4% inter: 17.7% 17.8% 0.2%
[libx264 @ 0x5b3961cd8d00] i16 v,h,dc,p: 36% 17% 15% 32%
[libx264 @ 0x5b3961cd8d00] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 13% 12% 50%  4%  4%  4%  4%  4%  5%
[libx264 @ 0x5b3961cd8d00] i4 v,h,dc,ddl,ddr,vr,hd,vl,hu: 23% 19%  9%  8% 10%  9%  8%  7%  7%
[libx264 @ 0x5b3961cd8d00] i8c dc,h,v,p: 39% 31% 25%  4%
[libx264 @ 0x5b3961cd8d00] Weighted P-Frames: Y:8.6% UV:0.7%
[libx264 @ 0x5b3961cd8d00] ref P L0: 57.1% 14.6% 17.1%  5.8%  4.8%  0.6%
[libx264 @ 0x5b3961cd8d00] ref B L0: 86.3% 10.7%  2.5%  0.5%
[libx264 @ 0x5b3961cd8d00] ref B L1: 97.4%  2.6%
[libx264 @ 0x5b3961cd8d00] kb/s:1146.76
[aac @ 0x5b3961d3eb80] Qavg: 701.765
[ksta@lakshmi twitter-compatible]$ 
