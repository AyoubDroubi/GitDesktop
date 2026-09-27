# Privacy Policy — GitDesktop customized fork

_Last updated: 2026-09-27_

This repository is a customized GitDesktop fork maintained under the Apache License 2.0.

## Official builds from this fork

Official builds from this repository do not configure first-party product analytics or session recording.

GitDesktop keeps repository data on the local machine unless you explicitly use a feature that connects to an external service.

## External services

- **GitHub / GitLab / Bitbucket / Jira:** requests are sent only when you use the corresponding integration, using your own account or token.
- **AI providers:** when you explicitly use an AI feature, the context required for that action may be sent to the provider you configured. Local providers such as Ollama can keep processing on your machine.
- **GitHub Releases:** update checks and downloads use this repository's GitHub Releases endpoint.

## Credentials

Supported credentials and API keys are stored using the operating system keychain or the relevant provider CLI. They are not intentionally committed to this repository.

## Source code and repository contents

This fork does not intentionally collect or transmit your source code, file contents, repository paths, branch names, or commit text to its maintainer. External integrations receive only the information required for the action you choose to perform.

## Contact

For questions about this fork, contact **ayoub.al.droubi@gmail.com**.

## License and upstream attribution

The software remains licensed under Apache-2.0. Required upstream copyright and attribution notices are preserved in `LICENSE` and `NOTICE`.
