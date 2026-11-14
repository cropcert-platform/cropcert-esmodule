# ☕ cropcert-esmodule

> Elasticsearch module for CropCert

![License](https://img.shields.io/badge/license-Apache--2.0-blue.svg) ![Language](https://img.shields.io/badge/language-Java-ED8B00?logo=openjdk&logoColor=white) ![Part of](https://img.shields.io/badge/part%20of-CropCert%20Platform-2e7d32.svg)

## 🌱 Overview

The Elasticsearch module of the CropCert platform, providing search indexing and querying capabilities to other modules. Originally `biodiv-esmodule`.

This repository is part of the [CropCert Platform](https://github.com/cropcert-platform), an open-source platform for crop certification and traceability that helps small growers add value to their crops and reach better markets.

## ✨ Features

- Elasticsearch-backed search
- Java / Maven project

## 🚀 Getting started

### 📋 Prerequisites

- Java Development Kit (JDK) — see `pom.xml` for the required version
- [Apache Maven](https://maven.apache.org/) 3.x
- Any backing services this module needs (for example a database or message broker), as set in its configuration

### 🔧 Build & run

```bash
git clone https://github.com/cropcert-platform/cropcert-esmodule.git
cd cropcert-esmodule
mvn clean package
```

The build produces a deployable artifact in `target/`. Deploy it to a Java servlet container or run it as your environment requires.

### ⚙️ Configuration

Environment-specific settings (database connection, service URLs, credentials) are supplied through the module's configuration files. Keep secrets out of version control and provide them per environment.

### 📖 API documentation

This module exposes a REST API. Where Swagger / OpenAPI is configured, the generated documentation is available from the running service.

## 📁 Project structure

```text
.
├── pom.xml          # Maven build definition
├── src/main         # Application source code
└── LICENSE
```

## 🔗 Related repositories

| Repository | Description |
|---|---|
| [cropcert-user](https://github.com/cropcert-platform/cropcert-user) | User management microservice |
| [cropcert-usergroup](https://github.com/cropcert-platform/cropcert-usergroup) | User group microservice |
| [cropcert-activity](https://github.com/cropcert-platform/cropcert-activity) | Activity microservice |
| [cropcert-resources](https://github.com/cropcert-platform/cropcert-resources) | Resources microservice |
| [cropcert-document](https://github.com/cropcert-platform/cropcert-document) | Document microservice |
| [cropcert-files](https://github.com/cropcert-platform/cropcert-files) | File handling microservice |
| [cropcert-pages](https://github.com/cropcert-platform/cropcert-pages) | Pages microservice |
| [cropcert-utility](https://github.com/cropcert-platform/cropcert-utility) | Utility microservice |
| [cropcert-mail](https://github.com/cropcert-platform/cropcert-mail) | Mail microservice |

See all repositories in the [cropcert-platform](https://github.com/cropcert-platform) organisation.

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/my-change`
3. Commit your changes with clear messages
4. Push the branch and open a pull request

For bugs and feature requests, please [open an issue](https://github.com/cropcert-platform/cropcert-esmodule/issues).

## 📄 License

Distributed under the **Apache License 2.0**. See [`LICENSE`](LICENSE) for details.

## 🙏 Acknowledgements

This repository is a fork of [biodiv-platform/biodiv-esmodule](https://github.com/biodiv-platform/biodiv-esmodule) maintained for the CropCert platform. Thanks to the original authors and the [biodiv-platform](https://github.com/biodiv-platform) community.
