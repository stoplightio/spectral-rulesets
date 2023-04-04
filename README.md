# Spectral Rulesets

Keeping track of Spectral Rulesets in the wild, covering all sorts of use-cases like enforcing organization's API Style Guides, security scanning, spellchecking, and helping folks write better quality API descriptions.

## API Style Guides

Rulesets focused on helping you design and build better APIs.

- [Adidas](https://github.com/adidas/api-guidelines/blob/master/.spectral.yml) - Adidas were one of the first companies to release their API Style Guide in a written guide _and_ a Spectral ruleset. Lots of good rules to try in here.
- [APIs You Won't Hate](https://github.com/apisyouwonthate/style-guide) - An opinionated collection of rules based on advice in the book APIs You Won't Hate community. 
- [Box](https://github.com/box/box-openapi/blob/main/.spectral.yml) - Lots of [Custom Functions](https://meta.stoplight.io/docs/spectral/ZG9jOjI1MTkw-custom-functions) being used to enforce good practices that the Box API governance folks are interested in.
- [Tranascom](https://github.com/transcom/mymove/blob/master/swagger-def/.spectral.yml) - Don't even think about using anything other than `application/json`.
- [SPS Commerce](https://github.com/spscommerce/sps-api-standards) - Holistic and opinionated API style guide with documentation portal and associated sprectral ruleset.

## OpenAPI Style Guides

Rulesets helping you write better OpenAPI or AsyncAPI, but doesn't really tell you how to write the API itself.

- [Documentation](https://github.com/stoplightio/spectral-documentation) - Scan an OpenAPI description to make sure you're leveraging enough of its features to help documentation tools like Stoplight Elements, ReDoc, and Swagger UI build the best quality API Reference Documentation possible.
- [Azure](https://github.com/Azure/azure-api-style-guide/blob/main/spectral.yaml) - Ruleset and complimentary style guide for creating OpenAPI 2 or 3 definitions of Azure services.
- [DigitalOcean](https://github.com/digitalocean/openapi/blob/main/spectral/ruleset.yml) - Keeping their OpenAPI nice and tidy, enforcing use of `$ref` (probably to minimize conflicts), naming conventions for Operation IDs, and all sorts of other handy OpenAPI tips.
- [Monite](https://github.com/team-monite/api-style-guide/blob/main/Guidelines.md) - A written API Style Guide being implemented bit at a time with create Spectral rules, with a brilliant [monite-language-non-inclusive](https://github.com/team-monite/api-style-guide/blob/main/spectral/monite.section2-language.yaml) rule.
- [Nexmo](https://github.com/Nexmo/api-specification/blob/main/.spectral.yml) - Communication company (now part of Vonage) have some handy rules like enforcing SemVer, requiring properties to have an example, and determining a preferred order of HTTP method definitions.
- [Red Hat](https://github.com/redhat-developer/app-services-api-guidelines/tree/main/spectral) - Available as a npm module, this ruleset enforces the use of the companies preferred license, URL conventions for the whole path, and sets up consistent error responses across all APIs.
- [SchwarzIT](https://github.com/SchwarzIT/api-linter-rules/blob/main/spectral.yml) - Ruleset from the IT service provider behind Lidl, Kaufland and other companies from the Schwarz group.
- [Team Digitale](https://github.com/teamdigitale/api-openapi-samples/blob/master/.spectral.yml) - The Italian government have an interesting ruleset with great caching rules, helping teams avoid confusion like using both Cache-Control and Expires at once.
- [VRChat Community](https://github.com/vrchatapi/specification/blob/main/.spectral.yaml) - Very interesting use of the `resolved: false` option to make sure teams are using `$ref` instead of inlining things. [Keep it DRY](https://blog.stoplight.io/keeping-openapi-dry-and-portable)!
- [VTex](https://github.com/vtex/openapi-schemas/blob/master/.spectral.yml) - This Digital Commerce Platform loves style guides. They have one for their React components, so why not have one for their [many many Web APIs](https://github.com/vtex/openapi-schemas).

## Functional Rulesets

Guiding people to write APIs that conform to certain standards, or to work with specific tooling.

- [AWS Gateway](https://github.com/andylockran/spectral-aws-apigateway-ruleset) - Made by [@andylockran](https://github.com/andylockran) to help avoid some of the quirks of AWS Gateway's OpenAPI compatibility. 
- [OWASP API Security](https://github.com/stoplightio/spectral-owasp-ruleset) - Improve the security of your API by detecting common vulnerabilities as defined by OWASP and enforced with Spectral. 
- [URL Versioning](https://github.com/stoplightio/spectral-url-versioning) - API versioning can be a scary topic but there are a few easy wins that are always best avoided.

Checkout more style guides at [API Stylebook](apistylebook.stoplight.io) by @stoplightio and [API Guidelines](https://dret.github.io/guidelines/) by @dret
