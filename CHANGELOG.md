# CHANGELOG

## [3.0.10] - 2021-10-13
### Changed
- `HttpClient` and `WsClient` no longer have default type param

## [3.0.6] - 2021-09-01
### Fixed
- `HttpProxy` 检查返回码是否为 200
- 修复 Cocos 3.2 新版本无法 import 的问题
- 更新 `tsrpc-base-client` 修复一些问题

## [3.0.5] - 2021-08-14

### Changed
- `callApi` 返回错误非业务错误时，通过 `logger.error` 打印日志而不是 `logger.log`。
- handler of `client.listenMsg` changed to `(msg, msgName, client)=>void` 