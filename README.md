# Locations sample client (Angular)

## Summary

This is a sample client for locations service written in [Angular](https://angularjs.org/). 

**!important**: before running this client you have to add this line to the styles array in your angular.json file to load
leaflet(map library used by this client) global styles like this: 
```
"midgard-angular": {
            ...
            "styles": [
              "src/styles.scss",
              "./src/clients/locations/node_modules/leaflet/dist/leaflet.css"
            ],
            ...
```

## Dependencies

### npm libraries

-  _List of npm packages used_
-  _List of npm packages used_

## Develop this client

-  To **build** the project: `ng build {name-of-module}`  
  -  The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.
-  To **run tests** using [Karma](https://karma-runner.github.io/0.13/index.html): `ng test {name-of-module}`
-  To **run end-to-end tests** using [Protractor](https://www.protractortest.org/#/): `ng e2e {name-of-module}`

## File structure

-  `/components`: Components that do not have roots assigned to them.
-  `/helpers`: The client's helper classes.
-  `/pages`: Components that have roots assigned to them.
-  `/services`: Classes that provide data.
-  `/state`: State-related files and data models.
-  `/styles`: Contains styles specific to the client.
-  `routing.module.ts`: Where the client's routes are defined.
-  `ngModule`: Where components, services, pipes, etc. are defined.

## Services

This client connects to the following services:

-  [Link to documentation for service that the client uses](https://example.com)
-  [Link to documentation for service that the client uses](https://example.com)

Document the ways in which this client connects to the service. Methods used, data models used, endpoints used, etc.

## API documentation (Compodoc)

Run `npm run compodoc` to generate [Compodoc](https://compodoc.github.io/compodoc/) documentation to the `/documentation` directory.

## License

Copyright &#169;2019 Humanitec GmbH.

This code is released under the [Humanitec Affero GPL](LICENSE).
