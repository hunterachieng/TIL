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

*https://github.com/hunterachieng/graphql-practice*

## Updating data

GraphQL uses the same mutation format to update data to the server. A few changes can be implemented in the mutation to support the exact item being updated. Eg:

```
const UPDATE_USER = gql`
  mutation UpdateUser($id: String!, $firstname: String!, $lastname: String!, $nickname: String!, $email: String!, $password: String!) {
    updateUser(
      id: $id,
      data: {
        firstname: $firstname, 
        lastname: $lastname, 
        nickname: $nickname, 
        email: $email, 
        password: $password
      }
    ) {
      id
    }
  }
`;
```
