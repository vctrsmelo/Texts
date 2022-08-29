# OpenAPI (and Swagger)

OpenAPI Specification (formerly Swagger Specification) is an API description format for REST APIs. An OpenAPI file allows you to describe your entire API, including:

* Available endpoints (`/users`) and operations on each endpoint (`GET /users, POST /users`)
* Operation parameters Input and output for each operation
* Authentication methods
* Contact information, license, terms of use and other information.

API specifications can be written in YAML or JSON. The complete OpenAPI Specification can be found on GitHub [here](https://github.com/OAI/OpenAPI-Specification/blob/master/versions/3.0.3.md).

## Why Use OpenAPI?

Once written, an OpenAPI specification and Swagger tools can drive your API development further in various ways:
* Design-first users: use [Swagger Codegen](https://github.com/swagger-api/swagger-codegen) to **generate a server stub** for your API. The only thing left is to implement the server logic - and your API is ready to go live!
* Use [Swagger Codegen](https://github.com/swagger-api/swagger-codegen) to **generate client libraries** for your API in over 40 languages.
* Use [Swagger UI](https://github.com/swagger-api/swagger-ui) to generate **interactive API documentation** that lets your users try out the API calls directly in the browser.
* Use the spec to connect API-related tools to your API. For example, import the spec to [SoapUI](https://soapui.org/) to create automated tests for your API.
* And more! Check out the [open-source](https://swagger.io/tools/open-source/open-source-integrations/) and [commercial tools](https://swagger.io/commercial-tools/) that integrate with Swagger.
