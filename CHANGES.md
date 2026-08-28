# Changelog

## 0.0.7
2026-08-28, Craig C. 

### Changed

No major changes

### Fixed
- numpy compatibility issues for version 2.0, including replacing `numpy.float` (removed in v1.24) with builtin `float`
- replace `pandas.DataFrame.append` method (removed in pandas version 2.0) with `.concat` method
