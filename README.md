# hardware-monitoreo

This repository contains a small hardware monitoring utility extracted from the current workspace.

Included files:

- `nvidia_monitor.ps1`: a PowerShell script that captures NVIDIA GPU status and retains log files.
- `graficas.py`: a Python script that reads NVIDIA log files, generates plots, and exports CSV data.

## Usage

1. Run `nvidia_monitor.ps1` on a Windows machine with NVIDIA drivers installed.
2. Use `graficas.py` to parse generated `03_nvidia_*.txt` logs and create charts.

## Notes

This repository was created from the current workspace using GitHub MCP.
