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
- Decompose problems into smaller components through systematic analysis, using constructs such as procedures, modules, and/or objects (3A-AP-17) https://www.csteachers.org/page/standards
- Create artifacts by using procedures within a program, combinations of data and procedures, or independent but interrelated programs (3A-AP-18) https://www.csteachers.org/page/standards
- Construct solutions to problems using student-created components, such as procedures, modules and/or objects (3B-AP-14) https://www.csteachers.org/page/standards
- Demonstrate code reuse by creating programming solutions using libraries and APIs (3B-AP-16) https://www.csteachers.org/page/standards
- Use lists to simplify solutions, generalizing computational problems instead of repeatedly using simple variables (3A-AP-14) https://www.csteachers.org/page/standards
- Create computational models that represent the relationships among different elements of data collected from a phenomenon or process (3A-DA-12) https://www.csteachers.org/page/standards

## Resources
- https://www.c-sharpcorner.com/article/func-delegate-in-c-sharp/
- https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/operators/lambda-expressions

Copyright &copy; 2025 Knight Moves. All Rights Reserved.
