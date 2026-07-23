 <div align="center">
 <img alt="Donkey Logo" src="_static/assets/favicon.png" width="80px">
  <h1>Donkey</h1>
  <p><strong>Build production-ready AI applications with modular, composable components.</strong></p>
</div>

## ⚡ Starter
The quickest way to get up and running is with the starter bundle, which includes the core framework plus our most popular integrations:

=== "pip"

    ```bash
    $ pip install donkeyai
    ```

=== "uv"

    ```bash
    $ uv add donkeyai
    ```

## 🔧 Advanced (recommended for production)
For production deployments, we recommend installing only the core package plus the specific integrations you actually use:

=== "pip"

    ```bash
    $ pip install donkey-core
    $ pip install donkey-llms-*
    $ pip install donkey-vector-stores-*
    ```

=== "uv"

    ```bash
    $ uv add donkey-core
    $ uv add donkey-llms-*
    $ uv add donkey-vector-stores-*
    ```
<small>
Installing individual packages instead of the full bundle keeps your environment lean:

- **Smaller footprint** — Fewer dependencies means smaller Docker images and faster cold starts.
- **Fewer conflicts** — Avoid pulling in transitive dependencies from integrations you never use. 
- **Security surface** — Less third-party code to audit, patch, and monitor for vulnerabilities.
- **Predictable upgrades** — Control exactly which integrations get updated and when.
</small>

## ✨ Highlight features

- **Modular Architecture** — Pick only the components you need. Each integration is its own installable package.
- **Enterprise Integrations** — First-class support for watsonx.ai, Elasticsearch, Chroma, Hugging Face, and more.
- **Built-in Observability** — Instrument your pipelines with OpenTelemetry-compatible tracing and custom metrics.
- **Guardrails** — Apply input/output guardrails to keep your AI applications safe and compliant.
- **Async-First Workflows** — Event-driven workflow engine with fan-out/fan-in, shared state, and built-in HTTP server.

## 👋 Contributing

We welcome contributions! Please see our [issue templates](https://github.com/donkey-project/donkey/issues/new/choose) to get started.

## License

[Apache License 2.0](LICENSE).
