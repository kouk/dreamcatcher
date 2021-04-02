Node-based service providing a lightweight API for generating JPEG/PNG and PDF representations of a web page, using headless Chrome and [Puppeteer](https://pptr.dev/).

## Quick Start

 * Install depencencies with `npm install`.
 * To install additional fonts in the built image, place them in a top-level `fonts` directory.
 * To start the server, `npm start`.

Consult the [documentation](https://persado.github.io/dreamcatcher/docs/features) for configuration options and usage.

## OpenTelemetry integration

By default opentelemetry is disabled, set the `ENABLE_OPENTELEMETRY`
environment variable to "true" to enable it.

Telemetry will be printed to the console by default however Jaeger export is
also supported by setting the `OTEL_EXPORTER_JAEGER_ENDPOINT` environment
variable to the URL of the Jaeger agent.
