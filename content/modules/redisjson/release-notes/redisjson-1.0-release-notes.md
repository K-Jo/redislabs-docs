---
Title: RedisJSON 1.0 Release Notes
description:
weight: 100
alwaysopen: false
categories: ["Modules"]
---
## RedisJSON 1.0.8 (August 2021)

This is a maintenance release for version 1.0.
Update urgency: `LOW` -  No need to upgrade unless there are new features you want to use.

Details:

- Enhancements:
    - #[257](https://github.com/redisjson/redisjson/issues/257) Support inter shards TLS capability

- Bug fixes:
   - #[282](https://github.com/redisjson/redisjson/issues/282) Change [JSON.DEBUG](https://oss.redislabs.com/redisjson/commands/#jsondebug) first key index to 2

## RedisJSON 1.0.7 (December 2020)

This is a maintenance release for version 1.0.

Headlines:

- This release improves overall stability and provides fixes for issues found after the previous release.

Details:

- [#222](https://github.com/RedisJSON/RedisJSON/pull/222) Validate path is not empty.
- [#253](https://github.com/RedisJSON/RedisJSON/pull/253) `NULL` de-reference after error.

## RedisJSON 1.0.5 (September 2020)

This is a maintenance release for version 1.0.

Headlines:

- This release improves overall stability and provides fixes for issues found after the previous release.

Details:

- Enhancements:
    - Republish docker image based on Redis 6
- Bugfixes:
    - #[200](https://github.com/RedisJSON/RedisJSON/issues/200) Following a call to JSON.ARRPOP and JSON.STRAPPEND, the LRU cache should be invalidated.

## RedisJSON 1.0.4 (February 2019)

## RedisJSON 1.0.3

This release disables the cache by default, and allows an explicit `CACHE` `<ON|OFF>` module argument to enable it.

## RedisJSON 1.0.2 (September 2018)

This release contains some bug fixes over 1.0.2. It also includes some ci changes as well.

## RedisJSON 1.0.1 (December 2017)
