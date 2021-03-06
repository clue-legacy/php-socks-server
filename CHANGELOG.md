# Changelog

## 0.7.0 (2017-04-14)

* Feature / BC break: Update Socket to v0.7
  (#12 by @clue)

* Improve test suite by adding PHPUnit to require-dev
  (#11 by @clue)

> The `v0.6.0` release has been skipped intentionally to avoid confusion with
  the release tags of `clue/socks-react` and `react/socket`.

## 0.5.1 (2016-11-25)

* Feature: Cancel pending outgoing connection if incoming connection closes
  (#7 by @clue)

* Fix: Support empty strings for auth info (username or password)
  (#6 by @clue)

## 0.5.0 (2016-11-07)

* First tagged release
* Async SOCKS `Server` implementation
* Project was originally part of [clue/socks-react](https://github.com/clue/php-socks-react)
  and was split off from its latest release v0.4.0
  (#1 by @clue)

> Upgrading from clue/socks v0.4.0? Use namespace `Clue\React\Socks\Server`
  instead of `Clue\React\Socks` and you're ready to go!

## 0.0.0 (2011-04-26)

* Initial concept, originally tracked as part of
  [clue/socks](https://github.com/clue/php-socks)
