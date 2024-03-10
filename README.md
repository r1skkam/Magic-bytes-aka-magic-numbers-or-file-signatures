# Magic bytes aka magic numbers or file signatures

Magic bytes, also known as magic numbers or file signatures, are a sequence of bytes used to identify or classify the format or content of a file. They are often found at the beginning of files and are used by software to determine the file type without relying on file extensions. Here are some common magic bytes for various file types:

1. **JPEG/JFIF Image**: 0xFFD8FF
2. **PNG Image**: 0x89504E470D0A1A0A
3. **GIF Image**: 0x474946383961 (GIF89a) or 0x474946383761 (GIF87a)
4. **PDF Document**: 0x25504446 (PDF)
5. **ZIP Archive**: 0x504B0304 (PK)
6. **Microsoft Word Document**: 0xD0CF11E0A1B11AE1 (DOC)
7. **Microsoft Excel Spreadsheet**: 0xD0CF11E0A1B11AE1 (XLS)
8. **Microsoft PowerPoint Presentation**: 0xD0CF11E0A1B11AE1 (PPT)
9. **MP3 Audio**: 0xFFFB (MPEG-1 Layer 3) or 0x494433 (ID3 tag)
10. **MPEG Video**: 0x000001BA (MPEG Program Stream)
11. **AVI Video**: 0x52494646 (RIFF)
12. **Executable (PE) File**: 0x4D5A (MZ)
13. **ELF Executable**: 0x7F454C46 ('\x7FELF' in ASCII)
14. **GZIP Archive**: 0x1F8B08 (GZIP)
15. **TAR Archive**: 0x7573746172 (ustar) or 0x746172 (tar)
16. **BMP Image**: 0x424D (BM)
17. **FLV Video**: 0x464C56 (FLV)
18. **SQLite Database**: 0x53514C69746520666F726D6174203300 (SQLite 3.x)
19. **JPEG2000 Image**: 0x0000000C6A5020200D0A870A (JP2)

These are just a few examples of common magic bytes. Different file types have their own unique magic bytes. When developing software that handles various file types, it's important to use magic bytes to accurately identify and validate the files being processed.
