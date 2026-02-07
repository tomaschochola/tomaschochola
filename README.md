# Tomáš Chochola

**Solution Architect & Lead Engineer**

This profile serves as the central registry for a proprietary architectural ecosystem engineered for high-availability environments.

The repositories hosted here represent a unified full-stack foundation where every component—from low-level libraries to complete project templates—is designed to function as a hardened architectural primitive. The focus is exclusively on **correctness**, **determinism**, and **zero-overhead performance**.

---

## The Ecosystem Registry

### 01. Architectural Foundations

_Strictly typed, dependency-free implementations of interoperability standards._

- [**php-splx**](https://github.com/tomaschochola/php-splx)
  The axiomatic foundation of the ecosystem. Zero-dependency extensions to the standard library providing hardened, strictly typed primitives.
- [**php-psr-3-logger**](https://github.com/tomaschochola/php-psr-3-logger)
  OTLP-ready structured logging implementation for modern observability pipelines.
- [**php-psr-7-http-message**](https://github.com/tomaschochola/php-psr-7-http-message)
  Immutable, strictly typed implementation of HTTP messages optimized for low memory footprint.
- [**php-psr-11-container**](https://github.com/tomaschochola/php-psr-11-container)
  Zero-magic dependency injection container enforcing explicit service definitions.
- [**php-psr-15-request-handlers**](https://github.com/tomaschochola/php-psr-15-request-handlers)
  Standardized middleware pipeline and request handler definitions.
- [**php-psr-16-simple-cache**](https://github.com/tomaschochola/php-psr-16-simple-cache)
  High-performance APCu caching layer for ephemeral data storage.
- [**php-psr-17-http-factory**](https://github.com/tomaschochola/php-psr-17-http-factory)
  Stateless factories for decoupling instantiation logic from implementation.
- [**php-psr-18-http-client**](https://github.com/tomaschochola/php-psr-18-http-client)
  Production-grade HTTP client wrapping cURL with robust error handling.
- [**php-psr-20-clock**](https://github.com/tomaschochola/php-psr-20-clock)
  Temporal abstraction for deterministic time testing and control.

### 02. Core Infrastructure

_The engine room of the ecosystem._

- [**php-quickmux**](https://github.com/tomaschochola/php-quickmux)
  The Alpine Linux of Routers. An ultra-low latency request dispatcher designed for microservices requiring O(1) routing performance.

### 03. Project Blueprints (Templates)

_Production-ready starting points with pre-configured DevSecOps, Docker Swarm, and CI/CD._

- [**php-template-mezzio**](https://github.com/tomaschochola/php-template-mezzio)
  Enterprise-grade middleware application structure for complex APIs.
- [**php-template-quickmux**](https://github.com/tomaschochola/php-template-quickmux)
  Minimalist microservice foundation for latency-critical applications.
- [**php-template-library**](https://github.com/tomaschochola/php-template-library)
  Standardized structure for developing strictly typed PHP packages.
- [**php-template-project**](https://github.com/tomaschochola/php-template-project)
  Generic, high-performance CLI/Worker environment foundation.

### 04. Quality Assurance Tooling

_Centralized enforcement of engineering standards._

- [**php-tooling-phpstan-config**](https://github.com/tomaschochola/php-tooling-phpstan-config)
  Maximum strictness static analysis configuration (PHP 8.5+).
- [**php-tooling-php-cs-fixer-config**](https://github.com/tomaschochola/php-tooling-php-cs-fixer-config)
  Opinionated codestyle enforcement for backend services.
- [**ts-tooling-eslint-config**](https://github.com/tomaschochola/ts-tooling-eslint-config)
  Strict static analysis ruleset for TypeScript and React ecosystems.
- [**ts-tooling-prettier-config**](https://github.com/tomaschochola/ts-tooling-prettier-config)
  Deterministic formatting standards for frontend codebases.

---

## Engineering Doctrine

This ecosystem operates under a strict set of axioms designed to eliminate technical debt before it is created.

1.  **Defensive Posture:** Trust no one. Validate every input. Verify every return value.
2.  **Immediate Termination:** Fail fast, fail loud. No silent error suppression.
3.  **Absolute Type Safety:** The runtime is treated as strictly typed. No mixed, no implicit casts.
4.  **Zero Dependency:** Rely on the standard library. External code is a liability, not an asset.

## Contact

### Tomáš Chochola

**Solution Architect and Lead Engineer**

This ecosystem represents a specific architectural vision. For inquiries regarding enterprise implementation, architectural consultation, or long-term strategic partnership, please utilize the direct communication channels listed below.

**Email**<br />
tomaschochola@tomaschochola.cz

**GitHub Profile**<br />
https://github.com/tomaschochola

**Sponsorship**<br />
https://github.com/sponsors/tomaschochola

---

<div align="center">
    <sub>
        Licensed under <strong>CC BY-ND 4.0</strong>. Designed for integrity. Built for production.
    </sub>
</div>
