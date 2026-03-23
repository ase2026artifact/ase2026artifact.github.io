| Project     | Tool           | Vulnerability Type   | Status    | Crash Location          |
| ----------- | -------------- | -------------------- | --------- | ----------------------- |
| FlatBuffers | flatc          | Buffer Overflow      | Reported  | idl_parser.cpp          |
|             |                | Buffer Overflow      | Reported  | reflection.cpp          |
|             |                | Buffer Overflow      | Reported  | base.h                  |
|             |                | Buffer Overflow      | Reported  | flatc.cpp               |
|             |                | Buffer Overflow      | Reported  | idl_gen_java.cpp        |
|             |                | Buffer Overflow      | Reported  | base.h                  |
|             |                | Buffer Overflow      | Reported  | binary_annotator.h      |
|             |                | Buffer Overflow      | Reported  | binary_annotator.h      |
|             |                | Buffer Overflow      | Reported  | idl_gen_csharp.cpp      |
|             |                | Buffer Overflow      | Reported  | idl_gen_php.cpp         |
|             |                | Buffer Overflow      | Reported  | idl_gen_kotlin.cpp      |
|             |                | Buffer Overflow      | Reported  | idl_gen_go.cpp          |
|             |                | Null Ptr Dereference | Reported  | idl_parser.cpp          |
|             |                | Null Ptr Dereference | Reported  | binary_annotator.cpp    |
|             |                | Null Ptr Dereference | Reported  | idl.h                   |
|             |                | Null Ptr Dereference | Reported  | idl_gen_cpp.cpp         |
|             |                | Null Ptr Dereference | Reported  | bfbs_gen_nim.cpp        |
|             |                | Null Ptr Dereference | Reported  | idl_parser.cpp          |
|             |                | Null Ptr Dereference | Reported  | idl_gen_python.cpp      |
|             |                | Assertion Failure    | Reported  | idl_parser.cpp          |
|             |                | Assertion Failure    | Reported  | flatbuffer_builder.h    |
|             |                | Assertion Failure    | Reported  | idl_gen_cpp.cpp         |
|             |                | Assertion Failure    | Reported  | idl_gen_rust.cpp        |
|             |                | Assertion Failure    | Reported  | idl_gen_java.cpp        |
|             |                | Integer Overflow     | Reported  | idl_parser.cpp          |
|             |                | Integer Overflow     | Reported  | idl_parser.cpp          |
|             |                | Integer Overflow     | Reported  | vector_downward.h       |
|             |                | Type Confusion       | Reported  | idl_gen_rust.cpp        |
|             |                | Type Confusion       | Reported  | idl_gen_swift.cpp       |
|             |                | Type Confusion       | Reported  | idl_gen_go.cpp          |
|             |                | Division by Zero     | Fixed     | idl_parser.cpp          |
|             |                | Stack Overflow       | Fixed     | idl_parser.cpp          |
|             |                | UAF                  | Reported  | idl_parser.cpp, idl.h   |
| libsixel    | img2sixel      | Buffer Overflow      | Fixed     | fromgif.c               |
|             |                | Buffer Overflow      | Fixed     | fromgif.c               |
|             |                | Integer Overflow     | Fixed     | encoder.c               |
|             |                | Integer Overflow     | Fixed     | encoder.c               |
|             |                | Integer Overflow     | Fixed     | encoder.c               |
|             |                | Integer Overflow     | Fixed     | quant.c                 |
|             |                | Integer Overflow     | Fixed     | loader.c                |
|             |                | SEGV                 | Fixed     | loader.c                |
|             |                | SEGV                 | Fixed     | frompnm.c               |
|             | sixel2png      | Integer Overflow     | Fixed     | fromsixel.c             |
|             |                | Integer Overflow     | Fixed     | writer.c                |
| Bento4      | mp4dump        | Invalid Enum Load    | Reported  | Ap4MetaData.cpp         |
|             |                | Invalid Enum Load    | Reported  | Ap4MetaData.cpp         |
|             |                | Null Ptr Dereference | Reported  | Ap4DataBuffer.cpp       |
|             |                | Memory Leak          | Reported  | Mp4Dump.cpp             |
|             | mp4tag         | Invalid Enum Load    | Reported  | Ap4MetaData.cpp         |
|             | mp4split       | Invalid Enum Load    | Reported  | Ap4MetaData.cpp         |
|             | mp4pssh        | Type Confusion       | Reported  | Mp4Pssh.cpp             |
|             |                | Invalid Enum Load    | Reported  | Ap4MetaData.cpp         |
|             |                | Assertion Failure    | Reported  | Ap4Atom.cpp             |
|             | mp4decrypt     | Null Ptr Dereference | Reported  | Ap4Processor.cpp        |
|             |                | Null Ptr Dereference | Reported  | Ap4Processor.cpp        |
|             | mp4edit        | Null Ptr Dereference | Reported  | Ap4Processor.cpp        |
|             | mp4encrypt     | Null Ptr Dereference | Reported  | Ap4CommonEncryption.cpp |
|             |                | Null Ptr Dereference | Reported  | Ap4Array.h              |
|             | mp42aac        | Integer Overflow     | Reported  | Ap4SampleEntry.cpp      |
|             | mp4info        | Integer Overflow     | Reported  | Ap4Utils.cpp            |
|             | mp42hls        | Integer Overflow     | Reported  | Ap4Utils.cpp            |
|             |                | Integer Overflow     | Reported  | Mp42Hls.cpp             |
|             | mp4fragment    | Integer Overflow     | Reported  | Mp4Fragment.cpp         |
|             | mp4mux         | Integer Overflow     | Reported  | Ap4HevcParser.cpp       |
|             |                | Integer Overflow     | Reported  | Ap4HevcParser.cpp       |
|             |                | Integer Overflow     | Reported  | Ap4Utils.cpp            |
|             |                | Buffer Overflow      | Reported  | Ap4Utils.cpp            |
|             |                | Buffer Overflow      | Reported  | Ap4DataBuffer.cpp       |
|             |                | Null Ptr Dereference | Reported  | Ap4HevcParser.cpp       |
|             |                | Memory Leak          | Reported  | Mp4Mux.cpp              |
|             | mp42hevc       | Null Ptr Dereference | Reported  | Mp42Hevc.cpp            |
|             |                | Null Ptr Dereference | Reported  | Mp42Hevc.cpp            |
|             |                | Null Ptr Dereference | Reported  | Mp42Hevc.cpp            |
|             |                | Null Ptr Dereference | Reported  | Mp42Hevc.cpp            |
|             |                | Null Ptr Dereference | Reported  | Mp42Hevc.cpp            |
|             |                | Null Ptr Dereference | Reported  | Ap4DataBuffer.cpp       |
|             |                | Memory Leak          | Reported  | Mp42Hevc.cpp            |
|             | mp42ts         | Null Ptr Dereference | Reported  | Ap4Mpeg2Ts.cpp          |
|             |                | Null Ptr Dereference | Reported  | Ap4Mpeg2Ts.cpp          |
|             |                | Null Ptr Dereference | Reported  | Ap4Mpeg2Ts.cpp          |
| GPAC        | gpac           | Buffer Overflow      | Fixed     | avilib.c                |
|             |                | Buffer Overflow      | Fixed     | load_text.c             |
|             |                | Buffer Overflow      | Fixed     | dmx_nhnt.c              |
|             |                | UAF                  | Fixed     | av_parsers.c            |
|             |                | Division by Zero     | Fixed     | uncv_config             |
|             | MP4Box         | Buffer Overflow      | Fixed     | loader_xmt.c            |
|             |                | Buffer Overflow      | Fixed     | box_code_base.c         |
|             |                | Buffer Overflow      | Fixed     | dmx_nhml.c              |
|             |                | Buffer Overflow      | Fixed     | mp4box.c                |
|             |                | Buffer Overflow      | Fixed     | mp4box.c                |
|             |                | Null Ptr Dereference | Fixed     | filter_props.c          |
|             |                | Null Ptr Dereference | Fixed     | dmx_nhml.c              |
|             |                | Null Ptr Dereference | Fixed     | mux_isom.c              |
|             |                | Memory Leak          | Reported  | avilib.c                |
| Exiv2       | exiv2          | Integer Overflow     | Confirmed | types.cpp               |
| FLAC        | flac           | Division by Zero     | Fixed     | encode.c                |
|             |                | Buffer Overflow      | Fixed     | analyze.c               |
| miniaudio   | audioconverter | Integer Overflow     | Fixed     | stb_vorbis.c            |
|             |                | Integer Overflow     | Confirmed | stb_vorbis.c            |
|             |                | Integer Overflow     | Confirmed | stb_vorbis.c            |
|             |                | Integer Overflow     | Confirmed | stb_vorbis.c            |
|             |                | Null Ptr Dereference | Confirmed | stb_vorbis.c            |
| FreeType    | ftrandom       | Buffer Overflow      | Fixed     | ttcolr.c                |
| libtiff     | tiffdump       | Misaligned Address   | Fixed     | tiffdump.c              |
|             | tiffcp         | Buffer Overflow      | Fixed     | tiffcp.c                |
|             | tiffsplit      | Buffer Overflow      | Fixed     | tiffsplit.c             |
| libheif     | heif-enc       | Integer Overflow     | Fixed     | pixelimage.cc           |
| libpng      | pngfix         | Integer Overflow     | Reported  | pngfix.c                |