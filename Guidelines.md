These guidelines should be seen as an extension to the "Google Swift Style Guide": www.google.github.io/swift/ ,
Kodeco: www.github.com/kodecocodes/swift-style-guide
and the "Apple API Design Guidelines": www.swift.org/documentation/api-design-guidelines/


## Vertical Whitespace

- **Rule**: Use **two blank lines** between type declarations (`struct`, `enum`, `class`), as well as between `protocol` and `extension` definitions.
- **Exceptions**:
  1. No blank lines are required if the type declaration immediately follows the file header or `import` statements.
  2. No blank lines are required if the type declaration is immediately followed by the end of its enclosing scope (e.g., a closing brace) or the end of the file.
- **Rationale**: Two blank lines enhance readability by visually separating distinct units of logic.

- **Rule**: Use two blank lines between functions, methods, or properties marked with `@ViewBuilder`
- **Rationale**: This spacing distinguishes complex view "blocks" from other code, improving maintainability

## Naming
### General naming conventions laid out in the aforementioned guideline references apply, with the following modifications:

- **Rule**: Functions, methods, and properties marked with `@ViewBuilder` must end with the suffix Block
- **Rationale**: The Block suffix clearly indicates that the entity produces a "block" forms the View hierarchy, distinguishing it from other utilities or data-focused entities.
