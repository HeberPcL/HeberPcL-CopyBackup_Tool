# CopyBackup_Tool


-- Package Required

Ionic.Zip

Newtonsoft.Json



-- Example Config
[
  {
    "Title": "Front",
    "Enable": "true",
    "SourcePath": "C:\\\\\\CopyBackup_Tool\\\\TESTE\\\\Pasta1",
    "DestinationPath": "C:\\CopyBackup_Tool\\TESTE\\Pasta2",
    "Ignore": {
      "Folders": [
        "folder1",
        "folder2",
        "folder3",
        "Inside"
      ],
      "Files": [
        "folder4/abc.txt",
        "folder4/xzd.dll"
      ]
    },
    "Backup": {
      "Enable": "true",
      "SourcePath": "C:\\CopyBackup_Tool\\TESTE\\Pasta1",
      "MoveToPath": "C:\\CopyBackup_Tool\\TESTE"
    }
  }
]