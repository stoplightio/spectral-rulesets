# Spectral Rulesets

Keeping track of Spectral Rulesets in the wild, helping you build better, more consistent APIs, via OpenAPI, AsyncAPI, JSON Schema, etc.


## Design Rulesets (a.k.a "API Style Guide")

Helping you design and build better APIs.

- [Adidas](https://github.com/adidas/api-guidelines/blob/master/.spectral.yml) - Adidas were one of the first companies to release their API Style Guide in a written guide _and_ a Spectral ruleset. Lots of good rules to try in here.
- [APIs You Won't Hate](https://github.com/apisyouwonthate/style-guide) - An opinionated collection of rules based on advice in the book APIs You Won't Hate community. 
- [Box](https://github.com/box/box-openapi/blob/main/.spectral.yml) - Lots of [Custom Functions](https://meta.stoplight.io/docs/spectral/ZG9jOjI1MTkw-custom-functions) being used to enforce good practices that the Box API governance folks are interested in.
- [Tranascom](https://github.com/transcom/mymove/blob/master/swagger-def/.spectral.yml) - Don't even think about using anything other than `application/json`.

## Lint Rulesets

Helping you write better OpenAPI or AsyncAPI.

- [DigitalOcean](https://github.com/digitalocean/openapi/blob/main/spectral/ruleset.yml) - Keeping their OpenAPI nice and tidy, enforcing use of `$ref` (probably to minimize conflicts), naming conventions for Operation IDs, and all sorts of other handy OpenAPI tips.
- [Nexmo](https://github.com/Nexmo/api-specification/blob/main/.spectral.yml) - Communication company (now part of Vonage) have some handy rules like enforcing SemVer, requiring properties to have an example, and determining a preferred order of HTTP method definitions.
- [Red Hat](https://github.com/redhat-developer/app-services-api-guidelines/tree/main/spectral) - Available as a npm module, this ruleset enforces the use of the companies preferred license, URL conventions for the whole path, and sets up consistent error responses across all APIs.
- [Team Digitale](https://github.com/teamdigitale/api-openapi-samples/blob/master/.spectral.yml) - The Italian government have an interesting ruleset with great caching rules, helping teams avoid confusion like using both Cache-Control and Expires at once.
- [VRChat Community](https://github.com/vrchatapi/specification/blob/main/.spectral.yaml) - Very interesting use of the `resolved: false` option to make sure teams are using `$ref` instead of inlining things. [Keep it DRY](https://blog.stoplight.io/keeping-openapi-dry-and-portable)!
- [VTex](https://github.com/vtex/openapi-schemas/blob/master/.spectral.yml) - This Digital Commerce Platform loves style guides. They have one for their React components, so why not have one for their [many many Web APIs](https://github.com/vtex/openapi-schemas).
- [Azure](https://github.com/Azure/azure-api-style-guide/blob/main/spectral.yaml) - Ruleset and complimentary style guide for creating OpenAPI 2 or 3 definitions of Azure services.
