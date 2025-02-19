### Tobac Changelog

_**Version 1.3:**_

**Enhancements**

- Significant performance improvements for tracking [#89](https://github.com/climate-processes/tobac/pull/89)
- Significant performance improvements for feature detection and segmentation [#90](https://github.com/climate-processes/tobac/pull/90)
- Performance improvement for `calculate_area` [#93](https://github.com/climate-processes/tobac/issues/93)
- Added ability to set a user defined stub cell value instead of `np.nan`. Default value is `-1` and stub cell values are now integers instead of floats by default [#74](https://github.com/climate-processes/tobac/issues/93)
- Added deprecation warnings for parameters `min_num` in feature detection and `d_min` in tracking, and added exceptions when multiple, incompatible parameters are given (e.g. `d_max` and `v_max`) [#107](https://github.com/climate-processes/tobac/pull/107)

**Bug fixes**

- Fixed level parameter in segmentation, as this previously had no effect [#92](https://github.com/climate-processes/tobac/pull/92)
- Remove `is` comparisons for string literals [#99](https://github.com/climate-processes/tobac/pull/99)
- Added missing `raise` for exception in `get_spacings` [#105](https://github.com/climate-processes/tobac/pull/105)
- Remove automatic setting of matplotlib backend to `agg` on import [#100](https://github.com/climate-processes/tobac/pull/100)
- Fix deprecation warnings for changed import paths in dependencies [#110](https://github.com/climate-processes/tobac/pull/110)

**Documentation**

- Added recommended python style [#72](https://github.com/climate-processes/tobac/issues/72)
- Updated author list and email addresses [#109](https://github.com/climate-processes/tobac/pull/109)

**Repository enhancements**

- Black formatting of all python code and formatting check in actions [#78](https://github.com/climate-processes/tobac/pull/78)
- Pre-commit hook for black formatting [#96](https://github.com/climate-processes/tobac/pull/96)
