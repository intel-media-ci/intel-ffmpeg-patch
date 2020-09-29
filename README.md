FFmpeg Unmerged Patches
========================
Intel upstream patches queue for ffmpeg

ffmpeg mainline codebase
commit: 0919c6d507c2fe015fb165ae1880d75f16ec327c

How to use the Unmerged Patches:
1), How to update patches
    Please put patch set (*.patch) in your ffmpeg mainline folder.

2), How to submit pull request
    Please submit pull request for this repo (https://github.com/intel-media-ci/intel-ffmpeg-patch).

3), How to apply patches
    $ git am *.patch
    or
    $ for i in *.patch; do patch -p1 < $i; done

Please contact focus.luo@intel.com or ullysses.a.eoff@intel.com or haihao.xiang@intel.com or guangxin.xu@intel.com, if you have any questions.
