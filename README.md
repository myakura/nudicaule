This browser extension (Manifest V3) blocks JavaScript files served from https://polyfill.io/ .

## Why?

Polyfill.io is a service that provides polyfills for various web APIs. It is used by many websites to provide support for older browsers.

In 24th of February 2024, the owner of the service and the domain were changed to a China-based company Funnull. https://github.com/polyfillpolyfill/polyfill-service/issues/2834

While being owned by a company behind Great Firewall of China does not necessarily mean that the service is malicious, it is still a good idea to block it to prevent potential privacy and security issues.

Plus, since browsers matured and no longer need polyfills, it is not necessary anymore to load scripts from polyfill.io.
