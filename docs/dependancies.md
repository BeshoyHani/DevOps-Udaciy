# Application Dependencies


## Back-End

The Back-End API depends on many packages which are listed below.

### Production deps

1. `bcrypt`: Used for Hashing the user's password
2. `jsonwebtoken`: Used for signing & verifying authorization tokens
3. `dotenv`: Used for getting environment files from a `.env` file
4. `body-parser`: Used for parsing JSON body of HTTP requests
5. `cors`: Used for managing Cross Origin headers
6. `pg`: Used by interact with Postgres DB
7. `sequelize`: An ORM library, used to handle Models & Sync DB
8. `sequelize-typescript`: Provides features for Sequelize that exist only in Typescript and not JavaScript (e.g. Decorators)  
9. `reflect-metadata`: Provides the ability of Dependency Injection, Runtime type validation, ...etc
10. `express`: Used for HTTP server management (Routing, middlewares, ..etc)
11. `email-validator`: Validates emails... 
11. `aws-sdk`: Used for generating signed URLs for S3 for both Get & Put operations.

### Dev deps

1. `@typescript-eslint/eslint-plugin`: To Support TS in ESLint
1. `eslint-config-google`: Uses Google's Config
1. `@typescript-eslint/parser`: Parses TypeScript
1. `chai`: Provides easier assertion in testing
1. `chai-http`: Extends `chai` with http based assertion
1. `mocha`: Used as the testing framework
1. `ts-node-dev`: Runs ts as .js files but restarts when they are changed. 
1. `typescript`: Used for adding types to JS, also includes Typescript compiler

## Front-End

### Production deps

1. `angular/*`: Angular libraries & extensions
2. `ionic-native/*`: Provides Native plugins for Ionic Apps (e.g. Splash Screen)
3. `core-js`: Polyfills & support for new standard ECMA versions
4. `rxjs`: To use Reactive Programming for Async ops.
5. `zone.js`: To be able to use different execution contexts.

### Dev Deps

1. Karma, Jasmine & Protractor for testing
2. ts-node, tslint & Typescript for compilation, linting & dev.

## Deployment Pipeline

1. `npm-run-all`: To run multipl npm scrips in a shorter way. Instead of `npm run x && npm run y`, use `npm-run-all x y`