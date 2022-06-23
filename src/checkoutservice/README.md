# checkoutservice

Run the following command to restore dependencies to `vendor/` directory:

```sh
dep ensure --vendor-only
```

## OpenTelemetry features

### Emoji Legend

- Completed: :100:
- Not Present (Yet): :construction:

### Traces

- :100: [Instrumentation
  Libraries](https://opentelemetry.io/docs/concepts/instrumenting-library/)
- :construction: [Manual Span
  Creation](https://github.com/open-telemetry/opentelemetry-specification/blob/main/specification/glossary.md#manual-instrumentation)
- :construction: [Span Data
  Enrichment](https://opentelemetry.io/docs/instrumentation/net/manual/#add-tags-to-an-activity)
- :construction: Interprocess Context Propagation
- :construction: [Intra-service Context
  Propagation](https://opentelemetry.io/docs/instrumentation/java/manual/#context-propagation)
- :construction: [Trace
  Links](https://github.com/open-telemetry/opentelemetry-specification/blob/main/specification/overview.md#links-between-spans)
- :construction:
  [Baggage](https://github.com/open-telemetry/opentelemetry-specification/blob/main/specification/baggage/api.md#overview)

### Metrics

- :construction: [Instrumentation
  Libraries](https://opentelemetry.io/docs/concepts/instrumenting-library/)
- :construction: [Manual Metric
  Creation](https://github.com/open-telemetry/opentelemetry-specification/blob/main/specification/glossary.md#manual-instrumentation)
- :construction: [Collector Agent Metric
  Transformation](https://opentelemetry.io/docs/collector/deployment/#agent)
- :construction: [Push
  Metrics](https://opentelemetry.io/docs/reference/specification/metrics/sdk/#push-metric-exporter)
- :construction:[SLO Metrics](https://github.com/openslo/openslo#slo): :construction:
- :construction: [Multiple Manual Metric
  Instruments](https://opentelemetry.io/docs/reference/specification/metrics/api/#synchronous-and-asynchronous-instruments)