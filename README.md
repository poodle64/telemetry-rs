# telemetry-rs

One call installs a household Rust process's telemetry: `tracing` to stderr for the developer, allow-listed OTLP/HTTP logs and OTLP traces to the household front door. Configured by the standard `OTEL_EXPORTER_OTLP_*` variables plus one helper variable for the bearer; local-only when the endpoint is unset.

Consumed as a tagged git dependency. Contract: `rules-library/platform/telemetry.md`; wiring: `docs/master/reference/guide-telemetry.md` §Rust.
