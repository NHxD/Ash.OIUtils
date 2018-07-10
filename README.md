[![Latest Release](https://img.shields.io/badge/version-1.1.0-brightgreen.svg)](releases/tag/v1.1.0) ![Console App Output](https://img.shields.io/badge/output-console_app-green.svg) ![.NET Framework](https://img.shields.io/badge/%2ENET_framework-4%2E5%2E2-green.svg) ![C# Language](https://img.shields.io/badge/language-C%23-yellow.svg) [![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

# Instructions

Drop `.3` archive files or directories onto the program window or icon and it'll extract the files within it to the designated output folder (by default: `out`).

The first entry in most archives is not a PNG file. Its contents and file format is unknown. But if you still wish to extract it, use the option:

> /exportData=true

Most of the entries are 1 by 1 pixel PNG's. They're likely unused assets, but if you still wish to extract them, use the option:

> /exportSinglePixelImage=true


# Known Issues

- Relative link operands, such as `./` and `../` are likely not supported.