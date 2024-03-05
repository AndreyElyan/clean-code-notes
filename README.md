# *Clean Code*


<details>
<summary><b>Course content index</b></summary>

- [Clean Code Fundamentals](#clean-code-fundamentals)
  - [What is/is not Clean Code](#what-isis-not-clean-code)
  - [Principles of Clean Code](#principles-of-clean-code)
- [Clean Code with JavaScript](#clean-code-with-javascript)
  - [Variable Naming](#variable-naming)
  - [Challenge: Variable Naming](#challenge-variable-naming)
  - [Clean Code in Booleans](#clean-code-in-booleans)
  - [Challenge: Clean Code in Booleans](#challenge-clean-code-in-booleans)
  - [Cause vs. Effect](#cause-vs-effect)
  - [Challenge: Cause vs. Effect](#challenge-cause-vs-effect)
  - [Code in English](#code-in-english)
  - [Challenge: Code in English](#challenge-code-in-english)
  - [Rules in Conditionals](#rules-in-conditionals)
  - [Challenge: Rules in Conditionals](#challenge-rules-in-conditionals)
  - [Parameters and Destructuring](#parameters-and-destructuring)
  - [Challenge: Parameters and Destructuring](#challenge-parameters-and-destructuring)
  - [Magic Numbers](#magic-numbers)
  - [Challenge: Magic Numbers](#challenge-magic-numbers)
  - [Comments vs Documentation](#comments-vs-documentation)
  - [Challenge: Comments vs Documentation](#challenge-comments-vs-documentation)
  - [Avoid Syntactic Sugars](#avoid-syntactic-sugars)
  - [Challenge: Avoid Syntactic Sugars](#challenge-avoid-syntactic-sugars)
- [Clean Code in React](#clean-code-in-react)
  - [Decoupling Components](#decoupling-components)
  - [Pure Components](#pure-components)
  - [Functions and Events in React](#functions-and-events-in-react)
  - [Composition vs Customization](#composition-vs-customization)
  - [Conditionals in Render](#conditionals-in-render)
- [Clean Code in Node.js](#clean-code-in-nodejs)
  - [Clean code in the back-end](#clean-code-in-the-back-end)
  - [SOLID Principles](#solid-principles)
  - [Practical Examples of SOLID](#practical-examples-of-solid)
  - [DDD Principles](#ddd-principles)
  - [Practical Example of DDD](#practical-example-of-ddd)
  - Uniting DDD with SOLID

</details>

## Clean Code Fundamentals

### What is/is not Clean Code

Characteristics of clean code:

- Easy to read
- Easy to maintain
- Predictable
- Trustworthy

What clean code **is not**:

- A manual
- Folder/file organization
- Small number of lines
- System architecture (Clean Architecture)
- Faster performance

Example: a project with many folders, files of 100 lines, and excellent performance may not be clean code, while another project with a single folder and files of 1000 lines is considered clean code for having the listed characteristics.

### Principles of Clean Code

- Automated tests to facilitate maintenance
- Code reviews for each new feature
- Code refactoring
- Simplicity - KISS: Keep It Simple and Stupid, do not think about solutions to problems that do not yet exist
- Short iterations to facilitate testing and review of changes

## Clean Code with JavaScript

### Variable Naming

- Avoid diminutives
- Prefer long names that explicitly state the meaning/use of the variable
- Avoid generic names

Practical examples in the [file](JavaScript/01_nomeclatura_variaveis.js).

### Challenge: Variable Naming

The [challenge](https://efficient-sloth-d85.notion.site/Desafio-Nomea-o-de-vari-veis-0a8484a8cdc743558d6677910590a874) consists of applying the knowledge from the previous lesson to the variables and object attributes in the [file](ignite-clean-code-desafios-main/desafios/01-nomenclatura-de-variaveis.ts).

### Clean Code in Booleans

- Always write in the form of a question, for example: `isLoading`, `isEnabled`, `isClosed`.
- Keep it as semantic as possible

Practical examples in the [file](JavaScript/02_booleanos.js).

### Challenge: Clean Code in Booleans

The [challenge](https://efficient-sloth-d85.notion.site/Desafio-Booleanos-aaab19f8e0394d20ae135c30094a7a3c) consists of applying the knowledge from the previous lesson to the variables in the [file](ignite-clean-code-desafios-main/desaf

ios/02-booleanos.ts).

### Cause vs. Effect

Name variables and functions so that they clearly indicate their purpose and context.

Practical examples in the [file](JavaScript/03_causa_efeito.js).

### Challenge: Cause vs. Effect

The [challenge](https://efficient-sloth-d85.notion.site/Desafio-Causa-vs-Efeito-10f8b94e572d4b13bfb187c870ae98f3) consists of applying the knowledge from the previous lesson to the variables and function names in the [file](ignite-clean-code-desafios-main/desafios/03-causa-efeito.ts).

### Code in English

- Use English for code, comments, and documentation to facilitate understanding and maintainability by a wider audience.
- Avoid using mixed languages in the same codebase, as it can make understanding difficult.

Practical examples in the [file](JavaScript/04_english_code.js).

### Challenge: Code in English

The [challenge](https://efficient-sloth-d85.notion.site/Desafio-C-digo-em-Ingl-s-6b065b70b05747dcb5d02f52923a271e) consists of applying the knowledge from the previous lesson to translate the variables and function names in the [file](ignite-clean-code-desafios-main/desafios/04-codigo-em-ingles.ts).

### Rules in Conditionals

- Use positive and affirmative conditions whenever possible to make code more readable.
- Avoid double negations, as they make the code harder to understand.

Practical examples in the [file](JavaScript/05_regras_condicionais.js).

### Challenge: Rules in Conditionals

The [challenge](https://efficient-sloth-d85.notion.site/Desafio-Regras-Condicionais-380d460b8f014ae8a8b32ac05e1b4e49) consists of applying the knowledge from the previous lesson to simplify the conditional expressions in the [file](ignite-clean-code-desafios-main/desafios/05-regras-condicionais.ts).

### Parameters and Destructuring

- Use object destructuring for functions with multiple parameters to improve readability and maintainability.
- Use default values for parameters that have a common value in most use cases.

Practical examples in the [file](JavaScript/06_parametros_desestruturacao.js).

### Challenge: Parameters and Destructuring

The [challenge](https://efficient-sloth-d85.notion.site/Desafio-Par-metros-e-Destrutura-o-1b46bfe73cd84c1e8963db839628e556) consists of applying the knowledge from the previous lesson to improve the function parameters in the [file](ignite-clean-code-desafios-main/desafios/06-parametros-desestruturacao.ts).

### Magic Numbers

- Avoid using magic numbers in the code.
- Use constants or variables with descriptive names to represent these values.

Practical examples in the [file](JavaScript/07_numeros_magicos.js).

### Challenge: Magic Numbers

The [challenge](https://efficient-sloth-d85.notion.site/Desafio-N-meros-M-gicos-5deacfd3f6b14df9831c0cdd24c02c4a) consists of applying the knowledge from the previous lesson to replace the magic numbers in the [file](ignite-clean-code-desafios-main/desafios/07-numeros-magicos.ts) with descriptive constants.

### Comments vs Documentation

- Comments should be avoided whenever possible, as they can become outdated and misleading.
- Prefer self-explanatory code and use comments only when necessary to clarify complex or non-intuitive parts of the code.
- Documentation should focus on the why and not the how, explaining the reasoning behind the code's design decisions.

Practical examples in the [file](JavaScript/08_comentarios_documentacao.js).

### Challenge: Comments vs Documentation

The [challenge](https://efficient-sloth-d85.notion.site/Desafio-Coment-rios-vs-Documenta-o-bba270be91264347b4226b3c45e6c1b6) consists of applying the knowledge from the previous lesson to improve the comments and documentation in the [file](ignite-clean-code-desafios-main/desafios/08-comentarios-documentacao.ts).

### Avoid Syntactic Sugars

- Avoid using syntactic sugars that may reduce readability and maintainability, such as arrow functions for simple operations or complex object destructuring.

Practical examples in the [file](JavaScript/09_acucar_sintatico.js).

### Challenge: Avoid Syntactic Sugars

The [challenge](https://efficient-sloth-d85.notion.site/Desafio-Evitar-A-ucares-Sint-ticos-f5ae36da24a349d3bc0e7f0a64c56f38) consists of applying the knowledge from the previous lesson to replace the syntactic sugars in the [file](ignite-clean-code-desafios-main/desafios/09-acucar-sintatico.ts) with more explicit and readable code.

## Clean Code in React

### Decoupling Components

- Create components that are as independent as possible to facilitate reuse and maintenance.
- Avoid components that depend heavily on the context in which they are used.

Practical examples in the [file](React/01_desacoplamento_componentes.js).

### Pure Components

- Use pure components whenever possible to avoid unnecessary re-renders and improve performance.
- Avoid using class components unless necessary, as functional components are simpler and more predictable.

Practical examples in the [file](React/02_componentes_puros.js).

### Functions and Events in React

- Avoid using anonymous functions in JSX to improve readability and performance.
- Use named functions for event handlers to make the code easier to understand and debug.

Practical examples in the [file](React/03_funcoes_eventos.js).

### Composition vs Customization

- Prefer composition over customization to create more flexible and maintainable components.
- Use props to customize the behavior and appearance of components instead of creating multiple similar components with minor differences.

Practical examples in the [file](React/04_composicao_customizacao.js).

### Conditionals in Render

- Avoid complex conditionals in the render method to improve readability and maintainability.
- Use conditional rendering techniques such as ternary operators or logical && to simplify the code.

Practical examples in the [file](React/05_condicionais_render.js).

## Clean Code in Node.js

### Clean code in the back-end

- Apply the same clean code principles used in front-end development to back-end development to improve maintainability and readability.
- Use meaningful variable and function names, avoid unnecessary complexity, and write clear and concise code.

### SOLID Principles

- SOLID principles are a set of five design principles that aim to make software design more understandable, flexible, and maintainable.
- **Single Responsibility Principle (SRP)**: A class should have only one reason to change, meaning it should have only one responsibility.
- **Open/Closed Principle (OCP)**: Software entities should be open for extension but closed for modification, meaning they should be easily extendable without modifying the existing code.
- **Liskov Substitution Principle (

LSP)**: Objects of a superclass should be replaceable with objects of its subclasses without affecting the correctness of the program.
- **Interface Segregation Principle (ISP)**: A client should not be forced to implement an interface that it does not use, meaning interfaces should be specific to the client's needs.
- **Dependency Inversion Principle (DIP)**: High-level modules should not depend on low-level modules. Both should depend on abstractions, meaning the dependency should be on interfaces or abstract classes rather than concrete implementations.

### Implementing Clean Architecture in Node.js

- Clean Architecture is a software design philosophy that separates the application into layers, with each layer having a specific responsibility and dependency direction.
- **Entities**: Represent the core business objects and contain enterprise-wide business rules.
- **Use Cases**: Contain application-specific business rules and orchestrate the flow of data between entities and external systems.
- **Interfaces**: Define how external systems interact with the application, such as APIs or databases.
- **Frameworks & Drivers**: Contain the implementation details of external systems, such as web frameworks or database drivers.
- By separating concerns and defining clear boundaries between layers, Clean Architecture makes the application more maintainable, testable, and scalable.

## Refactoring Techniques

### Extract Function

- Extracting a function from existing code can improve readability and maintainability by breaking down complex logic into smaller, more manageable parts.
- Identify repeated or complex code blocks that can be extracted into a separate function with a descriptive name.

Practical examples in the [file](Refactoring/01_extract_function.js).

### Rename Variable

- Choosing descriptive and meaningful variable names can improve code readability and maintainability.
- Rename variables to better reflect their purpose and context within the code.

Practical examples in the [file](Refactoring/02_rename_variable.js).

### Inline Function

- Inlining a function involves replacing a function call with the function's implementation to simplify the code.
- Use this technique when a function call adds unnecessary complexity or when the function's logic is simple and easy to understand inline.

Practical examples in the [file](Refactoring/03_inline_function.js).

### Extract Variable

- Extracting a variable from an expression can improve readability and maintainability by giving a name to the intermediate result.
- Identify complex or repeated expressions that can be extracted into a variable with a descriptive name.

Practical examples in the [file](Refactoring/04_extract_variable.js).

### Inline Variable

- Inlining a variable involves replacing a variable with its value to simplify the code.
- Use this technique when a variable adds unnecessary complexity or when its value is simple and can be easily understood inline.

Practical examples in the [file](Refactoring/05_inline_variable.js).

## Final Project

### Refactoring Legacy Code

- Refactoring legacy code involves improving the code's structure, readability, and maintainability without changing its external behavior.
- Identify code smells, such as duplicated code, long methods, or complex conditionals, and apply refactoring techniques to address them.

Practical examples in the [file](Refactoring/06_refactoring_legacy_code.js).

---

These lessons cover a range of topics related to clean code and refactoring techniques, including naming conventions, code organization, SOLID principles, and Clean Architecture. By applying these principles and techniques, you can write code that is easier to understand, maintain, and extend.
