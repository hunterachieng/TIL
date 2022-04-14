## GraphQL Codegen

This is a library used to generate GraphQL hooks from the provided graphQL schema.

The generated hooks seperates the model from the view in client-side software architecture. 

To install in React: 

`npm i @graphql-codegen/cli`

After installation, run:

`yarn graphql-codegen init`

This initializes graphql codegen and then you specify the dependencies to be installed as well as the location of the generated hooks.

To run the GraphQL code generator, run: ``` npm run graphql:codegen```
