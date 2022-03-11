### GraphQL

It is a query language for APIs. Can be used in the front-end and back-end.

Basic use cases: 

        Query
        Mutations
        Subscriptions
        
Query - Used to get data from the server.

        `feed{
        id
        links{
        description
        url
        }
        }`

Mutations - Used to change data or add new data into the server.

       `mutation PostMutation($description:String!, $url: String!){
       post(description: $description, url: $url){
       id
       description
       url
       }
       }`

Subscriptions - Used to send data to the client from the server when an even occurs. 
