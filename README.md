## Web HW2 

### Spring Boot

I also put a ProductDTO besides ProductDto as a record to simplify responses.
I asked ChatGPT what are the advantages of record over class in this structure and got this:
Using Java records instead of classes for Spring Boot request and response structures offers several advantages:

1. **Conciseness**: Records are more concise than traditional Java classes. They automatically generate boilerplate code for constructors, getters, `equals()`, `hashCode()`, and `toString()` methods, reducing the amount of code you need to write and maintain.

2. **Readability**: Records improve code readability by making the intent of the code clearer. With records, you can quickly understand the structure of the data being passed around in your application.

3. **Immutability**: Records are immutable by default, meaning that their state cannot be changed after instantiation. This helps enforce data integrity and prevents accidental modification of data, which can lead to bugs and unexpected behavior.

4. **Built-in Value Semantics**: Records have built-in support for value semantics, meaning that two record instances with the same values are considered equal. This simplifies comparisons and makes it easier to work with data structures like sets and maps.

5. **Integration with Frameworks**: Many frameworks, including Spring Boot, have built-in support for records. Spring Boot can automatically serialize and deserialize records to and from JSON, making it easier to work with RESTful APIs.

Overall, using records in Spring Boot applications can lead to cleaner, more maintainable code with less boilerplate, improved readability, and better integration with frameworks and libraries.