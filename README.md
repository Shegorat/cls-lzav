# cls-lzav - FreeArc compression filter. 
cls-lzav is implementation of LZAV algorithm as FreeArc compression filter. 
This filter is based on LZAV v.5.8 sources https://github.com/avaneev/lzav

LZAV is a fast general-purpose in-memory data compression algorithm based on now-classic LZ77 lossless data compression method. LZAV holds a good position on the Pareto landscape of factors, among many similar in-memory (non-streaming) compression algorithms.

### Options:
| Name | Description |
| ------ | ------ |
| b=<block_size> | Size of compression block (default 4mb) |
| mode=<mode> | Compression mode [default, high] |

### Usage:
```bash
	arc.exe a -ep1 -dses --dirs -s; -r -m=lzav:b=128m data.arc "packeddata\*"
```

---

## Support the Project

[![Support on Patreon](https://c5.patreon.com/external/logo/become_a_patron_button.png)](https://www.patreon.com/Shegorat)

If you find this project useful, consider supporting development on Patreon.
