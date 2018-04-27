# Metascan API

_____________________________________

## Getting Started

Following are instructions to get the program running

### Requirements:

Python 3.6

## Installation

```
pip install -r requirements.txt
```
## Example

```
python3 scan_file.py -f test.txt -k apikey
```

## Flags

Command | Detail
:-- | --:
-f, --file | Specify file to be scanned
-k, --key | Unique API token; required
-hash, --hash | specify hash function (md5, sha1, sha256)
-m, -meta | get metadata for scanned file
-n, --name | flag to preserve file name in scan
-p, --p | password for password protected files
-s, --share | allows file scans to be share or not
-w, --workflow | active workflows, allowed values: mcl-metadefender-rest-sanitize-disabled-unarchive



## Author

Donnell Muse
