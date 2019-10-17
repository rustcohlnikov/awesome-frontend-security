# Awesome FE Security [![Awesome](https://awesome.re/badge-flat2.svg)](https://github.com/sindresorhus/awesome)
> 💜 A curated list of tools, articles &amp; resources to help take your frontend security to the next level.
> Feel free to contribute!

## Contents
- [Code](#code)
  - [Linters](#linters)
  - [Sanitizers](#sanitizers)
  - [Serializers](#serializers)
- [Dependencies](#dependencies)
- [Headers](#headers)
  - [Content-Security-Policy](#content-security-policy)
  - [X-Frame-Options](#x-frame-options)
  - [X-XSS-Protection](#x-xss-protection)
- [Articles](#articles)
- [Other lists](#other-lists)


## Code
- [Security Policy](https://help.github.com/en/articles/adding-a-security-policy-to-your-repository) - How to add a security policy to your Github repository.

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
- [Github Automated Security Fixes](https://help.github.com/en/articles/configuring-automated-security-fixes) - use automated or manual pull requests to easily update vulnerable dependencies.

## Headers
- [Security Headers](https://securityheaders.com/) - check your website's HTTP response headers for security.

### Content-Security-Policy 
#### 📚Learn
- [MDN](https://developer.mozilla.org/en-US/docs/Web/HTTP/CSP) - An article on MDN.
- [CSP Is Dead, Long Live CSP!](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/45542.pdf) - On the Insecurity of Whitelists and the Future of Content Security Policy.

#### 🧪Create
- [Webpack CSP configuration](https://webpack.js.org/guides/csp/) - Webpack is capable of adding nonce(number used once) to all scripts that it loads.
- [`csp-html-webpack-plugin`](https://github.com/slackhq/csp-html-webpack-plugin) - Generates meta content for your Content Security Policy tag.
- [CSP Hash Generator](https://report-uri.com/home/hash) - Script and style hasher for `script-src` and `style-src` directives to disallow inline scripts and styles. More [here](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Content-Security-Policy/script-src#Unsafe_inline_script).

#### 🔍Validate
- [CSP Evaluator](https://csp-evaluator.withgoogle.com/) - Paste your policy and check if its safe and strong enough.
- [CSP Header Inspector](https://cspvalidator.org) - Validate your policies as served from the given URL.
- [CSP Tester](https://github.com/yandex/csp-tester) - Browser extension for testing Content Security Policy (CSP).

#### 🤔Analyse
- [CSP WTF?](https://github.com/nico3333fr/CSP-useful/blob/master/csp-wtf/explained.md) - Explanations for strange CSP Report notifications.

### X-Frame-Options 
#### 📚Learn
- [MDN](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options) - An article on MDN.

### X-XSS-Protection 
#### 📚Learn
- [MDN](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-XSS-Protection) - An article on MDN.

## Articles
- [Cybersecurity threatscape](https://www.ptsecurity.com/ww-en/analytics/cybersecurity-threatscape-2019-q2/) - Positive Technologies' quarter report on cyber threats and recommendations on how to stay safe.

## Other lists
- [OWASP Web Application Security Checklist](https://github.com/0xRadi/OWASP-Web-Checklist)
- [CSP useful](https://github.com/nico3333fr/CSP-useful) - A collection of parsers, examples and tips for Content Security Policy.
- [Awesome Web Security](https://github.com/qazbnm456/awesome-web-security) - A curated list of Web Security materials and resources.

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)
