# Scoop Bucket for proc

[![Tests](https://github.com/yazeed/scoop-bucket-proc/actions/workflows/ci.yml/badge.svg)](https://github.com/yazeed/scoop-bucket-proc/actions/workflows/ci.yml) [![Excavator](https://github.com/yazeed/scoop-bucket-proc/actions/workflows/excavator.yml/badge.svg)](https://github.com/yazeed/scoop-bucket-proc/actions/workflows/excavator.yml)

[Scoop](https://scoop.sh) bucket for [proc](https://github.com/yazeed/proc) - semantic CLI tool for process management.

## Installation

```powershell
scoop bucket add proc https://github.com/yazeed/scoop-bucket-proc
scoop install proc
```

## Update

```powershell
scoop update proc
```

## About proc

Semantic CLI tool for process management. Target by port, PID, name or path.

```bash
proc on :3000                   # what's on port 3000?
proc on :3000,:8080,node        # multi-target: ports + name
proc by node --in . --min-cpu 5 # node in cwd using >5% CPU
proc kill :3000,:8080,node -y   # kill mixed targets at once
```

Learn more at [github.com/yazeed/proc](https://github.com/yazeed/proc).
