# alx-graphql-0x00

Character Query Task
Objective
Retrieve a paginated list of characters using GraphQL.

Instructions
Run the GraphQL queries in the provided .graphql files to fetch character data.
Save the output in the corresponding .json files.
Query Structure
query {
  characters(page: 1) {
    results {
      id
      name
      status
      image
    }
  }
}
Repeat this query for pages 2, 3, and 4, adjusting the page parameter each time.

Save the Query
Save each query in separate files as specified:

characters-page-1.graphql → For page 1. characters-page-2.graphql → For page 2. characters-page-3.graphql → For page 3. characters-page-4.graphql → For page 4.

Fetch and Save the Output Run the queries using a GraphQL client or an API testing tool like Postman, Insomnia, or any code implementation. After running each query, save the JSON response as follows:
characters-page-1-output.json → Output of the query for page 1. characters-page-2-output.json → Output of the query for page 2. characters-page-3-output.json → Output of the query for page 3. characters-page-4-output.json → Output of the query for page 4.

Update the README.md In the README.md file, provide an explanation of:
Tools Required
GraphQL client (e.g., Insomnia, Postman) API Endpoint: <Provide the API URL>