# inversify-express-example

>The official express + inversify + inversify-express-utils example

## Use examples

First of all run `npm install`

You can start a example by using `ts-node` 
```
$ npm install -g ts-node
$ ts-node <example>/bootstrap
```
This will start up the server and you can use the example

If you want to run the unit tests, simply use `npm test <example>/**/*.spec.ts`

To run all tests simply run `npm run test:all`

## Currently available examples

Name    | Description
------- | -------------------------------------------------------------------------------------------------------------------------------
Basic   | A really basic example. Nothing too fancy.
BindingDecorators | Similar to the basic example. This time with inversify-binding-decorators.
MiddlewareInjection | A small example that shows how to inject middleware into controllers.
PostgresAndTypeORM | A small example that shows how to integrate inversify-express-utils with TypeORM.
