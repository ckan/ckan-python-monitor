# ckan-python-monitor

This is a monitor that twice a week runs the test suite of CKAN core against different Python versions.


## Status

| CKAN | Python | Status |
| --------- | ---- | ---- |
| 2.9 | 3.7 | [![CKAN 2.9 on Python 3.7](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckan29-python37.yml/badge.svg)](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckan29-python37.yml) |
| 2.9 | 3.8 | [![CKAN 2.9 on Python 3.8](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckan29-python38.yml/badge.svg)](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckan29-python38.yml) |
| 2.9 | 3.9 | [![CKAN 2.9 on Python 3.9](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckan29-python39.yml/badge.svg)](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckan29-python39.yml) |
| 2.10 | 3.8 | [![CKAN 2.10 on Python 3.8](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckan210-python38.yml/badge.svg)](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckan210-python38.yml) |
| 2.10 | 3.9 | [![CKAN 2.10 on Python 3.9](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckan210-python39.yml/badge.svg)](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckan210-python39.yml) |
| 2.10 | 3.10 | [![CKAN 2.10 on Python 3.10](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckan210-python310.yml/badge.svg)](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckan210-python310.yml) |
| 2.10 | 3.11 | [![CKAN 2.10 on Python 3.11](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckan211-python311.yml/badge.svg)](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckan210-python311.yml) |
| 2.11 | 3.9 | [![CKAN 2.11 on Python 3.9](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckan211-python39.yml/badge.svg)](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckan211-python39.yml) |
| 2.11 | 3.10 | [![CKAN 2.11 on Python 3.10](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckan211-python310.yml/badge.svg)](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckan211-python310.yml) |
| 2.11 | 3.11 | [![CKAN 2.11 on Python 3.11](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckan211-python311.yml/badge.svg)](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckan211-python311.yml) |
| 2.11 | 3.12 | [![CKAN 2.12 on Python 3.12](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckan211-python312.yml/badge.svg)](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckan211-python312.yml) |
| master | 3.10 | [![CKAN master on Python 3.10](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckanmaster-python310.yml/badge.svg)](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckanmaster-python310.yml) |
| master | 3.11 | [![CKAN master on Python 3.11](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckanmaster-python311.yml/badge.svg)](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckanmaster-python311.yml) |
| master | 3.12 | [![CKAN master on Python 3.12](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckanmaster-python312.yml/badge.svg)](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckanmaster-python312.yml) |


## Notes

The main goal is to keep track if the most common CKAN extensions are working as expected against CKAN core latest development branch. This can be used to easily detect breaking changes on CKAN core.

Tests are run At 12:00am on Tuesday and Thursday (`0 0 * * 2,4`) to have a fresh run before CKAN's [Tech Meetings](https://github.com/ckan/ckan/wiki/Weekly-Developer-Meetings).

For a similar monitor but for extensions check: [ckan-extensions-monitor](https://github.com/ckan/ckan-extensions-monitor)
