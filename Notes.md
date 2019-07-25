to get started, cd into the new directory:
  cd server

To deploy your Graphcool service:
  graphcool deploy

To start your local Graphcool cluster:
  graphcool local up
  
To add facebook authentication to your service:
  graphcool add-template auth/facebook


$ graphcool init --force server

.
├── graphcool.yml
├── package.json
├── src
│   ├── hello.graphql
│   └── hello.js
└── types.graphql

graphcool.yml: Contains your service definition.

types.graphql: Contains the data model and any additional type definitions for your Graphcool service, 

written in the GraphQL Schema Definition Language (SDL).

src: Contains the source code (and if necessary GraphQL queries) for the functions you've configured for 
your service.
