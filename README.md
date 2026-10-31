# CleanRift Scoop bucket

Scoop bucket for [CleanRift](https://github.com/iseaprojects/cleanrift), an
open-source Windows uninstaller with quarantine and undo.

## Install

```powershell
scoop bucket add cleanrift https://github.com/iseaprojects/scoop-cleanrift
scoop install cleanrift
```

## Update

```powershell
scoop update
scoop update cleanrift
```

## Notes

- CleanRift asks for administrator rights when it starts.
- Settings, action history and quarantine data are stored in
  `%LOCALAPPDATA%\CleanRift`.
- This is a beta. See the main project for limitations.

The manifest is updated manually for each CleanRift release.
