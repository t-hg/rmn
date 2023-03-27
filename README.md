rmn - remove node

Example:
```
$ tree -a
.
└── folderA
    └── folderB
        ├── fileA
        ├── fileB
        ├── fileC
        └── folderC
            └── .fileD

4 directories, 4 files

$ rmn folderA/folderB/

$ tree -a
.
└── folderA
    ├── fileA
    ├── fileB
    ├── fileC
    └── folderC
        └── .fileD

3 directories, 4 files
```
