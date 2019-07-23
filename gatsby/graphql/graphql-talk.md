# GraphQL

## What is GraphQL?

GraphQL was invented at Facebook to help product engineers pull needed data into React components.

GraphQL is a query language (the QL part of its name). If you're familiar with SQL, it works in a very similar way. Using a special syntax, you describe the data you want in your component and then that data is given to you.

## Why is it used in the industry?

- Strongly Typed

- Static Analysis of queries

- Know what clients are actually using from your api

- One unified endpoint

## Why is it used in Gatsby? 

- Eliminate frontend data boilerplate --- no need to worry about requesting & waiting for data. Just ask for the data you need with a GraphQL query and it'll show up when you need it

- Push frontend complexity into queries --- many data transformations can be done at build-time within your GraphQL queries

- It's the perfect data querying language for the often complex/nested data dependencies of modern applications

- Improve performance by removing data bloat --- GraphQL enables you to select only the data you need, not whatever an API returns

## Query === GET 

- Show how to access the docs

- Query Basics

- Show how to access edges and nodes

- Show how to use variables

- Show how to use functions

- Show how to use fragments and create your own

- Test for equality

- Call the same relation with different parameters and alias

- Setup the Playground instead of GraphiQL

## Where is it used in Gatsby? 

- useStaticQuery

- Show basic example

- Page queries

- Show basic example

- (Advanced) 3rd party endpoints with dynamic Apollo calls

- Maybe too advanced

Mutations  === PUT & POST => probably wont have time to do this
