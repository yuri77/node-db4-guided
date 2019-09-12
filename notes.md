# Requirements

A client has hired you to track zoo animals.
For each individual animal, you must track that their name, species, and all zoos in which they have resided (including zoo name and address).

Determine the database tables necessary to track this information.

Label any relationships between table.

## A good data model

-capture all the information the system needs
-captures only the information the system needs <---Abstraction
-reflects reality (from the point of view of the system)
-is flexible, can evolve with the system
-guarantees data integrity,without sacrificing performance <-- using constrains
-is driven by the way we access the data

## Components

-entities (nouns: zoo, animal, species), like a resource ->tables
-properties -> columns or fields
-relationships -> foreign keys

## Workflow

- identify entities
- identity properties
- identity relationships

## Relationships

-one to one : rare
-one to many : this is it!
-many to many

## Mantras

- every table must have a Primary Key
  -one to many relationships needs a foreign key
  -the foreign keys goes to the many side
  -many to many needs a third table
