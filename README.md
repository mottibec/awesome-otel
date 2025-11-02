# Awesome OpenTelemetry Side Projects

A curated list of awesome OpenTelemetry-related side projects and tools.

## Contents

### Collectors & Configuration
- [pavolloffay/opentelemetry-collector-config-schema](https://github.com/pavolloffay/opentelemetry-collector-config-schema) - OpenTelemetry collector config schema in JSON

### Instrumentation & Extensions
- [fastify/otel](https://github.com/fastify/otel) - Auto-instrumentation plugin for the Fastify (Node.js) web framework; generates OTEL spans and metrics for Fastify apps
- [howardyoo/airflow_otel_provider](https://github.com/howardyoo/airflow_otel_provider) - Apache Airflow OTEL Provider: hooks and listeners so Airflow DAG tasks emit OpenTelemetry traces, metrics, and logs
- [justindsmith/opentelemetry-instrumentations-js](https://github.com/justindsmith/opentelemetry-instrumentations-js) - Community-maintained collection of JavaScript instrumentation libraries (outside the official contrib) for popular frameworks and libraries

### MCP (Model Context Protocol) Integration
- [austinlparker/otel-mcp](https://github.com/austinlparker/otel-mcp) - Experimental Model Context Protocol (MCP) extension and connector for the OpenTelemetry Collector
- [liatrio-labs/otel-instrumentation-mcp](https://github.com/liatrio-labs/otel-instrumentation-mcp) - Framework for instrumenting Model Context Protocol (MCP) systems with OpenTelemetry
- [mottibec/otelcol-mcp](https://github.com/mottibec/otelcol-mcp) - The OTEL MCP Server: an OpenTelemetry Collector component to provide dynamic configuration via MCP
- [pavolloffay/opentelemetry-mcp-server](https://github.com/pavolloffay/opentelemetry-mcp-server) - Reference MCP server for OpenTelemetry, enabling LLMs or other systems to serve Collector configs via MCP
- [theharithsa/opentelemetry-instrumentation-mcp](https://github.com/theharithsa/opentelemetry-instrumentation-mcp) - TypeScript auto-instrumentation for the MCP SDK: collects telemetry from MCP-based apps with zero configuration

### CLI Tools & Utilities
- [CtrlSpice/otel-desktop-viewer](https://github.com/CtrlSpice/otel-desktop-viewer) - A Go-based OpenTelemetry Collector + TUI viewer: receive and visualize trace data locally (without sending to an external backend)
- [dell/opentelemetry-cli](https://github.com/dell/opentelemetry-cli) - Human-friendly OpenTelemetry CLI (Python) to craft and send telemetry (spans/metrics) via OTLP
- [equinix-labs/otel-cli](https://github.com/equinix-labs/otel-cli) - A Go-based CLI for sending OpenTelemetry spans from shell scripts (OTLP exporter)
- [krzko/run-with-telemetry](https://github.com/krzko/run-with-telemetry) - GitHub Action to run commands with OpenTelemetry instrumentation, exporting trace data for CI/CD pipelines
- [krzko/setup-telemetry](https://github.com/krzko/setup-telemetry) - GitHub Action to set up deterministic OpenTelemetry trace IDs and traceparent headers for workflow telemetry
- [serkan-ozal/otel-cli](https://github.com/serkan-ozal/otel-cli) - Node.js CLI tool to send OpenTelemetry traces to an external OTLP endpoint

### Visualization & Dashboards
- [cyrille-leclerc/opentelemetry-service-dashboard](https://github.com/cyrille-leclerc/opentelemetry-service-dashboard) - Grafana dashboard templating for monitoring OpenTelemetry services
- [jack5341/otelmap](https://github.com/jack5341/otelmap) - Generates service dependency maps (visualizations) from OpenTelemetry trace data
- [monitoringartist/opentelemetry-collector-monitoring](https://github.com/monitoringartist/opentelemetry-collector-monitoring) - Grafana dashboard for OpenTelemetry Collector's internal metrics
- [nikolaydubina/grafana-otel-go-runtime](https://github.com/nikolaydubina/grafana-otel-go-runtime) - Grafana dashboard for visualizing Go runtime metrics from OpenTelemetry instrumentation (built on go-otel-runtime)
- [ymtdzzz/otel-tui](https://github.com/ymtdzzz/otel-tui) - Terminal-based OpenTelemetry trace viewer (inspired by otel-desktop-viewer)

### Testing & Development Tools
- [cisco-open/test-telemetry-generator](https://github.com/cisco-open/test-telemetry-generator) - OpenTelemetry data generator for testing: acts like an exporter producing configurable spans/metrics/logs from YAML definitions
- [OddDotNet/OddDotNet](https://github.com/OddDotNet/OddDotNet) - .NET test harness for Observability-Driven Development (ODD); includes an OTLP receiver supporting traces, metrics and logs
- [wbollock/otel_upgrade_helper](https://github.com/wbollock/otel_upgrade_helper) - Static website tool to compare and filter OpenTelemetry Collector release notes and upgrade guides between versions

### Integrations & Receivers
- [honeycombio/anthropic-usage-receiver](https://github.com/honeycombio/anthropic-usage-receiver) - OTEL Collector receiver that collects usage and cost metrics from the Anthropic AI API and converts them into OTLP metrics/logs
- [kubearmor/otel-adapter](https://github.com/kubearmor/otel-adapter) - OpenTelemetry receiver for KubeArmor (container security); exports KubeArmor events into the OTel data pipeline
- [lightstep/telemetry-generator](https://github.com/lightstep/telemetry-generator) - Configurable OTEL receiver that generates synthetic metrics and traces to emulate live services (useful for load testing)
- [Marcinthecloud/otel-to-pipelines](https://github.com/Marcinthecloud/otel-to-pipelines) - A sample Cloudflare Worker that acts as an OTLP receiver and sends it to Cloudflare Pipelines
- [theletterf/otel-sonifier](https://github.com/theletterf/otel-sonifier) - Calm monitoring extension for the OpenTelemetry Collector

### Analysis & Quality Tools
- [openlit/openlit](https://github.com/openlit/openlit) - Open-source AI engineering platform with built-in OpenTelemetry observability for LLMs, GPUs, etc.; provides GPU monitoring and LLM telemetry integrated with OTel
- [polyfloyd/go-opentelemetry-lint](https://codeberg.org/polyfloyd/go-opentelemetry-lint) - Golang linter to find and automatically fix issues with OpenTelemetry spans
- [wbollock/good_telemetry](https://github.com/wbollock/good_telemetry) - LLM analysis of whether your telemetry is "good" or not!

## Contributing

Contributions welcome! Please feel free to submit a Pull Request.

## License

This list is provided as-is for educational and informational purposes.

