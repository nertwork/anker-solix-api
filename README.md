# Anker SOLIX System Export — A1782 (F3000) with Active Manual Backup Plan

This branch hosts the complete, anonymized mock dataset generated using `AnkerSolixApiExport` (`export.py`) from a live Anker SOLIX owner account with an A1782 (F3000) system.

## Download
- Direct ZIP download: [`A1782_ManualBackup_2026-11-16_1018.zip`](./A1782_ManualBackup_2026-11-16_1018.zip)
- Direct RAW link: `https://github.com/nertwork/anker-solix-api/raw/exports/a1782-manual-backup/A1782_ManualBackup_2026-11-16_1018.zip`

## Included Files (119 JSON & log files)
The uncompressed JSON files are also available directly in the [`A1782_ManualBackup/`](./A1782_ManualBackup/) directory.

Key files for A1782 / Solarbank PPS disaster backup mock testing:
- `charging_site_device_disaster_126c3ff8-711a-6e3a-f797-1127110ccd4e.json`: Active manual disaster switch with scheduled backup details.
- `charging_disaster_support_func_126c3ff8-711a-6e3a-f797-1127110ccd4e.json`: Disaster support capability flags for A1782.
- `site_detail_126c3ff8-711a-6e3a-f797-1127110ccd4e.json`: Full site topology and device details.
- `device_attrs_*.json`: Attributes for A1782 and connected expansion batteries / portable power stations.
