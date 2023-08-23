<h1 align="center"> REPLICA3 </h1>
<div align="center">
<!--  <img src="logo.png" alt="Example" width="300" height="150">  -->
  <p>
  <strong>
  TAME THE PYHIDRA
  </strong>
 </p>
</div>
<div align="center">
  <!-- Crates version -->
  <a >
    <img src="https://img.shields.io/badge/version-v1.0.0-green.svg"
  </a>
  <a >
    <img src="https://img.shields.io/badge/license-MIT-blue.svg"
  </a>
  <a >
    <img src="https://img.shields.io/badge/Features-11-red.svg"
  </a>
  </a>
</div>

## NOTIFICATION:

I converted the REPLICA script (https://github.com/reb311ion/replica) to work in the "Pyhdira" (Python3) environment. Thanks reb311ion! 

## Features:

- ⚡ Disassemble missed instructions - Define code that Ghidra's auto analysis missed
- ⚡ Detect and fix missed functions - Define functions that Ghidra's auto analysis missed
- ⚡ Fix 'undefinedN' datatypes - Enhance Disassembly and Decompilation by fixing 
        'undefinedN' DataTypes 
- ⚡ Set MSDN API info as comments - Integrate information about functions, arguments
        and return values into Ghidra's disassembly listing in the form of comments
- ⚡ Tag Functions based on API calls - rename functions that calls one or more APIs with
        the API name and API type family if available
- ⚡ Detect and mark wrapper functions - Rename wrapper functions with the wrapping
        level and wrapped function name 
- ⚡ Fix undefined data and strings - Defines ASCII strings that Ghidra's auto analysis 
        missed and Converts undefined bytes in the data segment into DWORDs/QWORDs 
- ⚡ Detect and label crypto constants - Searche and label constants known to be associated
        with cryptographic algorithm in the code
- ⚡ Detect and comment stack strings - Find and post-comment stack strings 
- ⚡ Rename Functions Based on string references - rename functions that references one
        or more strings with the function name followed by the string name.
- ⚡ Bookmark String Hints - Bookmark intersting strings (file extensions, browser agents, registry keys, etc..)

## Dependencies:
- [Ghidra](https://github.com/NationalSecurityAgency/ghidra)
- [Pyhidra](https://github.com/dod-cyber-crime-center/pyhidra)
- [Python3](https://www.python.org/downloads/)


## Installation:
## Install

1. Download and install [Ghidra](https://github.com/NationalSecurityAgency/ghidra/releases) to a desired location.

1. Set the `GHIDRA_INSTALL_DIR` environment variable to point to the directory where Ghidra is installed.

1. Install pyhidra.

```console
> pip install pyhidra
```
### Enabling the Ghidra User Interface Plugin

1. Run `pyhidraw` from a terminal of your choice.
2. Open the Code Browser Tool.
3. From the `File` toolbar menu, select `Configure...`.
4. From the menu in the image below select `configure` under `Experimental`.
5. Copy the repository files into any of `ghidra_scripts` directories and extract `db.7z`, directories can be found from `Window->Script Manager->Script Directories`
