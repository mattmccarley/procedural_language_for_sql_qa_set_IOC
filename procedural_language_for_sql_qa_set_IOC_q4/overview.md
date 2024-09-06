# Question 4

## Prompt
```
Describe the difference between IN, OUT, and INOUT parameters in stored procedures and explain when each type would be used.
```

## Answers

- IN parameters:
- Used to pass values into the stored procedure.
- Cannot be modified within the procedure.
- Used when the procedure needs to receive input data for processing.
- OUT parameters:
- Used to return values from the stored procedure to the calling program.
- Can be modified within the procedure but their initial values are not accessible.
- Used when the procedure needs to return computed or retrieved data.
- INOUT parameters:
- Combine the functionality of both IN and OUT parameters.
- Can pass values into the procedure and return modified values.
- Used when a parameter needs to be both input and output, such as for updating existing values.
