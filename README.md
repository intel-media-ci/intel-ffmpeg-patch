FFmpeg Unmerged Patches
========================
Intel upstream patches queue for ffmpeg

ffmpeg mainline codebase
commit: 4106013523f46824d32fd5b469ea264fbdfdb591

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
