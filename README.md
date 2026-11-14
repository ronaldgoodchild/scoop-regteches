# scoop-regteches

Scoop bucket for the free REGTeches Windows tools.

```powershell
scoop bucket add regteches https://github.com/ronaldgoodchild/scoop-regteches
scoop install tech-sentinel-monitor   # or noc-dashboard, drivemapper-pro, rc
```

`rc` is REGTeches RC (Remote Connection Manager); its servers and logins are kept in `scoop\persistc`, so `scoop update rc` never touches them.

The EXEs are unsigned PyInstaller builds from the projects' GitHub Releases; Scoop verifies their SHA-256. MIT licensed.
