## Hotspot

A human-friendly HTML landing page for users resolving URLs within their browser that point to resources on a FHIR server.

This is a pure client-side app that is configured to point to a FHIR endpoint.

It can be configured with a custom stylesheet to be applied to narratives within FHIR resources.

Install local development dependencies:

* Node.js (https://nodejs.org/)
* Yarn (https://yarnpkg.com/en/docs/install)

Run it up locally:

```
yarn
yarn start
```

Edit `public/config.json` to customise.

Build for production:

```
yarn build
```