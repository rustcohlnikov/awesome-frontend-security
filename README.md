# Awesome Frontend Security [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
> 💜A curated list of tools, articles &amp; resources to help take your frontend security to the next level.
> Feel free to contribute!

## Contents
- [Code](#code)
  - [Linters](#linters)
  - [Sanitizers](#sanitizers)
  - [Serializers](#serializers)
- [Dependencies](#dependencies)
- [Headers](#headers)
  - [Content Security Policy](#content-security-policy)
  - [X-Frame-Options](#x-frame-options)
  - [X-XSS-Protection](#x-xss-protection)
- [Articles](#articles)
- [Other lists](#other-lists)


## Code
### Linters
- [`eslint-config-sec`](https://github.com/rustcohlnikov/eslint-config-sec) - Linting rules for safe and secure client code.
- [`eslint-plugin-security`](https://github.com/nodesecurity/eslint-plugin-security) - ESLint rules for Node Security.

### Sanitizers
- [`sanitize-html`](https://github.com/apostrophecms/sanitize-html) - Clean up user-submitted HTML.

### Serializers
- [`serialize-javascript`](https://github.com/yahoo/serialize-javascript) - Serialize JavaScript safely - HTML characters and JS line terminators are escaped automatically.

## Dependencies
- [`audit-ci`](https://github.com/IBM/audit-ci) - NPM and Yarn dependencies audit for CI/CD.
- [`dtrack-audit`](https://github.com/ozonru/dtrack-audit) - OWASP Dependency Track API client for CI/CD.

## Headers
### Content-Security-Policy 
#### Learn
- [MDN](https://developer.mozilla.org/en-US/docs/Web/HTTP/CSP) - An article on MDN.

#### Create
- [Webpack CSP configuration](https://webpack.js.org/guides/csp/) - Webpack is capable of adding nonce(number used once) to all scripts that it loads.
- [`csp-html-webpack-plugin`](https://github.com/slackhq/csp-html-webpack-plugin) - Generates meta content for your Content Security Policy tag.
- [CSP Hash Generator](https://report-uri.com/home/hash) – Script and style hasher for `script-src` and `style-src` directives to disallow inline scripts and styles. More [here](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Content-Security-Policy/script-src#Unsafe_inline_script).

#### Validate
- [CSP Evaluator](https://csp-evaluator.withgoogle.com/) - Paste your policy and check if its safe and strong enough.
- [CSP Header Inspector](https://cspvalidator.org) - Validate your policies as served from the given URL.
- [CSP Tester](https://github.com/yandex/csp-tester) - Browser extension for testing Content Security Policy (CSP).

#### Analyse
- [CSP WTF?](https://github.com/nico3333fr/CSP-useful/blob/master/csp-wtf/explained.md) - Explanations for strange CSP Report notifications.

### X-Frame-Options 
#### Learn
- [MDN](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options) - An article on MDN.

### X-XSS-Protection 
#### Learn
- [MDN](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-XSS-Protection) - An article on MDN.

## Articles

## Other lists
- [CSP useful](https://github.com/nico3333fr/CSP-useful) - A collection of parsers, examples and tips for Content Security Policy.
- [Awesome Web Security](https://github.com/qazbnm456/awesome-web-security) – A curated list of Web Security materials and resources.
