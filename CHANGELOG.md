# Changelog

## [master](https://github.com/anmonteiro/lumo/compare/1.0.0-alpha1...HEAD) (unreleased)

### New features

- Add `load` REPL special function. Same as [Clojure's `load`](http://clojure.github.io/clojure/clojure.core-api.html#clojure.core/load).

### Bug fixes

- Lack of OpenSSL support breaks some Node.js modules ([#2](https://github.com/anmonteiro/lumo/issues/2)).
- Allow foreign libraries to side-effect the global scope when required.
- Improve error message when a path is not passed to `-k` ([#14](https://github.com/anmonteiro/lumo/issues/14)).
- Don't throw when loading empty files [#10](https://github.com/anmonteiro/lumo/issues/10).
- `load-file` and init scripts shouldn't change the current namespace.

## 1.0-alpha1 (2016-11-09)

- Initial version.
