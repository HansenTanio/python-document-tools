# Document Inventory Tool

Scan a folder and exports a CSV report of all files in folder.

## Problem

Tracking documents in large folders by hand is not eficient, so this tool automates the inventory

## Features

- Scans a folder (including subfolders)
- Exports a CSV: file name, type, size, modified date
- (Planned) Flags duplicate file names
- (Planned) Counts files by type

## Setup

- Python 3.12+
- `git clone https://github.com/HansenTanio/python-document-tools.git`

## Usage

```bash
python inventory.py "C:/path/to/folder"
```

## Example output

| file_name  | type | size_kb | modified   |
| ---------- | ---- | ------- | ---------- |
| report.pdf | .pdf | 120     | 2026-11-01 |

## Roadmap

- [ ] Duplicate detection
- [ ] Summary by file type

## Author

Hansen
