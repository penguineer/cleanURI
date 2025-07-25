# cleanURI

> Central documentation for the cleanURI service.

The system consists of the following sub-projects:
* [Site](https://github.com/penguineer/cleanURI-site) - Interfaces and helpers for site-specific implementations
* [Site Implementations](https://github.com/penguineer/cleanURI-site-implementations) - Sites supported by the cleanURI project
* [Common](https://github.com/penguineer/cleanURI-common) - Common classes and definitions
* [API Gateway](https://github.com/penguineer/cleanURI-apigateway) - REST API Gateway to the backend services
* [Canonizer](https://github.com/penguineer/cleanURI-canonizer) - Transform a URL into its canonic form
* [Extractor](https://github.com/penguineer/cleanURI-extractor) - Extract meta-data to create decorated referencess
* :construction: Cache
* [Web UI](https://github.com/penguineer/cleanURI-webui) - A web-based frontend
* [Helm Chart](https://github.com/penguineer/cleanURI-helm)

## Why so complicated?

The cleanURI project is designed with a very high degree of modularity in mind.
This may seem overly complicated at first, but serves as a test bed for structural patterns that will be needed in larger projects.

While this projects serves a real purpose, it is also a playground and learning environment for the author.
New ideas and patterns are tested here, so that they can be used with confidence larger production environments.

## Maintainers

* Stefan Haun ([@penguineer](https://github.com/penguineer))


## Contributing

PRs are welcome!

If possible, please stick to the following guidelines:

* Keep PRs reasonably small and their scope limited to a feature or module within the code.
* If a large change is planned, it is best to open a feature request issue first, then link subsequent PRs to this issue, so that the PRs move the code towards the intended feature.

Please check the sub-projects linked above to see where the contribution would fit best.


## License

[MIT](LICENSE.txt) © 2022-2025 Stefan Haun and contributors
