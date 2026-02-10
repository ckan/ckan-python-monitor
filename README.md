# ckan-python-monitor

This is a monitor that twice a week runs the test suite of CKAN core against different Python versions.



## Status

| Python version | CKAN 2.10 | CKAN 2.11 | CKAN master |
| --- | --- | --- | --- |
| 3.10 | [![CKAN 2.10 on Python 3.10](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckan210-py310.yml/badge.svg)](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckan210-py310.yml) | [![CKAN 2.11 on Python 3.10](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckan211-py310.yml/badge.svg)](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckan211-py310.yml) | [![CKAN master on Python 3.10](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckanmaster-py310.yml/badge.svg)](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckanmaster-py310.yml) |
| 3.11 | [![CKAN 2.10 on Python 3.11](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckan210-py311.yml/badge.svg)](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckan210-py311.yml) | [![CKAN 2.11 on Python 3.11](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckan211-py311.yml/badge.svg)](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckan211-py311.yml) | [![CKAN master on Python 3.11](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckanmaster-py311.yml/badge.svg)](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckanmaster-py311.yml) |
| 3.12 | Not supported | [![CKAN 2.11 on Python 3.12](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckan211-py312.yml/badge.svg)](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckan211-py312.yml) | [![CKAN master on Python 3.12](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckanmaster-py312.yml/badge.svg)](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckanmaster-py312.yml) |
| 3.13 | Not supported | [![CKAN 2.11 on Python 3.13](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckan211-py313.yml/badge.svg)](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckan211-py313.yml) | [![CKAN master on Python 3.13](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckanmaster-py313.yml/badge.svg)](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckanmaster-py313.yml) |
| 3.14 | Not supported | [![CKAN 2.11 on Python 3.14](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckan211-py314.yml/badge.svg)](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckan211-py314.yml) | [![CKAN master on Python 3.14](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckanmaster-py314.yml/badge.svg)](https://github.com/ckan/ckan-python-monitor/actions/workflows/ckanmaster-py314.yml) |


## Notes

These workflows run the main CKAN core tests against different Python versions.

Tests are run At 12:00am on Tuesday and Thursday (`0 0 * * 2,4`) to have a fresh run before CKAN's [Tech Meetings](https://github.com/ckan/ckan/wiki/Weekly-Developer-Meetings).

For a similar monitor but for extensions check: [ckan-extensions-monitor](https://github.com/ckan/ckan-extensions-monitor)
