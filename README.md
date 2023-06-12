# GraphQLRestaurantSample
GraphQL restaurant tutorial

This is a sample project that demonstrates the usage of GraphQL to build a simple restaurant API. 
It provides basic operations to query and manipulate restaurant data.

## Prerequisites

Before running this project, ensure that you have the following installed:

- Node.js (version 14 or higher)
- NPM (Node Package Manager)


## Getting Started

1. Clone the repository:git clone <repository-url>
   
2. Install dependencies: npm install 
  
3. Start the server: node index.js
  
 4. Open your browser and navigate to http://localhost:5500/graphql to access the GraphQL Playground.
  
## Usage
The GraphQL API supports the following queries and mutations:

## Queries
  
1. restaurant(id: Int): restaurant: Retrieves a single restaurant based on the provided ID.
  
2. restaurants: [restaurant]: Retrieves a list of all restaurants.
  
## Mutations
1. setrestaurant(input: restaurantInput): restaurant: Creates a new restaurant based on the provided input.
  
2. deleterestaurant(id: Int): DeleteResponse: Deletes a restaurant based on the provided ID.
  
3. editrestaurant(id: Int!, name: String!): restaurant: Updates a restaurant's name based on the provided ID and new name.

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License.


