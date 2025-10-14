# Episode Query

## Objective

This project demonstrates how to write a GraphQL query to fetch details of a specific episode using its ID.

## Instructions

- Use the `episode(id: ID!)` field.
- Retrieve the following fields:
  - `id`
  - `name`
  - `air_date`
  - `episode`

## Example Query

The query retrieves information about the first episode.

```graphql
query {
  episode(id: 1) {
    id
    name
    air_date
    episode
  }
}
```
