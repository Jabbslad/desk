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

### Peek Into Desktop Archive

`desk peek` - list contents of latest archive

`desk peek <name>` - list contents of named archive

### Restore Desktop Archive

`desk restore` - restore latest archive to desktop

`desk restore <name>` - restore named archive to desktop

### Remove Archive

`desk rm <name>` - delete/remove named archive

## License

MIT License

Copyright (c) 2016 Jamie Atkinson

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
