# prisma-typegraphql-demo

First,execute: npm install.
Second, in order to run this project locally :
1- you should change the URL of the DB by your local url.
2- execute: npx prisma generate 
3- fix the problem of in many resolvers(PostCrudResolver, UserCrudResolver ..) by replacing import graphqlFields from "graphql-fields"; with this line : import * as graphqlFields from "graphql-fields";
4- execute: npx prisma db push
Finally execute : npm start and test your local graphQL server on http://localhost:4000

