PROG = 7zu.dll
DEF_FILE = ../../Archive/Archive2.def
CFLAGS = $(CFLAGS) -DNEED_7ZIP_GUID

COMMON_OBJS = \
  $O\CRC.obj \
  $O\CrcReg.obj \
  $O\IntToString.obj \
  $O\NewHandler.obj \
  $O\MyString.obj \
  $O\Sha256Reg.obj \
  $O\StringConvert.obj \
  $O\StringToInt.obj \
  $O\MyVector.obj \
  $O\Wildcard.obj \

WIN_OBJS = \
  $O\FileDir.obj \
  $O\FileFind.obj \
  $O\FileIO.obj \
  $O\FileName.obj \
  $O\PropVariant.obj \
  $O\Synchronization.obj \
  $O\System.obj \

7ZIP_COMMON_OBJS = \
  $O\CreateCoder.obj \
  $O\CWrappers.obj \
  $O\InBuffer.obj \
  $O\InOutTempBuffer.obj \
  $O\FilterCoder.obj \
  $O\LimitedStreams.obj \
  $O\MethodId.obj \
  $O\MethodProps.obj \
  $O\OutBuffer.obj \
  $O\ProgressUtils.obj \
  $O\PropId.obj \
  $O\StreamBinder.obj \
  $O\StreamObjects.obj \
  $O\StreamUtils.obj \
  $O\UniqBlocks.obj \
  $O\VirtThread.obj \

AR_OBJS = \
  $O\ArchiveExports.obj \
  $O\DllExports2.obj \

AR_COMMON_OBJS = \
  $O\CoderMixer2.obj \
  $O\HandlerOut.obj \
  $O\InStreamWithCRC.obj \
  $O\ItemNameUtils.obj \
  $O\OutStreamWithCRC.obj \
  $O\ParseProperties.obj \


7Z_OBJS = \
  $O\7zCompressionMode.obj \
  $O\7zDecode.obj \
  $O\7zEncode.obj \
  $O\7zExtract.obj \
  $O\7zFolderInStream.obj \
  $O\7zHandler.obj \
  $O\7zHandlerOut.obj \
  $O\7zHeader.obj \
  $O\7zIn.obj \
  $O\7zOut.obj \
  $O\7zProperties.obj \
  $O\7zSpecStream.obj \
  $O\7zUpdate.obj \
  $O\7zRegister.obj \


COMPRESS_OBJS = \
  $O\CodecExports.obj \
  $O\Bcj2Coder.obj \
  $O\Bcj2Register.obj \
  $O\BcjCoder.obj \
  $O\BcjRegister.obj \
  $O\BitlDecoder.obj \
  $O\BranchMisc.obj \
  $O\BranchRegister.obj \
  $O\ByteSwap.obj \
  $O\BZip2Crc.obj \
  $O\BZip2Encoder.obj \
  $O\BZip2Decoder.obj \
  $O\BZip2Register.obj \
  $O\CopyCoder.obj \
  $O\CopyRegister.obj \
  $O\DeflateEncoder.obj \
  $O\DeflateDecoder.obj \
  $O\DeflateRegister.obj \
  $O\DeltaFilter.obj \
  $O\Lzma2Decoder.obj \
  $O\Lzma2Encoder.obj \
  $O\Lzma2Register.obj \
  $O\LzmaDecoder.obj \
  $O\LzmaEncoder.obj \
  $O\LzmaRegister.obj \
  $O\LzOutWindow.obj \
  $O\PpmdDecoder.obj \
  $O\PpmdEncoder.obj \
  $O\PpmdRegister.obj \

CRYPTO_OBJS = \
  $O\7zAes.obj \
  $O\7zAesRegister.obj \
  $O\MyAes.obj \
  $O\MyAesReg.obj \
  $O\RandGen.obj \

C_OBJS = \
  $O\Alloc.obj \
  $O\Bcj2.obj \
  $O\Bcj2Enc.obj \
  $O\Bra.obj \
  $O\Bra86.obj \
  $O\BraIA64.obj \
  $O\BwtSort.obj \
  $O\CpuArch.obj \
  $O\Delta.obj \
  $O\HuffEnc.obj \
  $O\LzFind.obj \
  $O\LzFindMt.obj \
  $O\Lzma2Dec.obj \
  $O\Lzma2Enc.obj \
  $O\LzmaDec.obj \
  $O\LzmaEnc.obj \
  $O\MtCoder.obj \
  $O\Ppmd7.obj \
  $O\Ppmd7Dec.obj \
  $O\Ppmd7Enc.obj \
  $O\Sha256.obj \
  $O\Sort.obj \
  $O\Threads.obj \

!include "../../Aes.mak"
!include "../../Crc.mak"

COMPRESS_OBJS = $(COMPRESS_OBJS) \
  $O\Lz4Decoder.obj \
  $O\Lz4Encoder.obj \
  $O\Lz4Register.obj \
  $O\Lz5Decoder.obj \
  $O\Lz5Encoder.obj \
  $O\Lz5Register.obj \
  $O\ZstdDecoder.obj \
  $O\ZstdEncoder.obj \
  $O\ZstdRegister.obj \

LZ4_OBJS = \
  $O\lz4.obj \
  $O\lz4frame.obj \
  $O\lz4hc.obj \
  $O\lz4xxhash.obj \

LZ5_OBJS = \
  $O\lz5.obj \
  $O\lz5frame.obj \
  $O\lz5hc.obj \

ZSTD_OBJS = \
  $O\entropy_common.obj \
  $O\fse_decompress.obj \
  $O\huf_decompress.obj \
  $O\zstd_common.obj \
  $O\zstd_decompress.obj \
  $O\xxhash.obj \
  $O\fse_compress.obj \
  $O\huf_compress.obj \
  $O\zstd_compress.obj \
  $O\error_private.obj \

ZSTDMT_OBJS = \
  $O\threading.obj \
  $O\lz4mt_common.obj \
  $O\lz4mt_compress.obj \
  $O\lz4mt_decompress.obj \
  $O\lz5mt_common.obj \
  $O\lz5mt_compress.obj \
  $O\lz5mt_decompress.obj \
  $O\zstdmt_common.obj \
  $O\zstdmt_compress.obj \
  $O\zstdmt_decompress.obj \

!include "../../7zip.mak"
