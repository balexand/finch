# Changelog

## v0.5.2 (2020-11-10)
* Fix deprecation in nimble_options.

## v0.5.1 (2020-10-27)
* Fix crash in http2 pools when a message is received in disconnected state.

## v0.5.0 (2020-10-26)
* Add `:max_idle_time` option for http1 pools
* Optimize http2 connection closing.
* Use new lazy pools in NimblePool
* Additional `idle_time` measurements for all http1 connection telemetry

## v0.4.0 (2020-10-2)
* Update all dependencies. This includes bug fixes for Mint.

## v0.3.2 (2020-09-18)
* Add metadata to connection start telemetry in http/2 pools

## v0.3.1 (2020-08-29)
* Add HTTP method to telemetry events
* BUGFIX - Include query parameters in HTTP/2 requests

## v0.3.0 (2020-06-24)
* HTTP/2 support
* Streaming support for both http/1.1 and http/2 pools
* New api for building and making requests
* typespec fixes

## v0.2.0 (2020-05-06)
* Response body now defaults to an empty string instead of nil

## v0.1.1 (2020-05-04)
* Accepts a URI struct in request/3/4/5/6, Todd Resudek
* Fix `http_method()` typespec, Ryan Johnson

## v0.1.0 (2020-04-25)
* Initial Release
