## 2.0.1 / 2014-08-14

### Bug Fixes

  * Count total unique words using methods supported by `Vector` and `GSL::Vector` (#11)

### Development Fixes

  * Remove `stats` rake task (#17)
  * Add some tests for `ClassifierRebord::WordList` (#15)

## 2.0.0 / 2014-08-13

### Bug Fixes

  * Remove mathn dependency (#8)
  * Only perform first order transform if total UNIQUE words is greater than 1 (#3)
  * Update `LSI#remove_item` such that they will work with the `@items` hash. (#2)

### Development Fixes

  * Exclude Gemfile.lock in .gitignore (#7)
