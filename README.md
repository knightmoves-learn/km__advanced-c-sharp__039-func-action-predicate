# 039 Func Action Predicate

## Lecture

[![# Func Action Predicate)](https://img.youtube.com/vi/v1dbW26xRQQ/0.jpg)](https://www.youtube.com/watch?v=v1dbW26xRQQ)

## Instructions

- In `HomeEnergyApi/Models/HomeRepository`
  - Modify the `FindByOwnerLastName()` method
    - Create a new action that takes an argument of type `string`, and writes that string to the console
    - Call your new action with the argument `$"Finding by owner's last name: {ownerLastName}"`
    - Create a new preidcate that takes an argument of type `string` and returns false if the string is a single character, or false otherwise
    - In the `Where()` clause of the return statement, modify so that we are only returning Homes where the `OwnerLastName` property is NOT a single character, using your newly created predicate

## Additional Information

- Do not remove or modify anything in `HomeEnergyApi.Tests`
- Some Models may have changed for this lesson from the last, as always all code in the lesson repository is available to view
- Along with `using` statements being added, any packages needed for the assignment have been pre-installed for you, however in the future you may need to add these yourself

## Building toward CSTA Standards:

- Document design decisions using text, graphics, presentations, and/or demonstrations in the development of complex programs (3A-AP-23) https://www.csteachers.org/page/standards
- Systematically design and develop programs for broad audiences by incorporating feedback from users (3A-AP-19) https://www.csteachers.org/page/standards

## Resources

- https://swagger.io/
- https://github.com/dotnet/aspnet-api-versioning/wiki/API-Documentation

Copyright &copy; 2025 Knight Moves. All Rights Reserved.
