# Awesome Fiber [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) with stars

<a href="https://gofiber.io">
  <picture alt="Fiber Logo" align="right" style="margin-right: 25px">
    <source height="75" media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/gofiber/docs/master/static/img/logo-dark.svg">
    <img height="75" alt="Fiber Logo" align="right" style="margin-right: 25px" src="https://raw.githubusercontent.com/gofiber/docs/master/static/img/logo.svg">
  </picture>
</a>

> **Fiber** is an [Express](https://github.com/expressjs/express) ⭐ 68,787 | 🐛 186 | 🌐 JavaScript | 📅 2026-02-14 inspired **web framework** built on top of [Fasthttp](https://github.com/valyala/fasthttp) ⭐ 23,264 | 🐛 109 | 🌐 Go | 📅 2026-02-20, the **fastest** HTTP engine for [Go](https://golang.org/doc/). Designed to **ease** things up for **fast** development with **zero memory allocation** and **performance** in mind.

A curated list of awesome Fiber middlewares, boilerplates, recipes, articles and tools. <br>

## Contents

<!--lint disable awesome-toc-->

<!--lint disable awesome-git-repo-age-->

* [⚙️ Middlewares](#%EF%B8%8F-middlewares)
  * [🧬 Core](#-core)
  * [🔗 External](#-external)
  * [💻 Contrib](#-contrib)
  * [🌱 Third Party](#-third-party)
* [🚧 Boilerplates](#-boilerplates)
* [📁 Recipes](#-recipes)
* [🛠️ Tools](#%EF%B8%8F-tools)
* [📖 Articles](#-articles)
* [📺 Videos](#-videos)
* [🤖 Benchmarks](#-benchmarks)

## ⚙️ Middlewares

Where to discover Fiber middlewares.

### 🧬 Core

List of middlewares that are included within the Fiber framework.

* [Adaptor](https://github.com/gofiber/fiber/tree/main/middleware/adaptor) ⭐ 39,243 | 🐛 43 | 🌐 Go | 📅 2026-02-20 - Converter for net/http handlers to/from Fiber request handlers.
* [BasicAuth](https://github.com/gofiber/fiber/tree/main/middleware/basicauth) ⭐ 39,243 | 🐛 43 | 🌐 Go | 📅 2026-02-20 - Basic auth middleware provides an HTTP basic authentication. It calls the next handler for valid credentials and 401 Unauthorized for missing or invalid credentials.
* [Cache](https://github.com/gofiber/fiber/tree/main/middleware/cache) ⭐ 39,243 | 🐛 43 | 🌐 Go | 📅 2026-02-20 - Intercept and cache responses.
* [Compress](https://github.com/gofiber/fiber/tree/main/middleware/compress) ⭐ 39,243 | 🐛 43 | 🌐 Go | 📅 2026-02-20 - Compression middleware for Fiber, it supports `deflate`, `gzip` and `brotli` by default.
* [CORS](https://github.com/gofiber/fiber/tree/main/middleware/cors) ⭐ 39,243 | 🐛 43 | 🌐 Go | 📅 2026-02-20 - Enable cross-origin resource sharing (CORS) with various options.
* [CSRF](https://github.com/gofiber/fiber/tree/main/middleware/csrf) ⭐ 39,243 | 🐛 43 | 🌐 Go | 📅 2026-02-20 - Protect from CSRF exploits.
* [Earlydata](https://github.com/gofiber/fiber/tree/main/middleware/earlydata) ⭐ 39,243 | 🐛 43 | 🌐 Go | 📅 2026-02-20 - Early data support for Fiber.
* [Encrypt Cookie](https://github.com/gofiber/fiber/tree/main/middleware/encryptcookie) ⭐ 39,243 | 🐛 43 | 🌐 Go | 📅 2026-02-20 - Encrypt middleware which encrypts cookie values.
* [EnvVar](https://github.com/gofiber/fiber/tree/main/middleware/envvar) ⭐ 39,243 | 🐛 43 | 🌐 Go | 📅 2026-02-20 - Expose environment variables with providing an optional config.
* [ETag](https://github.com/gofiber/fiber/tree/main/middleware/etag) ⭐ 39,243 | 🐛 43 | 🌐 Go | 📅 2026-02-20 - Lets caches be more efficient and save bandwidth, as a web server does not need to resend a full response if the content has not changed.
* [Expvar](https://github.com/gofiber/fiber/tree/main/middleware/expvar) ⭐ 39,243 | 🐛 43 | 🌐 Go | 📅 2026-02-20 - Serves runtime exposed variants in JSON format via its HTTP server.
* [Favicon](https://github.com/gofiber/fiber/tree/main/middleware/favicon) ⭐ 39,243 | 🐛 43 | 🌐 Go | 📅 2026-02-20 - Ignore favicon from logs or serve from memory if a file path is provided.
* [Healthcheck](https://github.com/gofiber/fiber/tree/main/middleware/healthcheck) ⭐ 39,243 | 🐛 43 | 🌐 Go | 📅 2026-02-20 - Adds health-check endpoints for readiness and liveness probes.
* [Helmet](https://github.com/gofiber/fiber/tree/main/middleware/helmet) ⭐ 39,243 | 🐛 43 | 🌐 Go | 📅 2026-02-20 - Helps secure your apps by setting various HTTP headers.
* [Idempotency](https://github.com/gofiber/fiber/tree/main/middleware/idempotency) ⭐ 39,243 | 🐛 43 | 🌐 Go | 📅 2026-02-20 - Enables fault-tolerant APIs when duplicate requests occur.
* [Keyauth](https://github.com/gofiber/fiber/tree/main/middleware/keyauth) ⭐ 39,243 | 🐛 43 | 🌐 Go | 📅 2026-02-20 - Key auth middleware provides a key based authentication.
* [Limiter](https://github.com/gofiber/fiber/tree/main/middleware/limiter) ⭐ 39,243 | 🐛 43 | 🌐 Go | 📅 2026-02-20 - Rate-limiting middleware. Use to limit repeated requests to public APIs and/or endpoints such as password reset.
* [Logger](https://github.com/gofiber/fiber/tree/main/middleware/logger) ⭐ 39,243 | 🐛 43 | 🌐 Go | 📅 2026-02-20 - HTTP request/response logger.
* [Pprof](https://github.com/gofiber/fiber/tree/main/middleware/pprof) ⭐ 39,243 | 🐛 43 | 🌐 Go | 📅 2026-02-20 - Serves runtime profiling data in the format expected by the pprof visualization tool.
* [Proxy](https://github.com/gofiber/fiber/tree/main/middleware/proxy) ⭐ 39,243 | 🐛 43 | 🌐 Go | 📅 2026-02-20 - Allows you to proxy requests to a multiple servers.
* [Recover](https://github.com/gofiber/fiber/tree/main/middleware/recover) ⭐ 39,243 | 🐛 43 | 🌐 Go | 📅 2026-02-20 - Recovers from panics anywhere in the stack chain and hands control to the centralized ErrorHandler.
* [Redirect](https://github.com/gofiber/fiber/tree/main/middleware/redirect) ⭐ 39,243 | 🐛 43 | 🌐 Go | 📅 2026-02-20 - Handles HTTP redirects in Fiber.
* [RequestID](https://github.com/gofiber/fiber/tree/main/middleware/requestid) ⭐ 39,243 | 🐛 43 | 🌐 Go | 📅 2026-02-20 - Adds a requestid to every request.
* [Responsetime](https://github.com/gofiber/fiber/tree/main/middleware/responsetime) ⭐ 39,243 | 🐛 43 | 🌐 Go | 📅 2026-02-20 - Adds an `X-Response-Time` header to responses.
* [Rewrite](https://github.com/gofiber/fiber/tree/main/middleware/rewrite) ⭐ 39,243 | 🐛 43 | 🌐 Go | 📅 2026-02-20 - Rewrites the URL path based on provided rules for backward compatibility or cleaner links.
* [Session](https://github.com/gofiber/fiber/tree/main/middleware/session) ⭐ 39,243 | 🐛 43 | 🌐 Go | 📅 2026-02-20 - Provides session management. NOTE: This middleware uses our Storage package.
* [Skip](https://github.com/gofiber/fiber/tree/main/middleware/skip) ⭐ 39,243 | 🐛 43 | 🌐 Go | 📅 2026-02-20 - Skips a wrapped handler when a predicate is true.
* [Static](https://github.com/gofiber/fiber/tree/main/middleware/static) ⭐ 39,243 | 🐛 43 | 🌐 Go | 📅 2026-02-20 - Serves static files from a local or custom file system.
* [Timeout](https://github.com/gofiber/fiber/tree/main/middleware/timeout) ⭐ 39,243 | 🐛 43 | 🌐 Go | 📅 2026-02-20 - Adds a max time for a request and forwards to ErrorHandler if it is exceeded.

### 🔗 External

List of externally hosted middleware modules and maintained by the [Fiber team](https://github.com/orgs/gofiber/people).

* [storage](https://github.com/gofiber/storage) ⭐ 321 | 🐛 8 | 🌐 Go | 📅 2026-02-20 - Premade storage drivers that implement the Storage interface, designed to be used with various Fiber middlewares.
* [template](https://github.com/gofiber/template) ⭐ 310 | 🐛 18 | 🌐 Go | 📅 2026-02-16 - This package contains 8 template engines that can be used with Fiber v1.10.x Go version 1.13 or higher is required.

### ‍💻 Contrib

List of third party middlewares and maintained by the Fiber team and community.

* [casbin](https://github.com/gofiber/contrib/tree/main/v3/casbin) ⭐ 288 | 🐛 29 | 🌐 Go | 📅 2026-02-20 - Authorization middleware for Fiber powered by Casbin.
* [circuitbreaker](https://github.com/gofiber/contrib/tree/main/v3/circuitbreaker) ⭐ 288 | 🐛 29 | 🌐 Go | 📅 2026-02-20 - Circuit breaker middleware for Fiber.
* [fgprof](https://github.com/gofiber/contrib/tree/main/v3/fgprof) ⭐ 288 | 🐛 29 | 🌐 Go | 📅 2026-02-20 - Fiber profiling support via fgprof.
* [hcaptcha](https://github.com/gofiber/contrib/tree/main/v3/hcaptcha) ⭐ 288 | 🐛 29 | 🌐 Go | 📅 2026-02-20 - Bot-protection middleware using hCaptcha.
* [i18n](https://github.com/gofiber/contrib/tree/main/v3/i18n) ⭐ 288 | 🐛 29 | 🌐 Go | 📅 2026-02-20 - Internationalization middleware built on go-i18n.
* [jwt](https://github.com/gofiber/contrib/tree/main/v3/jwt) ⭐ 288 | 🐛 29 | 🌐 Go | 📅 2026-02-20 - JSON Web Token (JWT) auth middleware.
* [loadshed](https://github.com/gofiber/contrib/tree/main/v3/loadshed) ⭐ 288 | 🐛 29 | 🌐 Go | 📅 2026-02-20 - Load-shedding middleware to protect Fiber services under pressure.
* [monitor](https://github.com/gofiber/contrib/tree/main/v3/monitor) ⭐ 288 | 🐛 29 | 🌐 Go | 📅 2026-02-20 - Server metrics monitor middleware for Fiber.
* [newrelic](https://github.com/gofiber/contrib/tree/main/v3/newrelic) ⭐ 288 | 🐛 29 | 🌐 Go | 📅 2026-02-20 - New Relic instrumentation support for Fiber.
* [opa](https://github.com/gofiber/contrib/tree/main/v3/opa) ⭐ 288 | 🐛 29 | 🌐 Go | 📅 2026-02-20 - Open Policy Agent (OPA) middleware support for Fiber.
* [otel](https://github.com/gofiber/contrib/tree/main/v3/otel) ⭐ 288 | 🐛 29 | 🌐 Go | 📅 2026-02-20 - OpenTelemetry middleware support for Fiber.
* [paseto](https://github.com/gofiber/contrib/tree/main/v3/paseto) ⭐ 288 | 🐛 29 | 🌐 Go | 📅 2026-02-20 - Platform-Agnostic Security Tokens (PASETO) auth middleware.
* [sentry](https://github.com/gofiber/contrib/tree/main/v3/sentry) ⭐ 288 | 🐛 29 | 🌐 Go | 📅 2026-02-20 - Error monitoring and reporting integration for Fiber with Sentry.
* [socketio](https://github.com/gofiber/contrib/tree/main/v3/socketio) ⭐ 288 | 🐛 29 | 🌐 Go | 📅 2026-02-20 - Socket.IO-inspired WebSocket wrapper middleware for Fiber.
* [swaggo](https://github.com/gofiber/contrib/tree/main/v3/swaggo) ⭐ 288 | 🐛 29 | 🌐 Go | 📅 2026-02-20 - Middleware for serving Swag-generated API docs in Fiber.
* [swaggerui](https://github.com/gofiber/contrib/tree/main/v3/swaggerui) ⭐ 288 | 🐛 29 | 🌐 Go | 📅 2026-02-20 - Swagger UI middleware for serving OpenAPI specs in Fiber.
* [testcontainers](https://github.com/gofiber/contrib/tree/main/v3/testcontainers) ⭐ 288 | 🐛 29 | 🌐 Go | 📅 2026-02-20 - Service implementation for integrating Testcontainers with Fiber.
* [WebSocket](https://github.com/gofiber/contrib/tree/main/v3/websocket) ⭐ 288 | 🐛 29 | 🌐 Go | 📅 2026-02-20 - Fasthttp-based WebSocket integration for Fiber with `fiber.Ctx` support.
* [zap](https://github.com/gofiber/contrib/tree/main/v3/zap) ⭐ 288 | 🐛 29 | 🌐 Go | 📅 2026-02-20 - Logging middleware support for Fiber with Zap.
* [zerolog](https://github.com/gofiber/contrib/tree/main/v3/zerolog) ⭐ 288 | 🐛 29 | 🌐 Go | 📅 2026-02-20 - Logging middleware support for Fiber with Zerolog.

### 🌱 Third Party

List of middlewares that are created by the Fiber community.

* [darkweak/souin](https://github.com/darkweak/souin) ⭐ 942 | 🐛 44 | 🌐 Go | 📅 2026-02-20 - HTTP cache, RFC compliant, alternative to Varnish available as a middleware.
* [newrelic/go-agent](https://github.com/newrelic/go-agent/tree/master/v3/integrations/nrfiber) ⭐ 829 | 🐛 66 | 🌐 Go | 📅 2026-02-18 - Official New Relic middleware for Fiber that manages instrumentation for New Relic monitoring.
* [elastic/apmfiber](https://github.com/elastic/apm-agent-go/tree/master/module/apmfiber) ⭐ 425 | 🐛 104 | 🌐 Go | 📅 2026-02-09 - APM Agent for Go Fiber.
* [ansrivas/fiberprometheus](https://github.com/ansrivas/fiberprometheus) ⭐ 208 | 🐛 0 | 🌐 Go | 📅 2026-02-11 - Prometheus middleware for gofiber.
* [airbrake/gobrake](https://github.com/airbrake/gobrake/tree/master/examples/fiber) ⭐ 107 | 🐛 12 | 🌐 Go | 📅 2025-03-18 - An Airbrake middleware that reports performance data (route stats).
* [samber/slog-fiber](https://github.com/samber/slog-fiber) ⭐ 94 | 🐛 3 | 🌐 Go | 📅 2026-02-14 - A logger middleware that uses Go slog library.
* [oaswrap/fiberopenapi](https://github.com/oaswrap/spec/tree/main/adapter/fiberopenapi) ⭐ 92 | 🐛 3 | 🌐 Go | 📅 2025-11-05 - Fiber adapter for OpenAPI 3.x specification generation with automatic route documentation.
* [sacsand/gofiber-firebaseauth](https://github.com/sacsand/gofiber-firebaseauth) ⭐ 26 | 🐛 2 | 🌐 Go | 📅 2022-02-20 - Fiber Firebase Auth Middleware.
* [joffref/opa-middleware](https://github.com/Joffref/opa-middleware) ⭐ 22 | 🐛 2 | 🌐 Go | 📅 2024-03-14 - Provides an OPA middleware integration for fiber.
* [witer33/fiberpow](https://github.com/witer33/fiberpow) ⭐ 15 | 🐛 2 | 🌐 Go | 📅 2026-02-03 - Anti DDoS/Bot Middleware with a customizable Proof Of Work challenge.
* [shareed2k/fiber\_limiter](https://github.com/shareed2k/fiber_limiter) ⭐ 14 | 🐛 0 | 🌐 Go | 📅 2020-05-31 - Limiter using Redis as store for rate limit with two algorithms for choosing sliding window, gcra leaky bucket.
* [Idan-Fishman/fiber-bind](https://github.com/Idan-Fishman/fiber-bind) ⭐ 14 | 🐛 5 | 🌐 Go | 📅 2024-11-25 - Request schema validator middleware that validates sources such as the request body, query string parameters, route parameters and even form files.
* [shareed2k/fiber\_tracing](https://github.com/shareed2k/fiber_tracing) ⭐ 12 | 🐛 4 | 🌐 Go | 📅 2024-03-27 - Middleware trace requests on Fiber framework with OpenTracing API.
* [aschenmaker/fiber-health-check](https://github.com/aschenmaker/fiber-health-check) ⭐ 10 | 🐛 0 | 🌐 Go | 📅 2021-06-03 - Health-check middleware support health-check for Fiber️ framework.
* [mikhail-bigun/fiberlogrus](https://github.com/mikhail-bigun/fiberlogrus) ⭐ 10 | 🐛 0 | 🌐 Go | 📅 2025-03-11 - A logger middleware that uses logrus and its structured logging features.
* [zeiss/fiber-authz](https://github.com/ZEISS/fiber-authz) ⭐ 7 | 🐛 0 | 🌐 Go | 📅 2026-02-10 - A middleware to secure routes in Fiber with a defined RBAC model.
* [apitally/apitally-go](https://github.com/apitally/apitally-go) ⭐ 7 | 🐛 6 | 🌐 Go | 📅 2026-02-16 - Simple API monitoring tool for Fiber. Tracks API usage, errors, and performance, and includes request logging and alerting features.
* [zeiss/fiber-goth](https://github.com/ZEISS/fiber-goth) ⭐ 5 | 🐛 0 | 🌐 Go | 📅 2026-02-10 - Simple middleware to integrate authentication to your Fiber applications.
* [zeiss/fiber-htmx](https://github.com/ZEISS/fiber-htmx) ⭐ 5 | 🐛 1 | 🌐 CSS | 📅 2026-02-20 - A middleware for using HTMX in Fiber.
* [eozer/fiber\_ldapauth](https://github.com/eozer/fiber_ldapauth) ⭐ 4 | 🐛 5 | 🌐 Go | 📅 2024-05-13 - LDAP Authentication Middleware for Fiber.
* [streamerd/fibergun](https://github.com/streamerd/fibergun) ⭐ 4 | 🐛 0 | 🌐 Go | 📅 2024-11-22 - A GunDB middleware for Fiber. Enables easy integration of GunDB, a decentralized database.
* [beyer-stefan/gofiber-minifier](https://github.com/beyer-stefan/gofiber-minifier) ⚠️ Archived - Minifying middleware for HTML5, CSS3, and JavaScript.
* [vladfr/fiber-servertiming](https://github.com/vladfr/fiber-servertiming) ⭐ 2 | 🐛 0 | 🌐 Go | 📅 2022-10-31 - A middleware to add Server-Timing headers based on the W3C Server-Timing Spec.
* [jsorb84/ssefiber](https://github.com/jsorb84/ssefiber) ⭐ 2 | 🐛 0 | 🌐 Go | 📅 2024-03-15 - A basic SSE Implementation for Fiber.
* [DavidHoenisch/fiber-coraza](https://github.com/DavidHoenisch/fiber-coraza) ⭐ 1 | 🐛 0 | 🌐 Go | 📅 2026-02-10 - Coraza WAF middleware for Fiber, providing web application firewall protection with ModSecurity-compatible rules.
* [narmadaweb/limiter](https://github.com/narmadaweb/limiter) ⭐ 1 | 🐛 7 | 🌐 Go | 📅 2026-02-16 - A high-performance Redis-backed rate limiter middleware for Fiber, supporting fixed window, sliding window, and token bucket algorithms.
* [narmadaweb/gonify](https://github.com/narmadaweb/gonify) ⭐ 1 | 🐛 2 | 🌐 Go | 📅 2026-02-05 - Fiber Minifying middleware for HTML5, CSS3, JavaScript, Json, XML and SVG.
* [rodrigoodhin/fiper](https://gitlab.com/rodrigoodhin/fiper) - FiPer is a library that provides Fiber with Role Based Access Control (RBAC) using JWT and with database persistence using two ORM libraries are supported: Gorm and Bun.

## 🚧 Boilerplates

Premade boilerplates for Fiber.

* [create-go-app/fiber-go-template](https://github.com/create-go-app/fiber-go-template) ⭐ 1,102 | 🐛 6 | 🌐 Go | 📅 2026-02-19 - Fiber backend template for Create Go App CLI.
* [gofiber/boilerplate](https://github.com/gofiber/boilerplate) ⭐ 494 | 🐛 0 | 🌐 Go | 📅 2026-02-16 - Official fiber boilerplate.
* [sujit-baniya/fiber-boilerplate](https://github.com/sujit-baniya/fiber-boilerplate) ⭐ 433 | 🐛 2 | 🌐 Go | 📅 2025-09-24 - Boilerplate on the top of fiber web framework with many middlewares and features.
* [fiber-boilerplate](https://github.com/thomasvvugt/fiber-boilerplate) ⭐ 287 | 🐛 11 | 🌐 Go | 📅 2023-03-04 - A boilerplate for the Fiber web framework.
* [GalvinGao/gofiber-template](https://github.com/GalvinGao/gofiber-template) ⭐ 131 | 🐛 12 | 🌐 Go | 📅 2026-02-11 - A production-ready, container-first opinionated gofiber project template. Config by envvars, DI by go.uber.org/fx, Database by uptrace/bun, with out-of-the-box MVC folder structure and CI/CD support.
* [efectn/fiber-boilerplate](https://github.com/efectn/fiber-boilerplate) ⭐ 84 | 🐛 5 | 🌐 Go | 📅 2023-03-27 - Simple and scalable boilerplate to build powerful and organized REST projects with Fiber.
* [sebajax/go-vertical-slice-architecture](https://github.com/sebajax/go-vertical-slice-architecture) ⭐ 51 | 🐛 8 | 🌐 Go | 📅 2024-02-25 - Vertical Slice Architecture code archetype using Fiber and Uber dig. A maintainable, and scalable code organization.
* [embedmode/fiberseed](https://github.com/embedmode/fiberseed) ⭐ 40 | 🐛 1 | 🌐 Go | 📅 2021-05-04 - Fiber boilerplate api with many middlewares.
* [goravel/fiber](https://github.com/goravel/fiber) ⭐ 28 | 🐛 1 | 🌐 Go | 📅 2026-02-16 - Laravel similar boilerplate with support for Fiber.
* [mikhail-bigun/go-app-template](https://github.com/mikhail-bigun/go-app-template) ⭐ 20 | 🐛 0 | 🌐 Go | 📅 2023-11-07 - Clean architecture Go application boilerplate with enriched Fiber implementation.
* [amrebada/go-modules](https://github.com/amrebada/go-modules) ⭐ 15 | 🐛 0 | 🌐 Go | 📅 2025-10-01 - Nest JS like structure for Go Fiber.
* [felipeafonso/go-htmx-starter](https://github.com/FelipeAfonso/go-htmx-starter) ⭐ 4 | 🐛 1 | 🌐 Go | 📅 2025-03-19 - A front-end opinionated boilerplate for Go + HTMX development, using Tailwind and Vite for Bundling and Hot Reloading.
* [go-rat/fiber-skeleton](https://github.com/go-rat/fiber-skeleton) ⭐ 3 | 🐛 2 | 🌐 Go | 📅 2026-02-19 - Fiber skeleton to powers web projects, support wire-based dependency injection.
* [ingeniousambivert/fiber-bootstrapped](https://github.com/ingeniousambivert/fiber-bootstrapped) ⭐ 2 | 🐛 0 | 🌐 Go | 📅 2024-02-23 - A toolkit for Go projects embracing a service-centric architecture, inspired by the principles of FeathersJS.

## 📁 Recipes

Recipes for Fiber.

* [gofiber/recipes](https://github.com/gofiber/recipes) ⭐ 3,427 | 🐛 14 | 🌐 Go | 📅 2026-02-20 - Official Fiber cookbook.
* [koddr/tutorial-go-fiber-rest-api](https://github.com/koddr/tutorial-go-fiber-rest-api) ⭐ 398 | 🐛 3 | 🌐 Go | 📅 2026-02-09 - Tutorial for building a restful api with fiber.
* [alpody/golang-fiber-realworld-example-app](https://github.com/alpody/golang-fiber-realworld-example-app) ⭐ 146 | 🐛 1 | 🌐 Go | 📅 2025-11-20 - Example real world backend API built with Fiber, Gorm, Swagger.
* [firebase007/go-rest-api-with-fiber](https://github.com/firebase007/go-rest-api-with-fiber) ⭐ 58 | 🐛 1 | 🌐 Go | 📅 2020-06-11 - Demo project with fiber, logging, basicAuth and postgresql.
* [EricLau1/go-fiber-auth-api](https://github.com/EricLau1/go-fiber-auth-api) ⭐ 55 | 🐛 1 | 🌐 Go | 📅 2021-02-14 - Golang Authentication API with Fiber MongoDB and JWT.
* [chawk/go\_fiber\_quickstart](https://github.com/chawk/go_fiber_quickstart) ⭐ 18 | 🐛 0 | 🌐 Go | 📅 2020-08-01 - Fiber quick start example project.
* [paundraP/golang-starter-template](https://github.com/paundraP/Go-Starter-Template) ⭐ 6 | 🐛 0 | 🌐 Go | 📅 2025-04-02 - Golang REST API with authentication, authorization, and integrated payment gateway support.
* [kiyonlin/fiblar-demo](https://github.com/kiyonlin/fiblar-demo) ⭐ 3 | 🐛 25 | 🌐 JavaScript | 📅 2023-01-06 - Fiber v1 + angular demo.

## 🛠️ Tools

Several tools to make Fiber usage easier.

* [deepmap/oapi-codegen](https://github.com/deepmap/oapi-codegen) ⭐ 8,085 | 🐛 621 | 🌐 Go | 📅 2026-02-21 - Generate Go client and server boilerplate from OpenAPI 3 specifications.
* [Alibaba/opentelemetry-go-auto-instrumentation](https://github.com/alibaba/opentelemetry-go-auto-instrumentation) ⭐ 786 | 🐛 36 | 🌐 Go | 📅 2026-02-11 - A tool to monitor fiber application without changing any code with OpenTelemetry APIs.
* [go-dawn/dawn](https://github.com/go-dawn/dawn) ⭐ 18 | 🐛 5 | 🌐 Go | 📅 2023-03-27 - Dawn is an opinionated web framework that provides rapid development capabilities which on top of Fiber.
* [tompston/gomakeme](https://github.com/tompston/gomakeme) ⭐ 10 | 🐛 0 | 🌐 Go | 📅 2022-02-21 - Generate boilerplate + endpoints for Fiber or Gin REST APIs.
* [ryanbekhen/feserve](https://github.com/ryanbekhen/feserve) ⭐ 9 | 🐛 4 | 🌐 Go | 📅 2025-11-27 - Feserve is a lightweight application or Docker image to serve frontend and load balancer applications.

## 📖 Articles

Articles about Fiber written by the community.

* [Working with middlewares and boilerplates](https://dev.to/koddr/go-fiber-by-examples-working-with-middlewares-and-boilerplates-3p0m)
* [Testing the application](https://dev.to/koddr/go-fiber-by-examples-testing-the-application-1ldf)
* [Delving into built-in functions](https://dev.to/koddr/go-fiber-by-examples-delving-into-built-in-functions-1p3k)
* [Go Fiber by Examples: How can the Fiber Web Framework be useful?](https://dev.to/koddr/go-fiber-by-examples-how-can-the-fiber-web-framework-be-useful-487a)
* [Build a RESTful API on Go: Fiber, PostgreSQL, JWT and Swagger docs in isolated Docker containers](https://dev.to/koddr/build-a-restful-api-on-go-fiber-postgresql-jwt-and-swagger-docs-in-isolated-docker-containers-475j)
* [Getting started with Fiber](https://dev.to/fenny/getting-started-with-fiber-36b6)
* [Building an Express-style API in Go with Fiber](https://blog.logrocket.com/express-style-api-go-fiber/)
* [Fiber v1.9.6 How to improve performance by 817% and stay fast, flexible and friendly?](https://dev.to/koddr/fiber-v1-9-5-how-to-improve-performance-by-817-and-stay-fast-flexible-and-friendly-2dp6)
* [Create a travel list app with Go, Fiber, Angular, MongoDB and Google Cloud Secret Manager](https://blog.yongweilun.me/create-a-travel-list-app-with-go-fiber-angular-mongodb-and-google-cloud-secret-manager-ck9fgxy0p061pcss1xt1ubu8t)
* [Building a Basic REST API in Go using Fiber](https://tutorialedge.net/golang/basic-rest-api-go-fiber/)
* [Creating Fast APIs In Go Using Fiber](https://dev.to/jozsefsallai/creating-fast-apis-in-go-using-fiber-59m9)
* [Is switching from Express to Fiber worth it?](https://dev.to/koddr/are-sure-what-your-lovely-web-framework-running-so-fast-2jl1)
* [Fiber v1.8. What's new, updated and re-thinked?](https://dev.to/koddr/fiber-v1-8-what-s-new-updated-and-re-thinked-339h)
* [Fiber released v1.7! What's new and is it still fast, flexible and friendly?](https://dev.to/koddr/fiber-v2-is-out-now-what-s-new-and-is-he-still-fast-flexible-and-friendly-3ipf)
* [Welcome to Fiber — an Express.js styled web framework written in Go with ❤️](https://dev.to/koddr/welcome-to-fiber-an-express-js-styled-fastest-web-framework-written-with-on-golang-497)
* [Blazing Fast Unit Tests - Fiber/fasthttp/http Internals](https://medium.com/trendyol-tech/golang-blazing-fast-unit-tests-fiber-fasthttp-http-internals-and-optimizing-http-server-tests-bbd1fe7b944b)
* [Building Microservices in Go : Part 1 - Project Setup, Dockerization](https://saadfarhan124.medium.com/building-microservices-in-go-part-1-e7e58893bc5e)
* [Building Microservices in Go : Part 2 - Live Reload](https://saadfarhan124.medium.com/building-microservices-in-go-part-2-f9c6c535805c)
* [Building Microservices in Go : Part 3 - Database, Models, Migrations](https://saadfarhan124.medium.com/building-microservices-in-go-part-3-database-models-migrations-a4455121bb11)
* [Build a REST API from scratch with Go, Docker & PostgreSQL](https://dev.to/divrhino/build-a-rest-api-from-scratch-with-go-and-docker-3o54)
* [Build a fullstack app with Go Fiber, Docker, and PostgreSQL](https://dev.to/divrhino/build-a-fullstack-app-with-go-fiber-docker-and-postgres-1jg6)
* [Create a CRUD app with Go Fiber, Docker, and PostgreSQL](https://dev.to/divrhino/create-a-crud-app-with-go-fiber-docker-and-postgres-47e3)

## 📺 Videos

Video tutorials created by the community about Fiber.

* [Is Fiber the best Go web framework? Better than Gin?](https://youtu.be/10miByMOGfY)

## 🤖 Benchmarks

Several benchmarks to compare Fiber with other frameworks.

* [TechEmpower](https://www.techempower.com/benchmarks/#section=data-r20\&hw=ph\&test=json) - Project provides performance measures across a wide field of web application frameworks.
* [web-frameworks-benchmark](https://web-frameworks-benchmark.netlify.app/result) - Project aims to measure the differences between the various programming language frameworks.
* [go-web-framework-benchmark](https://github.com/smallnest/go-web-framework-benchmark) ⭐ 2,137 | 🐛 4 | 🌐 Go | 📅 2025-01-17 - This benchmark suite aims to compare the performance of Go web frameworks.

### 👍 Contributing

Contribution guidelines can be found on [CONTRIBUTING.md](https://github.com/gofiber/awesome-fiber/blob/master/CONTRIBUTING.md) ⭐ 787 | 🐛 0 | 📅 2026-02-08
