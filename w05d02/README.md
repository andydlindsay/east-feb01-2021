# W05D02 - Database Design

### To Do
- [ ] Primary Keys/Foreign Keys
- [ ] Naming Conventions
- [ ] Data Types
- [ ] Relationship Types
- [ ] Design Concepts
- [ ] Entity Relationship Diagrams
- [ ] Breakout: Convert 2 Spreadsheets [15 mins]
- [ ] Student Suggestion ERD(s)

### Primary Keys/Foreign Keys
* A way of uniquely identifying a record (cannot be null)
* auto-incrementing integer
* email
* FK is they MUST be the same type
* stay away from composite keys

`andy; DROP TABLE users;`

### Naming Conventions
* field/table names should snake_case SELECT SeleCT select 'space name'
* table names are always plural
* `id` for primary keys
* foreign table singular plus `_id` `user_id`

### Data Types
* Much more of a concern in the old days ~10 years ago
* When a record is created, even if the field is null, the db sets aside space
* integer, varchar, boolean
* phone numbers? postal codes? 'H0H 0H0' 90210 00210 555 555 5555 +1 (778)

### Relationship Types
* One-to-One - 1 record in the first table is related to only 1 record in the second
* One-to-Many/Many-to-One - 1 record in the 1st table is related to 1 or more records in the 2nd
* Many-to-Many - 1 or more records in the 1st is related to 1 or more records in the 2nd, requires a junction/join/bridge table

### Design Concepts
* Make fields required - the record in its initial state
* Default values - use intelligent default values to speed up inserts CURRENT_DATE, active boolean field `true`
* Calculated fields - field whose value can be derived from one or more other fields
`first_name` and `last_name` `full_name`
* Normalization - is to reduce redundancy and get to single source of truth
SUM(item.price)
for..of
reduce 100x slower
* Pull repeated values out of the table a lookup table
1 Toronto toronto TOrnato
2 Montreal
3 Ottawa
* Try not to delete anything DELETE, `active` boolean

### ERD's
* Entity Relationship Diagram
* How we lay out tables and the relationships between them

ALTER TABLE
UPDATE


### Breakout: Convert Two Spreadsheets
- [Gist with instruction](https://gist.github.com/andydlindsay/20e7305e853bad7b587f294b054cf8de)
















# 
