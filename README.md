# PL-Literature-Review using a LLM
# Dylan Calderon
Repository that contains the Readme file for week 3 of CPSC354 Programming Languages

---

# Starting Question asked to Microsft's Copilot:

## How can functional programming paradigms improve code maintainability and reduce bugs in large-scale applications, particularly when using languages like JavaScript or Python that support multiple paradigms?

### 1. Immutability
- **Description**: Data cannot be changed once created.
- **Benefit**: Reduces side effects, making code easier to reason about.

### 2. Pure Functions
- **Description**: Functions with no side effects and no external state dependencies.
- **Benefit**: Easier to test and debug due to predictability.

### 3. Higher-Order Functions
- **Description**: Functions that take or return other functions.
- **Benefit**: Promotes code reuse and modularity.

### 4. First-Class Functions
- **Description**: Functions treated as first-class citizens.
- **Benefit**: Enables expressive and concise code.

### 5. Declarative Code
- **Description**: Focuses on what to do rather than how to do it.
- **Benefit**: More readable and easier to understand.

### 6. Function Composition
- **Description**: Combining simple functions to build complex ones.
- **Benefit**: Enhances code reuse and maintainability.

### 7. Concurrency
- **Description**: Naturally suited for concurrent programming.
- **Benefit**: More efficient and bug-free concurrent code.

## Do you see an introduction of new functional programming paradigms that will improve the code maintainability and other positive benefits in the future?

1. **Effect Systems**
   - **Description**: Effect systems extend type systems to track the side effects of functions, such as reading or writing to memory, at compile time. This allows developers to understand and manage the side effects of their code more effectively.
   - **Benefit**: Safer and more predictable code by managing side effects, reducing unexpected behaviors and making the code easier to reason about[^10^]¹¹.

2. **Dependent Types**
   - **Description**: Dependent types are types that depend on values. They allow for more expressive type systems where the type of a value can depend on another value. This is useful for encoding more precise invariants in the type system.
   - **Benefit**: Catches more errors at compile time, leading to robust code by ensuring that certain conditions are met before the code is executed¹⁸¹⁹.

3. **Algebraic Effects**
   - **Description**: Algebraic effects provide a way to define and handle side effects in a modular and composable manner. They separate the definition of effects from their implementation, allowing for more flexible and reusable code.
   - **Benefit**: Modular and composable side effect management, making it easier to reason about and manage side effects in a functional programming context¹².

4. **Functional Reactive Programming (FRP)**
   - **Description**: FRP is a programming paradigm that combines functional programming with reactive programming. It allows developers to work with time-varying values and event streams in a declarative manner.
   - **Benefit**: Simplifies interactive application development by providing a clear and concise way to handle asynchronous data flows and events¹³¹⁴.

5. **Category Theory**
   - **Description**: Category theory is a branch of mathematics that deals with abstract structures and relationships between them. In functional programming, it provides a framework for understanding and composing functions and data types in a highly abstract and reusable way.
   - **Benefit**: More reusable and composable code through abstract patterns, enabling developers to write more general and flexible code⁶⁸.

## Historically, how have the paradigms come to exist and is there a common pattern to the popularization of these paradigms that we can see repeated with the new and upcoming paradigms mentioned before?

### Common Patterns in Paradigm Popularization

1. **Addressing Specific Challenges**: New paradigms often arise to solve particular problems or inefficiencies in existing paradigms.
2. **Academic Research and Innovation**: Many paradigms originated in academic settings before gaining wider adoption in industry.
3. **Technological Advancements**: Advances in hardware and software technologies can spur the adoption of new paradigms.
4. **Community and Ecosystem Support**: The growth of supportive communities, libraries, and frameworks can accelerate the adoption of new paradigms.
5. **Industry Adoption and Success Stories**: Real-world success stories and industry adoption can validate and popularize new paradigms.

## What are some challenges in adopting new paradigms?

### 1. Learning Curve
- **Challenge**: Requires time and training for proficiency.

### 2. Legacy Code Integration
- **Challenge**: Complex integration with existing codebases.

### 3. Tooling and Ecosystem
- **Challenge**: Limited tools and libraries in early stages.

### 4. Performance Concerns
- **Challenge**: Potential performance overheads.

### 5. Cultural Resistance
- **Challenge**: Resistance to change within teams and organizations.

### 6. Debugging and Testing
- **Challenge**: Unfamiliar debugging and testing strategies.

### 7. Documentation and Best Practices
- **Challenge**: Lack of comprehensive resources and guidelines.

### 8. Interoperability
- **Challenge**: Ensuring compatibility with existing systems.

## Strategies to Overcome Challenges
- **Training and Education**: Invest in training programs.
- **Gradual Adoption**: Start with small projects.
- **Community Engagement**: Participate in communities and forums.
- **Tooling Investment**: Support development of tools and libraries.
- **Clear Communication**: Communicate benefits to stakeholders.

---

## References
Sure! Here are the references updated to include only Google Scholar articles, along with links to future paradigms:

## References

1. **A theory of gradual effect systems** - F. Bañados Schwerter, R. Garcia, É. Tanter
   - [Link](https://scholar.google.com/citations?user=vB4OU7sAAAAJ)
2. **Dependently typed programming in Agda** - U. Norell
   - [Link](https://scholar.google.com/citations?user=KEIhJYcAAAAJ)
3. **Programming and reasoning with algebraic effects and dependent types** - E. Brady
   - [Link](https://scholar.google.com/citations?user=v1butH8AAAAJ)
4. **Functional reactive programming from first principles** - Z. Wan, P. Hudak
   - [Link](https://scholar.google.com/citations?user=W6Mk2KwAAAAJ)
5. **Handlers of algebraic effects** - G. Plotkin, M. Pretnar
   - [Link](https://scholar.google.com/citations?user=VbovIwwAAAAJ)
6. **Towards a practical programming language based on dependent type theory** - U. Norell
   - [Link](https://scholar.google.com/citations?user=KEIhJYcAAAAJ)
7. **Functional reactive programming for embedded systems with GPGPUs** - Y. Sakurai, S. Moriguchi, T. Watanabe
   - [Link](https://scholar.google.com/citations?user=czIW23sAAAAJ)
8. **A comparative study of language support for generic programming** - R. Garcia, J. Jarvi, A. Lumsdaine, J. Siek, J. Willcock
   - [Link](https://scholar.google.com/citations?user=vB4OU7sAAAAJ)
9. **Simple unification-based type inference for GADTs** - S. Peyton Jones, D. Vytiniotis, S. Weirich, G. Washburn
   - [Link](https://scholar.google.com/citations?user=-vC_l2kAAAAJ)
10. **Functional reactive programming for small-scale embedded systems with recursive data types** - A. Yokoyama, S. Moriguchi, T. Watanabe
    - [Link](https://scholar.google.com/citations?user=czIW23sAAAAJ)

## References

1. **A theory of gradual effect systems** - F. Bañados Schwerter, R. Garcia, É. Tanter
   - [Link](https://scholar.google.com/citations?user=vB4OU7sAAAAJ)
2. **Dependently typed programming in Agda** - U. Norell
   - [Link](https://scholar.google.com/citations?user=KEIhJYcAAAAJ)
3. **Programming and reasoning with algebraic effects and dependent types** - E. Brady
   - [Link](https://scholar.google.com/citations?user=v1butH8AAAAJ)
4. **Functional reactive programming from first principles** - Z. Wan, P. Hudak
   - [Link](https://scholar.google.com/citations?user=W6Mk2KwAAAAJ)
5. **Handlers of algebraic effects** - G. Plotkin, M. Pretnar
   - [Link](https://scholar.google.com/citations?user=VbovIwwAAAAJ)
6. **Towards a practical programming language based on dependent type theory** - U. Norell
   - [Link](https://scholar.google.com/citations?user=KEIhJYcAAAAJ)
7. **Functional reactive programming for embedded systems with GPGPUs** - Y. Sakurai, S. Moriguchi, T. Watanabe
   - [Link](https://scholar.google.com/citations?user=czIW23sAAAAJ)
8. **A comparative study of language support for generic programming** - R. Garcia, J. Jarvi, A. Lumsdaine, J. Siek, J. Willcock
   - [Link](https://scholar.google.com/citations?user=vB4OU7sAAAAJ)
9. **Simple unification-based type inference for GADTs** - S. Peyton Jones, D. Vytiniotis, S. Weirich, G. Washburn
   - [Link](https://scholar.google.com/citations?user=-vC_l2kAAAAJ)
10. **Functional reactive programming for small-scale embedded systems with recursive data types** - A. Yokoyama, S. Moriguchi, T. Watanabe
    - [Link](https://scholar.google.com/citations?user=czIW23sAAAAJ)
