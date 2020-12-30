FFmpeg Unmerged Patches
========================
Intel upstream patches queue for ffmpeg

ffmpeg mainline codebase
commit: 686c07fb1e0455c4205eaad18e8a01bf64058dec

How to use the Unmerged Patches:
1), How to update patches
    Please put patch set (*.patch) in your ffmpeg mainline folder.

2), How to submit pull request
    Please submit pull request for this repo (https://github.com/intel-media-ci/intel-ffmpeg-patch).

3), How to apply patches
    $ git am *.patch
    or
    $ for i in *.patch; do patch -p1 < $i; done

Supported Platforms:
  BDW (Broadwell)
  SKL (Skylake)
  BXT (Broxton) / APL (Apollo Lake)
  KBLx (KBL/Kaby Lake; CFL/Coffe Lake; WHL/Whiskey Lake; CML/Comet Lake; AML/Amber Lake)
  ICL (Ice Lake)
  JSL (Jasper Lake)/EHL (Elkhart Lake)
  TGL (Tiger Lake)
  RKL (Rocket Lake)
  DG1/SG1

Supported Features:
  Decode: AVC/H264, HEVC/H265 (8/10/12bit), AV1 (8/10bit), VP9 (8, 10, 12bit), VP8, JPEG/MJPEG, MPEG2, VC1
  Encode: AVC/H264, HEVC/H265 (8/10bit), VP9 (8/10bitt), VP8, JPEG/MJPEG, MPEG2
  VPP   : brightness/contrast/saturation/hue, csc, deinterlace, denoise, scale, sharpen, mirroring, rotation, transpose

Please contact focus.luo@intel.com or ullysses.a.eoff@intel.com or haihao.xiang@intel.com or guangxin.xu@intel.com, if you have any question.
