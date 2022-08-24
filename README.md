# 🔨 actions-eslint

[![Checks status][checks status]][checks url]
[![Dependabot status][dependabot status]][dependabot url]
[![License][license badge]][license url]

🔥 Native, blazingly-fast `eslint` CLI on Github Actions, allows you to run
every `eslint` CLI command on Github Actions without having to install Node.js
or any dependency in advance.

> Average completion time: 5-8s - 7x faster than self-implemented workflow (with
> cache enabled).

## Usage

```yml
- uses: actions/checkout@v2 # Check out the repository first.
- uses: actions-eslint
  with:
    # eslint CLI arguments.
    args: --fix .
```

## License

This project is licensed under the [MIT License][license url].

<!-- Links -->

[checks status]: https://img.shields.io/github/checks-status/whjvenyl/actions-eslint/master?logo=Github
[dependabot status]: https://img.shields.io/badge/dependabot-enabled-025e8c?logo=Dependabot
[license badge]: https://img.shields.io/github/license/whjvenyl/actions-eslint
[checks url]: https://github.com/whjvenyl/actions-eslint/actions?query=workflow%3ACI+branch%3Amaster
[dependabot url]: /.github/dependabot.yml
[license url]: /LICENSE
