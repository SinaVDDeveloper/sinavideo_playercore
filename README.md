# sinavideo_playercore
播放器内核部分
##功能部分：
###提供类似于Google播放器三件套类似的接口【不完全兼容】
###支持软硬解
###支持hls直播
###支持m3u8点播方式拖动


##特性：
###按需解压，内核压缩包4M内，运行时按照cpu类型进行自动选择
###支持全量android CPU，包含：armv6 armv7 armv7s vfp neon mips x86 【暂时不支持64位】
###使用MediaCodec实现硬解码，避免openmax的兼容性问题
###可以支持高通、MTK、Atom等主流SoC的硬解码方案

