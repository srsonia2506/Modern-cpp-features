# Modern C++ Features

## C++23
### Language Features:
- Deduction Guides for std::pair and std::tuple: Simplifies the creation of these types.
- Expanded constexpr: Further enhancements to constexpr, allowing more complex constructs.
- New Standard Attributes: [[nodiscard]] and [[likely]] can now be applied to more contexts.
- Type Traits Enhancements: New type traits for better type manipulation.
- Explicit Object Parameters: Allows constructors to have explicit parameters for better clarity.
- std::move_only: A new type trait to indicate move-only types.
  
### Library Features:
- std::expected: Represents a value that may be in an error state, similar to std::optional but for error handling.
- std::ranges: Further enhancements to the Ranges library introduced in C++20.
- std::chrono: New features and improvements in the Chrono library.
- std::print: A new way to print formatted output.
- std::array: New member functions and enhancements.
- std::iterator: New iterator concepts and enhancements.

## C++20
### Language Features:
- Concepts: A way to specify template requirements more clearly.
- Ranges: A new way to work with sequences of values, providing a more expressive syntax.
- Coroutines: Introduces support for asynchronous programming with co_await, co_yield, and co_return.
- Modules: A new way to organize and encapsulate code, improving compile times and modularity.
- Three-way Comparison Operator (<=>): Also known as the spaceship operator, simplifies the implementation of comparison operators.
- Constexpr Enhancements: More features allowed in constexpr functions, including dynamic memory allocation.
- New Standard Attributes: [[likely]] and [[unlikely]] to provide hints to the compiler about branch prediction.
- Expanded constexpr: More constructs can be used in constexpr contexts.
  
### Library Features:
- std::format: A new way to format strings, similar to Python's f-strings.
- std::span: A lightweight view over a contiguous sequence of objects.
- std::bitset: New member functions and enhancements.
- std::atomic: New atomic operations and types.
- std::syncstream: A synchronized output stream for thread-safe output.
- std::barrier: A synchronization primitive for managing multiple threads.

## C++17 Features
### Language Features:
- Inline Variables: Allows variables to be defined inline in header files.
- Structured Bindings: Enables unpacking of tuple-like objects into individual variables.
- If and Switch with Initializers: Allows initialization of variables within the if and switch statements.
- constexpr if: Conditional compilation based on compile-time conditions.
- Template Argument Deduction for Class Templates: Simplifies template instantiation by allowing deduction of template parameters.
- Fold Expressions: Simplifies the syntax for variadic templates.
- std::optional: Represents an optional value that may or may not be present.
- std::variant: A type-safe union that can hold one of several types.
- std::any: A type-safe container for single values of any type.
  
### Library Features:
- std::string_view: A lightweight, non-owning view of a string.
- std::filesystem: Provides facilities for performing operations on file systems and their components.
- std::parallel algorithms: Introduces parallel versions of standard algorithms.
- std::shared_mutex: A new synchronization primitive that allows multiple readers or one writer.
- std::optional, std::variant, std::any: New utility types for better type handling.
