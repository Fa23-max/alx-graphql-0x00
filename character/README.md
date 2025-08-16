# Character GraphQL Queries

This directory contains GraphQL queries to fetch character details by ID and by page along with their expected output.

## Files for Character by ID

- `character-id-1.graphql` - Query for character with ID 1
- `character-id-1-output.json` - Expected output for character with ID 1
- `character-id-2.graphql` - Query for character with ID 2
- `character-id-2-output.json` - Expected output for character with ID 2
- `character-id-3.graphql` - Query for character with ID 3
- `character-id-3-output.json` - Expected output for character with ID 3
- `character-id-4.graphql` - Query for character with ID 4
- `character-id-4-output.json` - Expected output for character with ID 4

## Files for Characters by Page

- `characters-page-1.graphql` - Query for characters on page 1
- `characters-page-1-output.json` - Expected output for characters on page 1
- `characters-page-2.graphql` - Query for characters on page 2
- `characters-page-2-output.json` - Expected output for characters on page 2
- `characters-page-3.graphql` - Query for characters on page 3
- `characters-page-3-output.json` - Expected output for characters on page 3
- `characters-page-4.graphql` - Query for characters on page 4
- `characters-page-4-output.json` - Expected output for characters on page 4

## Query Fields

Each character query fetches the following fields:
- id
- name
- status
- species (for single character)
- type (for single character)
- gender (for single character)
- image (for characters by page)