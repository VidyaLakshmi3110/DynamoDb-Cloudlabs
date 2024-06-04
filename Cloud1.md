
# Introduction to Amazon DynamoDB 
---
## Overview
<p>Amazon DynamoDB is a fully managed NoSQL database service that provides fast and predictable performance with seamless scalability. You can use Amazon DynamoDB to create a database table that can store and retrieve any amount of data, and serve any level of request traffic. Amazon DynamoDB automatically spreads the data and traffic for the table over a sufficient number of servers to handle the request capacity specified by the customer and the amount of data stored, while maintaining consistent and fast performance<p>

### Core Components

1. **Tables**:
    -  Each table is a collection of items, similar to a table in a relational database.
    - Tables in DynamoDB are schema-less, meaning each item in the table can have different attributes, and attributes can vary in type.
    - Tables are organized based on primary keys, which uniquely identify each item in the table.
2. **Items**:
    - Items are individual records stored within a DynamoDB table. They represent a single data record or entity.
    - Each item consists of one or more attributes, which are the data fields or properties associated with the item.
    - Items can have different attributes, and there is no fixed schema for items within a table.
3. **Attributes:**
    - Attributes are the individual data fields or properties of an item in a DynamoDB table.
    - Each attribute has a name and a value. Attributes can be of various data types, including string, number, binary, Boolean, list, or map.
    - Attributes can be indexed for efficient querying and retrieval of data.
4. **Primary Keys:**
    - Every item in a DynamoDB table must have a primary key, which uniquely identifies the item within the table.
    - DynamoDB supports two types of primary keys:
        * Partition Key: A single attribute that uniquely identifies each item in the table. 
        * Composite Key: A combination of two attributes: a partition key (hash key) and a sort key (range key). Together, they uniquely identify each item in the table.

## Key Learnings:

- Understanding Amazon DynamoDB as a fully managed NoSQL database service.
- Learning about core components like tables, items, attributes, and primary keys.
- Exploring table creation, adding items, querying, and exploring DynamoDB with PartiQL queries.
- Exploring advanced features like backups, exporting data to Amazon S3
- Learning about table configurations, including indexes, monitoring, and global tables.
- Understanding various  table operations like item modification, deletion, and table deletion.



---


