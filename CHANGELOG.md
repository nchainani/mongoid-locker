# Changelog

## HEAD ([diff](https://github.com/afeld/mongoid-locker/compare/v0.2.1...master?w=1))

## 0.2.1 ([diff](https://github.com/afeld/mongoid-locker/compare/v0.2.0...v0.2.1?w=1))

* fix for `update()` on Mongoid 3
* automatically reload model after waiting - #1

## 0.2.0 ([diff](https://github.com/afeld/mongoid-locker/compare/v0.1.1...v0.2.0?w=1))

* handle recursive calls to `#with_lock` - #7
* lock optimizations, particularly for large documents
* add Mongoid 3 support - #3

## 0.1.1 ([diff](https://github.com/afeld/mongoid-locker/compare/v0.1.0...v0.1.1?w=1))

* fix for subclasses - #5

## 0.1.0

Initial release!
