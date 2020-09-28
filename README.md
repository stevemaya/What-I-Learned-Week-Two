# What-I-Learned-Week-Two

### Booleans
  - **Booleans** are values that can be only one of two things: `true` or `false`.
  - Are essential for conditional statements to work.
    - ***Logical operators***
    - `&&`: *And* is used with two or more values (operands), and only evaluates to true if all the operands are truthful.
    - `||`: *OR* is used with two or more values, but it evaluates to true if any of the operands (values) are true, so only evaluates to false if both operands are false.
    - `!`: *Not* Using the ! operator in front of a value will convert it to a Boolean and return an opposite value. It means that a true value will return false, and a false will return true.

### IF, Else, and Else IFs  
  - `IF`: is marked up with the simple letters if, followed up with an expression that will be evaluated to either true or false. The result will be a boolean. Then inside the curly braces you place all the code that should run if the expression is evaluated to true. If false the code inside the block will not be executed.
  - `Else`:If an if statement is true the code inside its curly braces will be run and if false nothing will happen. Except if an else statement is put directly afterwards. Then the code inside the else's block will run.
  - `Else IF`: is used when you want to guarantee that only one of the if statements are executed, even if multiple of them could result in true. When one of them is evaluated to true the code inside is executed, and then the rest of the else if statements are skipped over.