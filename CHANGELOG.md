<a name="unreleased"></a>
## [Unreleased]


<a name="v0.4.0"></a>
## [v0.4.0] - 2021-05-13
### Bug Fixes
- AccessToken refresh correctly. Close [#2](https://github.com/ekeynow/tuyacloud/issues/2)

### Miscellaneous
- rename module to github.com/ekeynow/tuyacloud. Close [#1](https://github.com/ekeynow/tuyacloud/issues/1)


<a name="v0.3.0"></a>
## [v0.3.0] - 2021-05-12
### Miscellaneous
- Deprecated this repo


<a name="v0.2.0"></a>
## [v0.2.0] - 2020-12-31
### Features
- compensation mechanism for refresh token

### Miscellaneous
- fix lint


<a name="v0.2.0-beta.1"></a>
## [v0.2.0-beta.1] - 2020-12-29
### Features
- ExponentialBackOff support for API.


<a name="v0.1.3"></a>
## [v0.1.3] - 2020-12-29
### Bug Fixes
- token data race bug

### Features
- Query the list of home that the user lives in


<a name="v0.1.2"></a>
## [v0.1.2] - 2020-12-07
### Code Refactoring
- Make sure request struct implements `RequestBody` interface.
- Some cases HTTP DELETE need HTTP body
- Refactor pairing

### Features
- Smart Home Management
- Device Control
- Pairing Management
- User Management

### Miscellaneous
- Github Action should only works in master branch and PR


<a name="v0.1.1"></a>
## [v0.1.1] - 2020-09-07
### Bug Fixes
- Content-Type parse
- Content-Type parse

### Code Refactoring
- Refactor pairing
- Request.URI() -> Request.URL()

### Features
- Smart Home Management
- Device Control
- Pairing Management
- User Management

### Miscellaneous
- Github Action should only works in master branch and PR


<a name="v0.1.0"></a>
## v0.1.0 - 2020-09-02
### Features
- device interface
- catalog/smartlock
- More powerful API Client

### Miscellaneous
- Make CI happy
- Update README.md


[Unreleased]: https://github.com/ekeynow/tuyacloud/compare/v0.4.0...HEAD
[v0.4.0]: https://github.com/ekeynow/tuyacloud/compare/v0.3.0...v0.4.0
[v0.3.0]: https://github.com/ekeynow/tuyacloud/compare/v0.2.0...v0.3.0
[v0.2.0]: https://github.com/ekeynow/tuyacloud/compare/v0.2.0-beta.1...v0.2.0
[v0.2.0-beta.1]: https://github.com/ekeynow/tuyacloud/compare/v0.1.3...v0.2.0-beta.1
[v0.1.3]: https://github.com/ekeynow/tuyacloud/compare/v0.1.2...v0.1.3
[v0.1.2]: https://github.com/ekeynow/tuyacloud/compare/v0.1.1...v0.1.2
[v0.1.1]: https://github.com/ekeynow/tuyacloud/compare/v0.1.0...v0.1.1
