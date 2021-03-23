# DEPRECATED

See https://pub.dev/packages/quiver instead!

Quiver Cache
============

A semi-persistent cache with map semantics.

[![Build Status](https://travis-ci.org/QuiverDart/quiver_cache.svg?branch=master)](https://travis-ci.org/QuiverDart/quiver_cache)
[![Coverage Status](https://img.shields.io/coveralls/QuiverDart/quiver_cache.svg)](https://coveralls.io/r/QuiverDart/quiver_cache)

## Documentation

[API Docs](http://www.dartdocs.org/documentation/quiver_cache/latest)

`Cache` is a semi-persistent, asynchronously accessed, mapping of keys to
values. Caches are similar to Maps, except that the cache implementation might
store values in a remote system, so all operations are asynchronous, and caches
might have eviction policies.

`MapCache` is a Cache implementation backed by a Map.
