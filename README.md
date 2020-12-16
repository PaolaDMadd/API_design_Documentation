
# API_design_Documentation
Design an API from Scratch

### Exercise 
We are building a neighborhood collaboration site and we want to make a system to keep track of people, houses, and addresses of those houses.

### Data information
- Each person has a name, age and number of people in their household
- Each house has an address and an owner
- Each address has a postcode and street address

### The REST API will need to enable users to:

- Store people, houses and addresses
- Look up a house, its address and owner
- Look up people in our neighborhood within certain age brackets and with specific household sizes

### Considerations 
1. Consider the type of data we will be storing and therefore the type of database we should implement (SQL vs NoSQL)
2. Create a schema for this database
3. Consider the requests our API should be capable of handling
4. List the routes you will need with their HTTP verb and path
5. Determine the responses that should be returned and the content types of these requests and responses
