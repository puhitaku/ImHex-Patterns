# ImHex-Patterns

Hex patterns, include patterns and magic files for the use with the ImHex Hex Editor

## Table of Contents

### Hex Patterns

| Name | MIME | Path | Description |
|------|------|------|-------------|
| BMP  | `image/bmp` | [`patterns/bmp.hexpat`](patterns/bmp.hexpat) | OS2/Windows Bitmap files |
| ELF  | `application/x-executable` | [`patterns/elf.hexpat`](patterns/elf.hexpat) | ELF header in elf binaries |
| PE   | `application/x-dosexec` | [`patterns/pe.hexpat`](patterns/pe.hexpat) | PE header, COFF header, Standard COFF fields and Windows Specific fields |
| NE   | | [`patterns/ne.hexpat`](patterns/ne.hexpat) | NE header and Standard NE fields |
| Intel HEX  | | [`patterns/intel_hex.hexpat`](patterns/intel_hex.hexpat) | [Intel hexadecimal object file format definition]("https://en.wikipedia.org/wiki/Intel_HEX") |
| MIDI | `audio/midi` | [`patterns/midi.hexpat`](patterns/midi.hexpat) | MIDI header, event fields provided |
| WAV  | `audio/wav`  | [`patterns/wav.hexpat`](patterns/wav.hexpat)  | RIFF header, WAVE header, PCM header |
| ZIP  | `application/zip` | [`patterns/zip.hexpat`](patterns/zip.hexpat) | End of Central Directory Header, Central Directory File Headers |
| PCAP | `application/vnd.tcpdump.pcap` | [`patterns/pcap.hexpat`](patterns/pcap.hexpat) | pcap header and packets | 
| SPIRV | | [`patterns/spirv.hexpat`](patterns/spirv.hexpat) | SPIR-V header and instructions | 
| AFE2 | | [`patterns/afe2.hexpat`](patterns/afe2.hexpat) | Nintendo Switch Atmosphère CFW Fatal Error log | 
| AR | `application/x-archive` | [`patterns/ar.hexpat`](patterns/ar.hexpat) | Static library archive files | 
| NACP | | [`patterns/nacp.hexpat`](patterns/nacp.hexpat) | Nintendo Switch NACP files | 
| NRO | | [`patterns/nro.hexpat`](patterns/nro.hexpat) | Nintendo Switch NRO files | 
| PRODINFO | | [`patterns/prodinfo.hexpat`](patterns/prodinfo.hexpat) | Nintendo Switch PRODINFO | 
| Java Class | `application/x-java-applet` | [`patterns/java_class.hexpat`](patterns/java_class.hexpat) | Java Class files | 
| ARM VTOR | | [`patterns/arm_cm_vtor.hexpat`](patterns/arm_cm_vtor.hexpat) | ARM Cortex M Vector Table Layout | 
| ICO | | [`patterns/ico.hexpat`](patterns/ico.hexpat) | Icon (.ico) or Cursor (.cur) files | 
| PNG  | `image/png` | [`patterns/png.hexpat`](patterns/png.hexpat) | PNG image files | 
| QOI  | `image/qoi` | [`patterns/qoi.hexpat`](patterns/qoi.hexpat) | QOI image files | 
| DDS | `image/vnd-ms.dds` | [`patterns/dds.hexpat`](patterns/dds.hexpat) | DirectDraw Surface |
| TGA | `image/tga` | [`patterns/tga.hexpat`](patterns/tga.hexpat) | Truevision TGA/TARGA image |
| ISO | | [`patterns/iso.hexpat`](patterns/iso.hexpat) | ISO 9660 file system |
| VDF | | [`patterns/vdf.hexpat`](patterns/vdf.hexpat) | Binary Value Data Format (.vdf) files | 
| IP | | [`patterns/ip.hexpat`](patterns/ip.hexpat) | Ethernet II Frames (IP Packets) | 
| UF2 | | [`patterns/uf2.hexpat`](patterns/uf2.hexpat) | [USB Flashing Format](https://github.com/microsoft/uf2) | 
| File System | | [`patterns/fs.hexpat`](patterns/fs.hexpat) | Drive File System | 
| Bencode | `application/x-bittorrent` | [`patterns/bencode.hexpat`](patterns/bencode.hexpat) | Bencode encoding, used by Torrent files | 
| Protobuf | | [`patterns/protobuf.hexpat`](patterns/protobuf.hexpat) | Google Protobuf encoding | 
| OGG | `audio/ogg` | [`patterns/ogg.hexpat`](patterns/ogg.hexpat) | OGG Audio format | 
| STL | `model/stl` | [`patterns/stl.hexpat`](patterns/stl.hexpat) | STL 3D Model format | 
| VHDX | | [`patterns/vhdx.hexpat`](patterns/vhdx.hexpat) | Microsoft Hyper-V Virtual Hard Disk format | 
| NTAG | | [`patterns/ntag.hexpat`](patterns/ntag.hexpat) | NTAG213/NTAG215/NTAG216, NFC Forum Type 2 Tag compliant IC | 
| Shell Link | `application/x-ms-shortcut` | [`patterns/lnk.hexpat`](patterns/lnk.hexpat) | Windows Shell Link file format | 
| Xilinx BIT | | [`patterns/xilinx_bit.hexpat`](patterns/xilinx_bit.hexpat) | Xilinx FPGA Bitstreams | 
| FLAC | `audio/flac` | [`patterns/flac.hexpat`](patterns/flac.hexpat) | Free Lossless Audio Codec, FLAC Audio Format | 
| BSON | `application/bson` | [`patterns/bson.hexpat`](patterns/bson.hexpat) | BSON (Binary JSON) format | 
| msgpack | `application/x-msgpack` | [`patterns/msgpack.hexpat`](patterns/msgpack.hexpat) | MessagePack binary serialization format | 
| MiniDump | `application/x-dmp` | [`patterns/minidump.hexpat`](patterns/minidump.hexpat) | Windows MiniDump files | 
| ID3 | `audio/mpeg` | [`patterns/id3.hexpat`](patterns/id3.hexpat) | ID3 tags in MP3 files |
| TAR | `application/x-tar` | [`patterns/tar.hexpat`](patterns/tar.hexpat) | Tar file format |
| CPIO | `application/x-cpio` | [`patterns/cpio.hexpat`](patterns/cpio.hexpat) | Old Binary CPIO Format |
| FDT | | [`patterns/fdt.hexpat`](patterns/fdt.hexpat) | Flat Linux Device Tree blob |
| StuffItV5 | `application/x-stuffit` | [`patterns/sit5.hexpat`](patterns/sit5.hexpat) | StuffIt V5 archive |
| NBT | | [`patterns/nbt.hexpat`](patterns/nbt.hexpat) | Minecraft NBT format |
| PCX | `application/x-pcx` | [`patterns/pcx.hexpat`](patterns/pcx.hexpat) | PCX Image format |
| GZIP | `application/gzip` | [`patterns/gzip.hexpat`](patterns/gzip.hexpat) | GZip compressed data format |
| PFS0 | | [`patterns/pfs0.hexpat`](patterns/pfs0.hexpat) | Nintendo Switch PFS0 archive (NSP files) |
| XCI | | [`patterns/xci.hexpat`](patterns/xci.hexpat) | Nintendo Switch XCI cardridge ROM |
| WAD | | [`patterns/wad.hexpat`](patterns/wad.hexpat) | DOOM WAD Archive |
| GIF | `image/gif` | [`patterns/gif.hexpat`](patterns/gif.hexpat) | GIF image files |
| ZSTD | `application/zstd` | [`patterns/zstd.hexpat`](patterns/zstd.hexpat) | Zstandard compressed data format |
| COFF | `application/x-coff` | [`patterns/coff.hexpat`](patterns/coff.hexpat) | Common Object File Format (COFF) executable |
| Mach-O | `application/x-mach-binary` | [`patterns/macho.hexpat`](patterns/macho.hexpat) | Mach-O executable |
| CHM | | [`patterns/chm.hexpat`](patterns/chm.hexpat) | Windows HtmlHelp Data (ITSF / CHM) |
| DMG | | [`patterns/dmg.hexpat`](patterns/dmg.hexpat) | Apple Disk Image Trailer (DMG) |
| XBEH | `audio/x-xbox-executable` | [`patterns/xbeh.hexpat`](patterns/xbeh.hexpat) | Xbox executable |
| QBCL | | [`patterns/qbcl.hexpat`](patterns/qbcl.hexpat) | Qubicle voxel scene project file |
| CCHVA | | [`patterns/cchva.hexpat`](patterns/cchva.hexpat) | Command and Conquer Voxel Animation |
| CCVXL | | [`patterns/ccvxl.hexpat`](patterns/ccvxl.hexpat) | Command and Conquer Voxel Model |
| CCPAL | | [`patterns/ccpal.hexpat`](patterns/ccpal.hexpat) | Command and Conquer Voxel Palette |
| PIF | `image/pif` | [`patterns/pif.hexpat`](patterns/pif.hexpat) | PIF Image Format |
| JPEG | `image/jpeg` | [`patterns/jpeg.hexpat`](patterns/jpeg.hexpat) | JPEG Image Format |
| DEX | | [`patterns/dex.hexpat`](patterns/dex.hexpat) | Dalvik EXecutable Format |

### Scripts

| Name | Path | Description |
|------|------|-------------|
| svd2pat | [`scripts/svd2pat.py`](scripts/svd2pat.py) | Converts a ARM .svd register MMIO definition file into a pattern |
| csv2tbl | [`scripts/csv2tbl.py`](scripts/csv2tbl.py) | Converts a 010 editor CSV encoding file into a table file |

### Pattern Libraries

| Name | Path | Description |
|------|------|-------------|
| libstd | [`includes/std/*`](includes/std) | Pattern Language Standard Libaray |
| libtype | [`includes/type/*`](includes/type) | Various custom types with special formatters |
| libhex | [`includes/hex/*`](includes/hex) | Functions to interact with ImHex |

### Yara rules

| Name | Path | Description |
|------|------|-------------|
| Official Rules | [`yara/official_rules/*`](yara/official_rules) | Official Yara rules repository |

### Magic files

| Name | Path | Description |
|------|------|-------------|
| Nintendo Switch | [`magic/nintendo_switch_magic`](magic/nintendo_switch_magic) | Identifies common file types used on the Nintendo Switch |
| Portable Executable | [`magic/portable_executable_magic`](magic/portable_executable_magic) | Identifies PE files used on Windows

### Constants files

| Name | Path | Description |
|------|------|-------------|
| CRC-16 | [`constants/crc16.json`](constants/crc16.json) | Constants associated with CRC-16 operations |
| CRC-32 | [`constants/crc32.json`](constants/crc32.json) | Constants associated with CRC-32 operations |
| HTTP-Codes | [`constants/http_status.json`](constants/http_status.json) | HTTP Status code values |
| Linux Error Codes | [`constants/linux_errors.json`](constants/linux_errors.json) | Values of Linux error results |

### Encoding files

| Name | Path | Description |
|------|------|-------------|
| Arabic ISO | [`encodings/arabic_iso.tbl`](encodings/arabic_iso.tbl) | Arabic ISO encoding |
| Arabic Windows | [`encodings/arabic_windows.tbl`](encodings/arabic_windows.tbl) | Arabic Windows encoding |
| ASCII | [`encodings/ascii.tbl`](encodings/ascii.tbl) | Regular ASCII encoding |
| ASCII+ANSI | [`encodings/ascii_ansi.tbl`](encodings/ascii_ansi.tbl) | Extended ASCII encoding |
| ASCII+OEM | [`encodings/ascii_oem.tbl`](encodings/ascii_oem.tbl) | ASCII encoding with Windows OEM characters |
| Baltic ISO | [`encodings/baltic_iso.tbl`](encodings/baltic_iso.tbl) | Baltic ISO encoding |
| Baltic Windows | [`encodings/baltic_windows.tbl`](encodings/baltic_windows.tbl) | Baltic Windows encoding |
| Cyrillic ISO | [`encodings/cyrillic_iso.tbl`](encodings/cyrillic_iso.tbl) | Cyrillic ISO encoding |
| Cyrillic Windows | [`encodings/cyrillic_windows.tbl`](encodings/cyrillic_windows.tbl) | Cyrillic Windows encoding |
| Cyrillic KOI8-R | [`encodings/cyrillic_koi8_r.tbl`](encodings/cyrillic_koi8_r.tbl) | Cyrillic KOI8-R encoding (Russian Characters) |
| Cyrillic KOI8-U | [`encodings/cyrillic_koi8_u.tbl`](encodings/cyrillic_koi8_u.tbl) | Cyrillic KOI8-U encoding (Ukranian Characters) |
| Eastern Europe ISO | [`encodings/eastern_europe_iso.tbl`](encodings/eastern_europe_iso.tbl) | Eastern Europe ISO encoding |
| Eastern Europe Windows | [`encodings/eastern_europe_windows.tbl`](encodings/eastern_europe_windows.tbl) | Eastern Europe Windows encoding |
| EBCDIC | [`encodings/ebcdic.tbl`](encodings/ebcdic.tbl) | Extended Binary Coded Decimal Interchange Code, developed by IBM for their Main Frames |
| EUC-JP | [`encodings/euc_jp.tbl`](encodings/euc_jp.tbl) | EUC-JP encoding with NEC special and IBM extended characters |
| EUC-KR | [`encodings/euc_kr.tbl`](encodings/euc_kr.tbl) | EUC-KR encoding |
| Greek ISO | [`encodings/greek_iso.tbl`](encodings/greek_iso.tbl) | Greek ISO encoding |
| Greek Windows | [`encodings/greek_windows.tbl`](encodings/greek_windows.tbl) | Greek Windows encoding |
| Hebrew ISO | [`encodings/hebrew_iso.tbl`](encodings/hebrew_iso.tbl) | Hebrew ISO encoding |
| Hebrew Windows | [`encodings/hebrew_windows.tbl`](encodings/hebrew_windows.tbl) | Hebrew Windows encoding |
| ISO/IEC 646 | [`encodings/iso_646.tbl`](encodings/iso_646.tbl) | ISO/IEC 646 encoding, an older version of ASCII |
| ISO/IEC 6937 | [`encodings/iso_6937.tbl`](encodings/iso_6937.tbl) | ISO/IEC 6937 encoding, an extension of ASCII containing additional character |
| JIS 0201 | [`encodings/jis_x_0201.tbl`](encodings/jis_x_0201.tbl) | JIS X 0201 encoding in UTF-8 |
| JIS X 0211 | [`encodings/jis_x_0211.tbl`](encodings/jis_x_0211.tbl) | JIS X 0211 encoding in UTF-8 |
| JIS 0213 | [`encodings/jis_x_0213.tbl`](encodings/jis_x_0213.tbl) | JIS X 0213 encoding in UTF-8 |
| Macintosh | [`encodings/macintosh.tbl`](encodings/macintosh.tbl) | Macintosh character encoding used by the Kermit protocol |
| Pokémon (English, Generation 1) | [`encodings/pokegen1_en.tbl`](encodings/pokegen1_en.tbl) | Character encoding used by the English generation 1 Pokémon games  |
| Shift-JIS UTF-8 | [`encodings/shiftjis.tbl`](encodings/shiftjis.tbl) | Shift-JIS encoding in UTF-8 |
| Thai | [`encodings/thai.tbl`](encodings/thai.tbl) | Thai character encoding |
| Turkish ISO | [`encodings/turkish_iso.tbl`](encodings/turkish_iso.tbl) | Turkish ISO encoding |
| Turkish Windows | [`encodings/turkish_windows.tbl`](encodings/turkish_windows.tbl) | Turkish Windows encoding |
| UTF-8 | [`encodings/utf8.tbl`](encodings/utf8.tbl) | UTF-8 encoding |
| Vietnamese | [`encodings/vietnamese.tbl`](encodings/vietnamese.tbl) | Vietnamese character encoding |

### Data Processor Nodes
| Name | Path | Description |
|------|------|-------------|
| Caesar Cipher | [`nodes/caesar.hexnode`](nodes/caesar.hexnode) | Simple adjustable per-byte Caecar Cipher (ROT) |
| XOR Cipher | [`nodes/xor.hexnode`](nodes/xor.hexnode) | XORs a input with a repeating XOR pad |

### Themes
| Name | Path | Description |
|------|------|-------------|
| Visual Studio Dark | [`themes/vs_dark.json`](themes/vs_dark.json) | Theme similar to Visual Studio's Dark theme |


## Contributing

If you want to contribute a file to the database, please make a PR which adds it to the right folder and adds a new entry to the table in this readme. 
To take advantage of the automatic pattern testing, please consider adding a test file named `<pattern_name>.hexpat.<extension>` to the `/tests/patterns/test_data` directory. Try to keep this file as small as possible so the repository doesn't become excessively large

Thanks a lot :)
