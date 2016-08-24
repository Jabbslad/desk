# Desk

Tame your messy OS X desktop contents with ease using this wrapper for the excellent [ZBackup](https://github.com/zbackup/zbackup).

## Prerequisites

ZBackup - [https://github.com/zbackup/zbackup]()

## Installation

`wget https://raw.githubusercontent.com/Jabbslad/desk/master/desk && chmod +x desk`

## Usage

### Clear Desktop 

`desk clear` - archives desktop contents

`desk clear "archive screenshots"` - archives desktop contents with optional comment

### List Desktop Archives

`desk ls` - list desktop archives with comments

### Restore Desktop Archive

`desk restore` - restore latest archive to desktop

`desk restore <name>` - restore named archive to desktop

### Remove Archive

`desk rm <name>` - delete/remove named archive

## License

MIT
