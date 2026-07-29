# Sparkey Scoop Bucket

[Scoop](https://scoop.sh) bucket for the **Sparkey Lens** CLI (Windows).

## Install

```powershell
scoop bucket add sparkey https://github.com/Sparkey-AI/scoop-bucket
scoop install sparkey
```

Then enroll your machine:

```powershell
sparkey enroll <token>
```

## Alternative install (no Scoop)

```powershell
irm https://install.sparkey.ai/install.ps1 | iex
```

Manifests are updated automatically by the release pipeline; binaries are
served from the public mirror at `install.sparkey.ai` with SHA256 verification.
