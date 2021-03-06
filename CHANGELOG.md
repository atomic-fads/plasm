# Changelog

## 2.0.2

### Fixes

* Fixed issue when finding primary key when a query is passed
* No longer load test assets in non-test envs


## 2.0.1

### Fixes

* Minor typespec fix


## 2.0.0

### Backwards-Incompatible Changes

* Support only Ecto 3


## 1.1.0

### Backwards-Incompatible Changes

* Drop support for Elixir < 1.4 and Ecto < 2.2.0
* Drop support for postgrex pre-releases


## 1.0.1

### Fixes

* Fixed `latest/1` and its tests


## 1.0.0

### Additions

* Added `at`, `at_or_later_than`, `at_or_earlier_than`, `earlier_than`, `earliest`, `later_than`, `latest`, `on`, `on_or_later_than`, `on_or_earlier_than`

### Improvements

* Improved specs and docs
* Rewrite tests to perform actual DB queries for better test coverage

### Backwards-Incompatible Changes

* Renamed `sum` to `total`, `avg` to `average`, `min` to `minimum`, `max` to `maximum`
* Removed `first_inserted`, `inserted_after`, `inserted_after_incl`, `inserted_before`, `inserted_before_incl`, `last_inserted`, `updated_after`, `updated_after_incl`, `updated_before`, `updated_before_incl`


## 0.4.0

### Additions

* `avg`, `min`, `max`, and `sum` can now take String.t field names

### Backwards-Incompatible Changes

* Added missing guards for existing API to enforce compliance


## 0.3.0

* Rename `first` to `first_inserted` and `last` to `last_inserted` to avoid conflicts with Ecto 2


## 0.2.0

* Relax Ecto requirement to support 2.0
