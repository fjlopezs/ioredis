## [4.14.3](https://github.com/luin/ioredis/compare/v4.14.2...v4.14.3) (2019-11-07)


### Bug Fixes

* update funding information ([c83cb05](https://github.com/luin/ioredis/commit/c83cb0524258e8090d0ae487c5d13cc873af2e27))

## [4.14.2](https://github.com/luin/ioredis/compare/v4.14.1...v4.14.2) (2019-10-23)


### Bug Fixes

* security deps updates [skip ci] ([a7095d7](https://github.com/luin/ioredis/commit/a7095d7ab66d9791c3c9a73ea3673c54dce5959d))

## [4.14.1](https://github.com/luin/ioredis/compare/v4.14.0...v4.14.1) (2019-08-27)


### Bug Fixes

* don’t clobber passed-in tls options with rediss:/ URLs ([#949](https://github.com/luin/ioredis/issues/949)) ([ceefcfa](https://github.com/luin/ioredis/commit/ceefcfa)), closes [#942](https://github.com/luin/ioredis/issues/942) [#940](https://github.com/luin/ioredis/issues/940) [#950](https://github.com/luin/ioredis/issues/950) [#948](https://github.com/luin/ioredis/issues/948)

# [4.14.0](https://github.com/luin/ioredis/compare/v4.13.1...v4.14.0) (2019-07-31)


### Features

* support rediss:// URL ([371bb9c](https://github.com/luin/ioredis/commit/371bb9c))

## [4.13.1](https://github.com/luin/ioredis/compare/v4.13.0...v4.13.1) (2019-07-22)


### Bug Fixes

* keep sentinels of options immutable ([bacb7e1](https://github.com/luin/ioredis/commit/bacb7e1)), closes [#936](https://github.com/luin/ioredis/issues/936)

# [4.13.0](https://github.com/luin/ioredis/compare/v4.12.2...v4.13.0) (2019-07-19)


### Bug Fixes

* **cluster:** suppress errors emitted from internal clients ([9a113ca](https://github.com/luin/ioredis/commit/9a113ca)), closes [#896](https://github.com/luin/ioredis/issues/896) [#899](https://github.com/luin/ioredis/issues/899)


### Features

* **cluster:** support binary keys ([b414ed9](https://github.com/luin/ioredis/commit/b414ed9)), closes [#637](https://github.com/luin/ioredis/issues/637)

## [4.12.2](https://github.com/luin/ioredis/compare/v4.12.1...v4.12.2) (2019-07-16)


### Bug Fixes

* **cluster:** prefer master when there're two same node for a slot ([8fb9f97](https://github.com/luin/ioredis/commit/8fb9f97))
* **cluster:** remove node immediately when slots are redistributed ([ecc13ad](https://github.com/luin/ioredis/commit/ecc13ad)), closes [#930](https://github.com/luin/ioredis/issues/930)

## [4.12.1](https://github.com/luin/ioredis/compare/v4.12.0...v4.12.1) (2019-07-15)


### Bug Fixes

* handle connecting immediately after "end" event ([#929](https://github.com/luin/ioredis/issues/929)) ([7bcd8a8](https://github.com/luin/ioredis/commit/7bcd8a8)), closes [#928](https://github.com/luin/ioredis/issues/928)

# [4.12.0](https://github.com/luin/ioredis/compare/v4.11.2...v4.12.0) (2019-07-14)


### Features

* **cluster:** add #duplicate() method ([#926](https://github.com/luin/ioredis/issues/926)) ([8b150c2](https://github.com/luin/ioredis/commit/8b150c2))

## [4.11.2](https://github.com/luin/ioredis/compare/v4.11.1...v4.11.2) (2019-07-13)


### Bug Fixes

* ETIMEDOUT error with Bluebird when connecting. ([#925](https://github.com/luin/ioredis/issues/925)) ([4bce38b](https://github.com/luin/ioredis/commit/4bce38b)), closes [#918](https://github.com/luin/ioredis/issues/918)

## [4.11.1](https://github.com/luin/ioredis/compare/v4.11.0...v4.11.1) (2019-06-26)


### Bug Fixes

* use connector as class not value ([#909](https://github.com/luin/ioredis/issues/909)) ([3fb2552](https://github.com/luin/ioredis/commit/3fb2552))

# [4.11.0](https://github.com/luin/ioredis/compare/v4.10.4...v4.11.0) (2019-06-25)


### Features

* support custom connectors ([#906](https://github.com/luin/ioredis/issues/906)) ([bf3fe29](https://github.com/luin/ioredis/commit/bf3fe29))

## [4.10.4](https://github.com/luin/ioredis/compare/v4.10.3...v4.10.4) (2019-06-11)


### Bug Fixes

* **cluster:** passing frozen natMap option causes crash ([3bc6165](https://github.com/luin/ioredis/commit/3bc6165)), closes [#887](https://github.com/luin/ioredis/issues/887)

## [4.10.3](https://github.com/luin/ioredis/compare/v4.10.2...v4.10.3) (2019-06-08)


### Bug Fixes

* **cluster:** reorder defaults arguments to prioritize user options ([#889](https://github.com/luin/ioredis/issues/889)) ([8da8d78](https://github.com/luin/ioredis/commit/8da8d78))

## [4.10.2](https://github.com/luin/ioredis/compare/v4.10.1...v4.10.2) (2019-06-08)


### Bug Fixes

* pipeline with transactions causes unhandled warnings ([#884](https://github.com/luin/ioredis/issues/884)) ([bbfd2fc](https://github.com/luin/ioredis/commit/bbfd2fc)), closes [#883](https://github.com/luin/ioredis/issues/883)

## [4.10.1](https://github.com/luin/ioredis/compare/v4.10.0...v4.10.1) (2019-06-08)


### Bug Fixes

* upgrade deps to resolve security vulnerabilities warnings ([#885](https://github.com/luin/ioredis/issues/885)) ([98c27cf](https://github.com/luin/ioredis/commit/98c27cf))

# [4.10.0](https://github.com/luin/ioredis/compare/v4.9.5...v4.10.0) (2019-05-23)


### Features

* upgrade to redis-commands@1.5.0 for streams support ([644f5cb](https://github.com/luin/ioredis/commit/644f5cb)), closes [#875](https://github.com/luin/ioredis/issues/875)

## [4.9.5](https://github.com/luin/ioredis/compare/v4.9.4...v4.9.5) (2019-05-15)


### Bug Fixes

* **cluster:** make blocking commands works with cluster ([#867](https://github.com/luin/ioredis/issues/867)) ([68db71b](https://github.com/luin/ioredis/commit/68db71b)), closes [#850](https://github.com/luin/ioredis/issues/850) [#850](https://github.com/luin/ioredis/issues/850)

## [4.9.4](https://github.com/luin/ioredis/compare/v4.9.3...v4.9.4) (2019-05-13)


### Bug Fixes

* handle non-utf8 command name ([#866](https://github.com/luin/ioredis/issues/866)) ([9ddb58b](https://github.com/luin/ioredis/commit/9ddb58b)), closes [#862](https://github.com/luin/ioredis/issues/862)

## [4.9.3](https://github.com/luin/ioredis/compare/v4.9.2...v4.9.3) (2019-05-07)


### Bug Fixes

* more meaningful errors when using pipeline after exec(). ([#858](https://github.com/luin/ioredis/issues/858)) ([0c3ef01](https://github.com/luin/ioredis/commit/0c3ef01))

## [4.9.2](https://github.com/luin/ioredis/compare/v4.9.1...v4.9.2) (2019-05-03)


### Bug Fixes

* removed flexbuffer dependency ([#856](https://github.com/luin/ioredis/issues/856)) ([35e0c5e](https://github.com/luin/ioredis/commit/35e0c5e))

## [4.9.1](https://github.com/luin/ioredis/compare/v4.9.0...v4.9.1) (2019-03-22)


### Bug Fixes

* use flexbuffer from GH with License ([#821](https://github.com/luin/ioredis/issues/821)) ([93ecd70](https://github.com/luin/ioredis/commit/93ecd70))

# [4.9.0](https://github.com/luin/ioredis/compare/v4.8.0...v4.9.0) (2019-03-18)


### Features

* **sentinel:** support Sentinel instances with authentication. ([#817](https://github.com/luin/ioredis/issues/817)) ([2437eae](https://github.com/luin/ioredis/commit/2437eae))

# [4.8.0](https://github.com/luin/ioredis/compare/v4.7.0...v4.8.0) (2019-03-12)


### Features

* nat support for sentinel connector ([#799](https://github.com/luin/ioredis/issues/799)) ([335b3e2](https://github.com/luin/ioredis/commit/335b3e2))

# [4.7.0](https://github.com/luin/ioredis/compare/v4.6.3...v4.7.0) (2019-03-12)


### Features

* add updateSentinels option to control new sentinel values being added to the original list ([#814](https://github.com/luin/ioredis/issues/814)) ([50a9db7](https://github.com/luin/ioredis/commit/50a9db7)), closes [#798](https://github.com/luin/ioredis/issues/798)

## [4.6.3](https://github.com/luin/ioredis/compare/v4.6.2...v4.6.3) (2019-02-03)


### Bug Fixes

* add second arg to "node error" to know which node failed ([#793](https://github.com/luin/ioredis/issues/793)) ([6049f6c](https://github.com/luin/ioredis/commit/6049f6c)), closes [#774](https://github.com/luin/ioredis/issues/774)

## [4.6.2](https://github.com/luin/ioredis/compare/v4.6.1...v4.6.2) (2019-02-02)


### Bug Fixes

* subscriber initialization when using Cluster ([#792](https://github.com/luin/ioredis/issues/792)) ([32c48ef](https://github.com/luin/ioredis/commit/32c48ef)), closes [#791](https://github.com/luin/ioredis/issues/791)

## [4.6.1](https://github.com/luin/ioredis/compare/v4.6.0...v4.6.1) (2019-01-29)


### Bug Fixes

* **Cluster:** ignore connection errors for subscriber. ([#790](https://github.com/luin/ioredis/issues/790)) ([f368c8a](https://github.com/luin/ioredis/commit/f368c8a)), closes [#768](https://github.com/luin/ioredis/issues/768)

# [4.6.0](https://github.com/luin/ioredis/compare/v4.5.1...v4.6.0) (2019-01-21)


### Features

* add maxLoadingRetryTime option when redis server not ready ([#784](https://github.com/luin/ioredis/issues/784)) ([0e7713f](https://github.com/luin/ioredis/commit/0e7713f))

## [4.5.1](https://github.com/luin/ioredis/compare/v4.5.0...v4.5.1) (2019-01-13)


### Performance Improvements

* add checking and loading scripts uniqueness in pipeline ([#781](https://github.com/luin/ioredis/issues/781)) ([66075ba](https://github.com/luin/ioredis/commit/66075ba))

# [4.5.0](https://github.com/luin/ioredis/compare/v4.4.0...v4.5.0) (2019-01-07)


### Features

* allow TLS when using Sentinel ([ebef8f5](https://github.com/luin/ioredis/commit/ebef8f5))

# [4.4.0](https://github.com/luin/ioredis/compare/v4.3.1...v4.4.0) (2019-01-04)


### Features

* support setting connectTimeout in Electron ([#770](https://github.com/luin/ioredis/issues/770)) ([2d591b7](https://github.com/luin/ioredis/commit/2d591b7))

## [4.3.1](https://github.com/luin/ioredis/compare/v4.3.0...v4.3.1) (2018-12-16)


### Bug Fixes

* **cluster:** handle connection errors by reconnection ([#762](https://github.com/luin/ioredis/issues/762)) ([21138af](https://github.com/luin/ioredis/commit/21138af)), closes [#753](https://github.com/luin/ioredis/issues/753)

# [4.3.0](https://github.com/luin/ioredis/compare/v4.2.3...v4.3.0) (2018-12-09)


### Features

* **cluster:** add NAT support ([#758](https://github.com/luin/ioredis/issues/758)) ([3702d67](https://github.com/luin/ioredis/commit/3702d67)), closes [#693](https://github.com/luin/ioredis/issues/693) [#365](https://github.com/luin/ioredis/issues/365)

## [4.2.3](https://github.com/luin/ioredis/compare/v4.2.2...v4.2.3) (2018-11-24)


### Bug Fixes

* MOVED slot redirection handler ([#749](https://github.com/luin/ioredis/issues/749)) ([bba418f](https://github.com/luin/ioredis/commit/bba418f))

## [4.2.2](https://github.com/luin/ioredis/compare/v4.2.1...v4.2.2) (2018-10-20)

## [4.2.1](https://github.com/luin/ioredis/compare/v4.2.0...v4.2.1) (2018-10-19)

# [4.2.0](https://github.com/luin/ioredis/compare/v4.1.0...v4.2.0) (2018-10-17)


### Features

* support customize dns lookup function ([#723](https://github.com/luin/ioredis/issues/723)) ([b9c4793](https://github.com/luin/ioredis/commit/b9c4793)), closes [antirez/redis#2410](https://github.com/antirez/redis/issues/2410)

<a name="4.1.0"></a>
# [4.1.0](https://github.com/luin/ioredis/compare/v4.0.0...v4.1.0) (2018-10-15)


### Bug Fixes

* **cluster:** quit() ignores errors caused by disconnected connection ([#720](https://github.com/luin/ioredis/issues/720)) ([fb3eb76](https://github.com/luin/ioredis/commit/fb3eb76))
* **cluster:** robust solution for pub/sub in cluster ([#697](https://github.com/luin/ioredis/issues/697)) ([13a5bc4](https://github.com/luin/ioredis/commit/13a5bc4)), closes [#696](https://github.com/luin/ioredis/issues/696)
* **cluster:** stop subscriber when disconnecting ([fb27b66](https://github.com/luin/ioredis/commit/fb27b66))


### Features

* **cluster:** re-select subscriber when the currenct one is failed ([c091f2e](https://github.com/luin/ioredis/commit/c091f2e))


### Performance Improvements

* remove lodash deps for smaller memory footprint ([80f4a45](https://github.com/luin/ioredis/commit/80f4a45))
* **cluster:** make disconnecting from cluster faster ([#721](https://github.com/luin/ioredis/issues/721)) ([ce46d6b](https://github.com/luin/ioredis/commit/ce46d6b))



<a name="4.0.2"></a>
## [4.0.2](https://github.com/luin/ioredis/compare/v4.0.1...v4.0.2) (2018-10-09)


### Bug Fixes

* **cluster:** subscription regards password setting ([47e2ab5](https://github.com/luin/ioredis/commit/47e2ab5)), closes [#718](https://github.com/luin/ioredis/issues/718)


### Performance Improvements

* reduce package bundle size ([eb68e9a](https://github.com/luin/ioredis/commit/eb68e9a))



<a name="4.0.1"></a>
## [4.0.1](https://github.com/luin/ioredis/compare/v4.0.0...v4.0.1) (2018-10-08)


### Bug Fixes

* **cluster:** robust solution for pub/sub in cluster ([#697](https://github.com/luin/ioredis/issues/697)) ([13a5bc4](https://github.com/luin/ioredis/commit/13a5bc4)), closes [#696](https://github.com/luin/ioredis/issues/696)



<a name="4.0.0"></a>
# [4.0.0](https://github.com/luin/ioredis/compare/v4.0.0-3...v4.0.0) (2018-08-14)

**This is a major release and contain breaking changes. Please read this changelog before upgrading.**

## Changes since 4.0.0-3:

### Bug Fixes

* port is ignored when path set to null ([d40a99e](https://github.com/luin/ioredis/commit/d40a99e)), closes [#668](https://github.com/luin/ioredis/issues/668)


### Features

* export Pipeline for inheritances enabling ([#675](https://github.com/luin/ioredis/issues/675)) ([ca58249](https://github.com/luin/ioredis/commit/ca58249))
* export ScanStream at package level ([#667](https://github.com/luin/ioredis/issues/667)) ([5eb4198](https://github.com/luin/ioredis/commit/5eb4198))

## Changes since 3.x

### Bug Fixes

* **Sentinel:** unreachable errors when sentinals are healthy ([7bf6fea](https://github.com/luin/ioredis/commit/7bf6fea))
* resolve warning for Buffer() in Node.js 10 ([6144c56](https://github.com/luin/ioredis/commit/6144c56))
* don't add cluster.info to the failover queue before ready ([491546d](https://github.com/luin/ioredis/commit/491546d))
* solves vulnerabilities dependencies ([2950b79](https://github.com/luin/ioredis/commit/2950b79))
* **Cluster:** issues when setting enableOfflineQueue to false ([#649](https://github.com/luin/ioredis/issues/649)) ([cfe4258](https://github.com/luin/ioredis/commit/cfe4258))

### Performance Improvements

* upgrade redis-parser for better performance.

### Features

* use native Promise instead of Bluebird, and allow users to switch back. ([da60b8b](https://github.com/luin/ioredis/commit/da60b8b))
* add maxRetriesPerRequest option to limit the retries attempts per command ([1babc13](https://github.com/luin/ioredis/commit/1babc13))
* `Redis#connect()` will be resolved when status is ready ([#648](https://github.com/luin/ioredis/issues/648)) ([f0c600b](https://github.com/luin/ioredis/commit/f0c600b))
* add debug details for connection pool ([9ec16b6](https://github.com/luin/ioredis/commit/9ec16b6))
* wait for ready state before resolving cluster.connect() ([7517a73](https://github.com/luin/ioredis/commit/7517a73))


### BREAKING CHANGES

* Drop support for < node v6
* **Use native Promise instead of Bluebird**. This change makes all the code that rely on the features provided by Bluebird not working
anymore. For example, `redis.get('foo').timeout(500)` now should be failed since the native
Promise doesn't support the `timeout` method. You can switch back to the Bluebird
implementation by setting `Redis.Promise`:

```
const Redis = require('ioredis')
Redis.Promise = require('bluebird')

const redis = new Redis()

// Use bluebird
assert.equal(redis.get().constructor, require('bluebird'))

// You can change the Promise implementation at any time:
Redis.Promise = global.Promise
assert.equal(redis.get().constructor, global.Promise)
```
* `Redis#connect()` will be resolved when status is ready
instead of `connect`:

```
const redis = new Redis({ lazyConnect: true })
redis.connect().then(() => {
  assert(redis.status === 'ready')
})
```
* `Cluster#connect()` will be resolved when the connection
status become `ready` instead of `connect`.
* The maxRetriesPerRequest is set to 20 instead of null (same behavior as ioredis v3)
by default. So when a redis server is down, pending commands won't wait forever
until the connection become alive, instead, they only wait about 10s (depends on the
retryStrategy option)
* The `new` keyword is required explicitly. Calling `Redis` as a function like
Redis(/* options */)` is deprecated and will not be supported in the next major version,
use `new Redis(/* options */)` instead.


<a name="4.0.0-3"></a>
# [4.0.0-3](https://github.com/luin/ioredis/compare/v4.0.0-2...v4.0.0-3) (2018-07-22)


### Bug Fixes

* **Sentinel:** unreachable errors when sentinals are healthy ([7bf6fea](https://github.com/luin/ioredis/commit/7bf6fea))
* resolve warning for Buffer() in Node.js 10 ([6144c56](https://github.com/luin/ioredis/commit/6144c56))



<a name="4.0.0-2"></a>
# [4.0.0-2](https://github.com/luin/ioredis/compare/v4.0.0-1...v4.0.0-2) (2018-07-07)

Upgrade redis-parser to v3.
See release notes on [redis-parser repo](https://github.com/NodeRedis/node-redis-parser/releases/tag/v.3.0.0) for details.


<a name="4.0.0-1"></a>
# [4.0.0-1](https://github.com/luin/ioredis/compare/v4.0.0-0...v4.0.0-1) (2018-07-02)


### Bug Fixes

* remove unnecessary bluebird usage ([2502b1b](https://github.com/luin/ioredis/commit/2502b1b))



<a name="4.0.0-0"></a>
# [4.0.0-0](https://github.com/luin/ioredis/compare/v3.2.2...v4.0.0-0) (2018-07-01)


### Bug Fixes

* Deprecated `Redis()` in favor of `new Redis()` ([8e7c6f1](https://github.com/luin/ioredis/commit/8e7c6f1))
* don't add cluster.info to the failover queue before ready ([491546d](https://github.com/luin/ioredis/commit/491546d))
* solves vulnerabilities dependencies ([2950b79](https://github.com/luin/ioredis/commit/2950b79))
* **Cluster:** issues when setting enableOfflineQueue to false ([#649](https://github.com/luin/ioredis/issues/649)) ([cfe4258](https://github.com/luin/ioredis/commit/cfe4258))


### Features

* use native Promise instead of Bluebird, and allow users to switch back. ([da60b8b](https://github.com/luin/ioredis/commit/da60b8b))
* add maxRetriesPerRequest option to limit the retries attempts per command ([1babc13](https://github.com/luin/ioredis/commit/1babc13))
* `Redis#connect()` will be resolved when status is ready ([#648](https://github.com/luin/ioredis/issues/648)) ([f0c600b](https://github.com/luin/ioredis/commit/f0c600b))
* add debug details for connection pool ([9ec16b6](https://github.com/luin/ioredis/commit/9ec16b6))
* wait for ready state before resolving cluster.connect() ([7517a73](https://github.com/luin/ioredis/commit/7517a73))


### BREAKING CHANGES

* Drop support for < node v6
* Use native Promise instead of Bluebird. This change makes all the code that rely on the features provided by Bluebird not working
anymore. For example, `redis.get('foo').timeout(500)` now should be failed since the native
Promise doesn't support the `timeout` method. You can switch back to the Bluebird
implementation by setting `Redis.Promise`:

```
const Redis = require('ioredis')
Redis.Promise = require('bluebird')

const redis = new Redis()

// Use bluebird
assert.equal(redis.get().constructor, require('bluebird'))

// You can change the Promise implementation at any time:
Redis.Promise = global.Promise
assert.equal(redis.get().constructor, global.Promise)
```
* `Redis#connect()` will be resolved when status is ready
instead of `connect`:

```
const redis = new Redis({ lazyConnect: true })
redis.connect().then(() => {
  assert(redis.status === 'ready')
})
```
* `Cluster#connect()` will be resolved when the connection
status become `ready` instead of `connect`.
* The maxRetriesPerRequest is set to 20 instead of null (same behavior as ioredis v3)
by default. So when a redis server is down, pending commands won't wait forever
until the connection become alive, instead, they only wait about 10s (depends on the
retryStrategy option)
* The `new` keyword is required explicitly. Calling `Redis` as a function like
`Redis(/* options */)` is deprecated and will not be supported in the next major version,
use `new Redis(/* options */)` instead.

<a name="3.2.2"></a>
## [3.2.2](https://github.com/luin/ioredis/compare/v3.2.1...v3.2.2) (2017-11-30)



<a name="3.2.1"></a>
## [3.2.1](https://github.com/luin/ioredis/compare/v3.2.0...v3.2.1) (2017-10-04)


### Bug Fixes

* **Cluster:** empty key name was sent to random nodes ([e42f30f](https://github.com/luin/ioredis/commit/e42f30f))



<a name="3.2.0"></a>
# [3.2.0](https://github.com/luin/ioredis/compare/v3.1.4...v3.2.0) (2017-10-01)


### Features

* truncate large/long debug output arguments ([#523](https://github.com/luin/ioredis/issues/523)) ([cf18554](https://github.com/luin/ioredis/commit/cf18554))



<a name="3.1.4"></a>
## [3.1.4](https://github.com/luin/ioredis/compare/v3.1.3...v3.1.4) (2017-08-13)

We mistakenly used `Object.assign` to replace `lodash.assign` in v3.1.3, which is not supported
by the old Node.js version (0.10.x). This change was a BC change and shouldn't happen without changing
the major version, so we added `lodash.assign` back.


<a name="3.1.3"></a>
## [3.1.3](https://github.com/luin/ioredis/compare/v3.1.2...v3.1.3) (2017-08-13)


### Bug Fixes

* allow convertObjectToArray to handle objects with no prototype ([#507](https://github.com/luin/ioredis/issues/507)) ([8e17920](https://github.com/luin/ioredis/commit/8e17920))



<a name="3.1.2"></a>
## [3.1.2](https://github.com/luin/ioredis/compare/v3.1.1...v3.1.2) (2017-07-26)


### Bug Fixes

* stop mutating the arguments when calling multi ([#480](https://github.com/luin/ioredis/issues/480)) ([a380030](https://github.com/luin/ioredis/commit/a380030))



<a name="3.1.1"></a>
## [3.1.1](https://github.com/luin/ioredis/compare/v3.1.0...v3.1.1) (2017-05-31)


### Bug Fixes

* show error name the error stack for Node.js 8 ([a628aa7](https://github.com/luin/ioredis/commit/a628aa7))



<a name="3.1.0"></a>
# [3.1.0](https://github.com/luin/ioredis/compare/v3.0.0...v3.1.0) (2017-05-30)


### Bug Fixes

* non-owned properties cause empty args for mset & hmset ([#469](https://github.com/luin/ioredis/issues/469)) ([e7b6352](https://github.com/luin/ioredis/commit/e7b6352))


### Features

* **cluster:** add option to control timeout on cluster slots refresh ([#475](https://github.com/luin/ioredis/issues/475)) ([493d095](https://github.com/luin/ioredis/commit/493d095))



<a name="3.0.0"></a>
# [3.0.0](https://github.com/luin/ioredis/compare/v3.0.0-2...v3.0.0) (2017-05-18)


### Features

* **pipeline:** add #length to get the command count ([a6060cb](https://github.com/luin/ioredis/commit/a6060cb)), closes [#461](https://github.com/luin/ioredis/issues/461)
* **sentinel:** allow connection to IPv6-only sentinels ([#463](https://github.com/luin/ioredis/issues/463)) ([a389f3c](https://github.com/luin/ioredis/commit/a389f3c))



<a name="3.0.0-2"></a>
# [3.0.0-2](https://github.com/luin/ioredis/compare/v3.0.0-1...v3.0.0-2) (2017-05-03)


### Bug Fixes

* restore the default connectTimeout to 10000 ([dc8256e](https://github.com/luin/ioredis/commit/dc8256e))



<a name="3.0.0-1"></a>
# [3.0.0-1](https://github.com/luin/ioredis/compare/v3.0.0-0...v3.0.0-1) (2017-04-16)


### Features

* add debug logs for resolved sentinel nodes ([8f3d3f7](https://github.com/luin/ioredis/commit/8f3d3f7))
* report error on Sentinel connection refused ([#445](https://github.com/luin/ioredis/issues/445)) ([#446](https://github.com/luin/ioredis/issues/446)) ([286a5bc](https://github.com/luin/ioredis/commit/286a5bc))
* set default port of sentinels to 26379. ([#441](https://github.com/luin/ioredis/issues/441)) ([539fe41](https://github.com/luin/ioredis/commit/539fe41))


### BREAKING CHANGES

* The default port of sentinels are now 26379 instead of 6379. This shouldn't break your app in most case since few setups has the sentinel server running on 6379, but if it's your case and the port isn't set explicitly, please go to update it.



<a name="3.0.0-0"></a>
# [3.0.0-0](https://github.com/luin/ioredis/compare/v2.5.0...v3.0.0-0) (2017-01-26)

This is a performance-focused release. We finially switch to the new version of JavaScript parser and drop the support for hiredis (Thanks to the lovely community!).
Also, we switch to [denque](https://github.com/Salakar/denque) to improve the queueing performance.

Let us know if there's any issue when using this pre-release.

### Other Changes

* increase the default reconnection interval ([c5fefb7](https://github.com/luin/ioredis/commit/c5fefb7)), closes [#414](https://github.com/luin/ioredis/issues/414)


### BREAKING CHANGES

* Although the interface doesn't change after upgrading the js parser, there may be still some potential internal differences that may break the applications which rely on them. Also, force a major version bump emphasizes the dropping of the hiredis.



<a name="2.5.0"></a>
# [2.5.0](https://github.com/luin/ioredis/compare/v2.4.3...v2.5.0) (2017-01-06)


### Features

* quit immediately when in reconnecting state (#410) ([a6f04f2](https://github.com/luin/ioredis/commit/a6f04f2))



<a name="2.4.3"></a>
## [2.4.3](https://github.com/luin/ioredis/compare/v2.4.2...v2.4.3) (2016-12-15)


### Bug Fixes

* wait all the commands in a pipeline before sending #411 (#413) ([bfa879a](https://github.com/luin/ioredis/commit/bfa879a))



<a name="2.4.2"></a>
## [2.4.2](https://github.com/luin/ioredis/compare/v2.4.1...v2.4.2) (2016-12-04)


### Bug Fixes

* handle error when creating tls connection ([904f433](https://github.com/luin/ioredis/commit/904f433))



<a name="2.4.1"></a>
## [2.4.1](https://github.com/luin/ioredis/compare/v2.4.0...v2.4.1) (2016-12-04)


### Performance Improvements

* by default call setNoDelay on the stream (#406) ([990a221](https://github.com/luin/ioredis/commit/990a221))



<a name="2.4.0"></a>
# [2.4.0](https://github.com/luin/ioredis/compare/v2.3.1...v2.4.0) (2016-09-24)


### Features

* Sentinel preferredSlaves option ([#370](https://github.com/luin/ioredis/issues/370)) ([6ddcc99](https://github.com/luin/ioredis/commit/6ddcc99))



<a name="2.3.1"></a>
## [2.3.1](https://github.com/luin/ioredis/compare/v2.3.0...v2.3.1) (2016-09-24)


### Bug Fixes

* prevent sentinel from getting duplicated nodes ([0338677](https://github.com/luin/ioredis/commit/0338677))



<a name="2.3.0"></a>
## [2.3.0](https://github.com/luin/ioredis/compare/v2.2.0...v2.3.0) (2016-08-11)


### Bug Fixes

* reject with general error in Redis#connect ([#354](https://github.com/luin/ioredis/issues/354)) ([8f7a436](https://github.com/luin/ioredis/commit/8f7a436))


### Features

* **cluster:** add lazy connect support ([#352](https://github.com/luin/ioredis/issues/352)) ([f1cadff](https://github.com/luin/ioredis/commit/f1cadff))



<a name="2.2.0"></a>
## [2.2.0](https://github.com/luin/ioredis/compare/v2.1.0...v2.2.0) (2016-06-28)


### Bug Fixes

* **cluster:** ensure node exists before being redirected via an ASK (#341) ([5d9d0d3](https://github.com/luin/ioredis/commit/5d9d0d3))

### Features

* **cluster:** add Cluster#quit() to quit cluster gracefully. (#339) ([68c4ccc](https://github.com/luin/ioredis/commit/68c4ccc)), closes [#315](https://github.com/luin/ioredis/issues/315)



<a name="2.1.0"></a>
## [2.1.0](https://github.com/luin/ioredis/compare/v2.0.1...v2.1.0) (2016-06-22)


### Bug Fixes

* remove unnecessary unhandled error warnings ([#322](https://github.com/luin/ioredis/issues/322)) ([a1ff2f6](https://github.com/luin/ioredis/commit/a1ff2f6))


### Features

* **sentinel:** update sentinels after getting master ([e3f14b2](https://github.com/luin/ioredis/commit/e3f14b2))


### Performance Improvements

* **cluster:** improve the performance of calculating slots ([#323](https://github.com/luin/ioredis/issues/323)) ([3ab4e8a](https://github.com/luin/ioredis/commit/3ab4e8a))



<a name="2.0.1"></a>
## [2.0.1](https://github.com/luin/ioredis/compare/v2.0.0...v2.0.1) (2016-06-01)

### Bug Fixes

* fix transaction with dropBufferSupport:true([47a2d9a](https://github.com/luin/ioredis/commit/47a2d9a))

<a name="2.0.0"></a>
## [2.0.0](https://github.com/luin/ioredis/compare/v2.0.0-rc4...v2.0.0) (2016-05-29)

Refer to [Breaking Changes between V1 and V2](https://github.com/luin/ioredis/wiki/Breaking-changes-between-v1-and-v2) for all breaking changes.

Changes since 2.0.0-rc4:

### Features

* include source and database in monitor events ([#308](https://github.com/luin/ioredis/issues/308)) ([a0d5b25](https://github.com/luin/ioredis/commit/a0d5b25))


### Performance Improvements

* improve the performance of checking flags ([#312](https://github.com/luin/ioredis/issues/312)) ([236da27](https://github.com/luin/ioredis/commit/236da27))


<a name="2.0.0-rc4"></a>
## [2.0.0-rc4](https://github.com/luin/ioredis/compare/v2.0.0-rc3...v2.0.0-rc4) (2016-05-08)


### Bug Fixes

* reconnect when ready check failed([3561fab](https://github.com/luin/ioredis/commit/3561fab))
* remove data handler when flushing command queue([b1c761c](https://github.com/luin/ioredis/commit/b1c761c))
* won't emit error again when password is wrong([dfdebfe](https://github.com/luin/ioredis/commit/dfdebfe))


### Features

* add dropBufferSupport option to improve the performance ([#293](https://github.com/luin/ioredis/issues/293))([1a8700c](https://github.com/luin/ioredis/commit/1a8700c))
* add support for Node.js v6 ([#295](https://github.com/luin/ioredis/issues/295))([a87f405](https://github.com/luin/ioredis/commit/a87f405))
* emit authentication related errors with "error" event([9dc25b4](https://github.com/luin/ioredis/commit/9dc25b4))
* print logs for unhandled error event([097fdbc](https://github.com/luin/ioredis/commit/097fdbc))


### BREAKING CHANGES

* Authentication related errors are emited with "error" event,
instead of "authError" event



<a name="2.0.0-rc3"></a>
## [2.0.0-rc3](https://github.com/luin/ioredis/compare/v2.0.0-rc2...v2.0.0-rc3) (2016-05-02)


### Bug Fixes

* fix wrong host not causing error ([25c300e](https://github.com/luin/ioredis/commit/25c300e)), closes [#287](https://github.com/luin/ioredis/issues/287)
* reconnect when getting fatal error (#292) ([1cf2ac1](https://github.com/luin/ioredis/commit/1cf2ac1))

### Features

* **deps:** upgrade redis-commands package ([df08250](https://github.com/luin/ioredis/commit/df08250))



<a name="2.0.0-rc2"></a>
## [2.0.0-rc2](https://github.com/luin/ioredis/compare/v2.0.0-rc1...v2.0.0-rc2) (2016-04-10)


### Bug Fixes

* **CLUSTER:** fix cluster not disconnected when called disconnect method (#281) ([91998e3](https://github.com/luin/ioredis/commit/91998e3)), closes [(#281](https://github.com/(/issues/281)
* **sentinel:** improve the error message when connection to sentinel is rejected ([3ca30d8](https://github.com/luin/ioredis/commit/3ca30d8)), closes [#280](https://github.com/luin/ioredis/issues/280)

### Features

* add stringNumbers option to return numbers as JavaScript strings (#282) ([2a33fc7](https://github.com/luin/ioredis/commit/2a33fc7)), closes [#273](https://github.com/luin/ioredis/issues/273)

<a name="2.0.0-rc1"></a>
## [2.0.0-rc1](https://github.com/luin/ioredis/compare/v2.0.0-alpha3...v2.0.0-rc1) (2016-03-18)

### Features

* **dependencies**: upgrade all dependencies to the newest version ([3fdafc8](https://github.com/luin/ioredis/commit/3fdafc8)).


<a name="2.0.0-alpha3"></a>
## [2.0.0-alpha3](https://github.com/luin/ioredis/compare/v2.0.0-alpha2...v2.0.0-alpha3) (2016-03-13)

### Bug Fixes

* **auth:** emit authError when the server requiring a password ([c5ca754](https://github.com/luin/ioredis/commit/c5ca754))

### Features

* **cluster:** add enableReadyCheck option for cluster ([b63cdc7](https://github.com/luin/ioredis/commit/b63cdc7))
* **cluster:** redirect on TRYAGAIN error ([b1a4b62](https://github.com/luin/ioredis/commit/b1a4b62))
* **cluster:** support update startupNodes in clusterRetryStrategy ([4a46766](https://github.com/luin/ioredis/commit/4a46766))
* **transaction:** transform replies of transactions ([e0b1883](https://github.com/luin/ioredis/commit/e0b1883)), closes [#158](https://github.com/luin/ioredis/issues/158)


### BREAKING CHANGES

  1. Reply transformers is supported inside transactions.
  2. `Pipeline#execBuffer()` is deprecated. Use `Pipeline#exec()` instead.

<a name="2.0.0-alpha2"></a>
## [2.0.0-alpha2](https://github.com/luin/ioredis/compare/v2.0.0-alpha1...v2.0.0-alpha2) (2016-02-29)


### Bug Fixes

* **cluster:** fix memory leaking in sendCommand method ([410af51](https://github.com/luin/ioredis/commit/410af51))

### Features

* **cluster:** add the option for a custom node selector in scaleReads ([6795b1e](https://github.com/luin/ioredis/commit/6795b1e))



<a name="2.0.0-alpha1"></a>
## [2.0.0-alpha1](https://github.com/luin/ioredis/compare/v1.15.0...v2.0.0-alpha1) (2016-02-10)


### Bug Fixes

* **cluster:** avoid command.reject being overwritten twice ([d0a0017](https://github.com/luin/ioredis/commit/d0a0017))
* **cluster:** fix not connecting to the unknown nodes ([0dcb768](https://github.com/luin/ioredis/commit/0dcb768))
* **cluster:** set retryDelayOnFailover from 2000ms to 200ms ([72fd804](https://github.com/luin/ioredis/commit/72fd804))

### Features

* **cluster:** support scaling reads to slaves ([98bdec2](https://github.com/luin/ioredis/commit/98bdec2)), closes [#170](https://github.com/luin/ioredis/issues/170)
* **redis:** support readonly mode for cluster ([0a4186e](https://github.com/luin/ioredis/commit/0a4186e))


### BREAKING CHANGES

* **cluster:** `Cluster#masterNodes` and `Cluster#nodes` is removed. Use `Cluster#nodes('masters')` and `Cluster#nodes('all')` instead.
* **cluster:** `Cluster#to()` is removed. Use `Promise.all(Cluster#nodes().map(function (node) {}))` instead.
* **cluster:** Option `readOnly` is removed. Check out `scaleReads` option.

<a name="1.15.1"></a>
## [1.15.1](https://github.com/luin/ioredis/compare/v1.15.0...v1.15.1) (2016-02-19)
* select db on connect event to prevent subscribe errors ([829bf26](https://github.com/luin/ioredis/commit/829bf26)), closes [#255](https://github.com/luin/ioredis/issues/255)

<a name="1.15.0"></a>
## [1.15.0](https://github.com/luin/ioredis/compare/v1.14.0...v1.15.0) (2016-01-31)


### Bug Fixes

* "MOVED" err not crashing process when slot was not assigned ([6974d4d](https://github.com/luin/ioredis/commit/6974d4d))
* remove extra typeof in .to cluster helper ([a7b0bfe](https://github.com/luin/ioredis/commit/a7b0bfe))

### Features

* revisit of .to(nodeGroup) command ([ba12e47](https://github.com/luin/ioredis/commit/ba12e47))



## v1.14.0 - January 4, 2016

* Support returning buffers for transactions ([#223](https://github.com/luin/ioredis/issues/223)).

## v1.13.2 - December 30, 2015

* Add argument transformer for msetnx to support Map ([#218](https://github.com/luin/ioredis/issues/218)).

## v1.13.1 - December 20, 2015

* Fix `mset` transformer not supporting keyPrefix ([#217](https://github.com/luin/ioredis/issues/217)).

## v1.13.0 - December 13, 2015

* [Cluster] Select a random node when the target node is closed.
* [Cluster] `maxRedirections` also works for `CLUSTERDOWN`.

## v1.12.2 - December 6, 2015

* [Cluster] Fix failover queue not being processed. [Shahar Mor](https://github.com/shaharmor).

## v1.12.1 - December 5, 2015

* [Cluster] Add queue support for failover and CLUSTERDOWN handling. [Shahar Mor](https://github.com/shaharmor).
* Emits "error" when connection is down for `scanStream` ([#199](https://github.com/luin/ioredis/issues/199)).

## v1.11.1 - November 26, 2015

* [Sentinel] Emits "error" when all sentinels are unreachable ([#200](https://github.com/luin/ioredis/issues/200)).

## v1.11.0 - November 19, 2015

* Emits "select" event when the database changed.
* [Cluster] Supports scanStream ([#175](https://github.com/luin/ioredis/issues/175)).
* Update debug module to 2.2.0
* Update bluebird module to 2.9.34

## v1.10.0 - October 24, 2015

* [Cluster] Support redis schema url.
* [Cluster] Support specifying password for each node.
* Add an option for setting connection name. [cgiovanacci](https://github.com/cgiovanacci).
* Switch to the previous db before re-subscribing channels.
* Listen to the "secureConnect" event when connect via TLS. [Jeffrey Jen](https://github.com/jeffjen).
* Improve parser performance.

## v1.9.1 - October 2, 2015

* Emits "authError" event when the password is wrong([#164](https://github.com/luin/ioredis/issues/164)).
* Fixed wrong debug output when using sentinels. [Colm Hally](https://github.com/ColmHally)
* Discard slave if flagged with s_down or o_down. [mtlima](https://github.com/mtlima)

## v1.9.0 - September 18, 2015

* Support TLS.
* Support reconnecting on the specified error.

## v1.8.0 - September 9, 2015

* Add keepAlive option(defaults to `true`).
* Fix compatible issues of Buffer with Node.js 4.0.

## v1.7.6 - September 1, 2015

* Fix errors when sending command to a failed cluster([#56](https://github.com/luin/ioredis/issues/56)).

## v1.7.5 - August 16, 2015

* Fix for allNodes array containing nodes not serving the specified slot. [henstock](https://github.com/henstock)

## v1.7.4 - August 13, 2015

* Restore the previous state before resending the unfulfilled commands. [Jay Merrifield](https://github.com/fracmak)
* Fix empty pipeline not resolving as empty array. [Philip Kannegaard Hayes](https://github.com/phlip9)

## v1.7.3 - August 3, 2015

* Handle watch-exec rollback correctly([#199](https://github.com/luin/ioredis/pull/119)). [Andrew Newdigate](https://github.com/suprememoocow)

## v1.7.2 - July 30, 2015

* Fix not running callback in pipeline custom command([#117](https://github.com/luin/ioredis/pull/117)). [Philip Kannegaard Hayes](https://github.com/phlip9)
* Fixes status debug message in case of Unix socket path([#114](https://github.com/luin/ioredis/pull/114)). [Thalis Kalfigkopoulos](https://github.com/tkalfigo)

## v1.7.1 - July 26, 2015

* Re-subscribe previous channels after reconnection([#110](https://github.com/luin/ioredis/pull/110)).

## v1.7.0 - July 23, 2015

* Support transparent key prefixing([#105](https://github.com/luin/ioredis/pull/105)). [Danny Guo](https://github.com/dguo)

## v1.6.1 - July 12, 2015

* Fix `Redis.Command` not being exported correctly([#100](https://github.com/luin/ioredis/issues/100)).

## v1.6.0 - July 11, 2015

* Add a streaming interface to `SCAN` commands.
* Support GEO commands.

## v1.5.12 - July 7, 2015

* Fix the order of received commands([#91](https://github.com/luin/ioredis/issues/91)).

## v1.5.11 - July 7, 2015

* Allow omitting callback in `exec`.

## v1.5.10 - July 6, 2015

* Add `send_command` method for compatibility([#90](https://github.com/luin/ioredis/issues/90)).

## v1.5.9 - July 4, 2015

* Fix connection error emitting before listening to `error` event([#80](https://github.com/luin/ioredis/issues/80)).

## v1.5.8 - July 3, 2015

* Fix `pmessage` gets `undefined` in cluster mode([#88](https://github.com/luin/ioredis/issues/88)). [Kris Linquist](https://github.com/klinquist)

## v1.5.7 - July 1, 2015

* Fix subscriptions lost after reconnection([#85](https://github.com/luin/ioredis/issues/85)).

## v1.5.6 - June 28, 2015

* Silent error when redis server has cluster support disabled([#82](https://github.com/luin/ioredis/issues/82)).

## v1.5.5 - June 25, 2015

* Fix storing wrong redis host internally.

## v1.5.4 - June 25, 2015

* Fix masterNodes not being removed correctly.

## v1.5.3 - June 24, 2015

* Fix sometimes monitor leads command queue error.

## v1.5.2 - June 24, 2015

* Fix `enableReadyCheck` is always `false` in monitor mode([#77](https://github.com/luin/ioredis/issues/77)).

## v1.5.1 - June 16, 2015

* Fix getting NaN db index([#74](https://github.com/luin/ioredis/issues/74)).

## v1.5.0 - June 13, 2015

* Uses double ended queue instead of Array for better performance.
* Resolves a bug with cluster where a subscribe is sent to a disconnected node([#63](https://github.com/luin/ioredis/pull/63)). [Ari Aosved](https://github.com/devaos).
* Adds ReadOnly mode for Cluster mode([#69](https://github.com/luin/ioredis/pull/69)). [Nakul Ganesh](https://github.com/luin/ioredis/pull/69).
* Adds `Redis.print`([#71](https://github.com/luin/ioredis/pull/71)). [Frank Murphy](https://github.com/frankvm04).

## v1.4.0 - June 3, 2015

* Continue monitoring after reconnection([#52](https://github.com/luin/ioredis/issues/52)).
* Support pub/sub in Cluster mode([#54](https://github.com/luin/ioredis/issues/54)).
* Auto-reconnect when none of startup nodes is ready([#56](https://github.com/luin/ioredis/issues/56)).

## v1.3.6 - May 22, 2015

* Support Node.js 0.10.16
* Fix unfulfilled commands being sent to the wrong db([#42](https://github.com/luin/ioredis/issues/42)).

## v1.3.5 - May 21, 2015

* Fix possible memory leak warning of Cluster.
* Stop reconnecting when disconnected manually.

## v1.3.4 - May 21, 2015

* Add missing Promise definition in node 0.10.x.

## v1.3.3 - May 19, 2015

* Fix possible memory leak warning.

## v1.3.2 - May 18, 2015

* The constructor of `pipeline`/`multi` accepts a batch of commands.

## v1.3.1 - May 16, 2015

* Improve the performance of sending commands([#35](https://github.com/luin/ioredis/issues/35)). [@AVVS](https://github.com/AVVS).

## v1.3.0 - May 15, 2015

* Support pipeline redirection in Cluster mode.

## v1.2.7 - May 15, 2015

* `Redis#connect` returns a promise.

## v1.2.6 - May 13, 2015

* Fix showFriendlyErrorStack not working in pipeline.

## v1.2.5 - May 12, 2015

* Fix errors when sending commands after connection being closed.

## v1.2.4 - May 9, 2015

* Try a random node when the target slot isn't served by the cluster.
* Remove `refreshAfterFails` option.
* Try random node when refresh slots.

## v1.2.3 - May 9, 2015

* Fix errors when `numberOfKeys` is `0`.

## v1.2.2 - May 8, 2015

* Add `retryDelayOnClusterDown` option to handle CLUSTERDOWN error.
* Fix `multi` commands sometimes doesn't return a promise.

## v1.2.1 - May 7, 2015

* Fix `sendCommand` sometimes doesn't return a promise.

## v1.2.0 - May 4, 2015

* Add `autoResendUnfulfilledCommands` option.

## v1.1.4 - May 3, 2015

* Support get built-in commands.

## v1.1.3 - May 2, 2015

* Fix buffer supporting in pipeline. [@AVVS](https://github.com/AVVS).

## v1.1.2 - May 2, 2015

* Fix error of sending command to wrong node when slot is 0.

## v1.1.1 - May 2, 2015

* Support Transaction and pipelining in cluster mode.

## v1.1.0 - May 1, 2015

* Support cluster auto reconnection.
* Add `maxRedirections` option to Cluster.
* Remove `roleRetryDelay` option in favor of `sentinelRetryStrategy`.
* Improve compatibility with node_redis.
* More stable sentinel connection.

## v1.0.13 - April 27, 2015

* Support SORT, ZUNIONSTORE and ZINTERSTORE in Cluster.

## v1.0.12 - April 27, 2015

* Support for defining custom commands in Cluster.
* Use native array instead of fastqueue for better performance.

## v1.0.11 - April 26, 2015

* Add `showFriendlyErrorStack` option for outputing friendly error stack.

## v1.0.10 - April 25, 2015

* Improve performance for calculating slots.

## v1.0.9 - April 25, 2015

* Support single node commands in cluster mode.

## v1.0.8 - April 25, 2015

* Add promise supports in Cluster.

## v1.0.7 - April 25, 2015

* Add `autoResubscribe` option to prevent auto re-subscribe.
* Add `Redis#end` for compatibility.
* Add `Redis.createClient`(was `Redis#createClient`).

## v1.0.6 - April 24, 2015

* Support setting connect timeout.
