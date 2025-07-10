# Changelog

## [0.1.8] - 2025-07-10

### Changed
- Modernized `pyproject.toml` to correct `setuptools` and `pytest` configurations.
- Updated `api` dependencies to their latest versions.
- Integrated `uvicorn` for a more lightweight and efficient server deployment.
- Refactored `lettucedetect_api/server.py` to remove redundant `asyncio.Lock` usage.
- Simplified `scripts/start_api.py` to use `uvicorn` directly.
