# Writing-Readable-Code-for-Beginners
It is a guide that helps coding beginners write clear, self-explanatory variable names, functions, and comments so their teammates and future selves can easily read and maintain their code without getting lost in messy logic.
## Clean Code Best Practices & Tips

Writing code that a computer can execute is easy; writing code that humans can easily understand is the real skill. Follow these core habits when writing your programs:

Use descriptive, intention-revealing names: Name variables and functions after what they represent or do (e.g., use `totalPrice` or `calculateTax()` instead of `x` or `doStuff()`).
Keep functions small and focused:** Each function should do one specific job well. If a function grows past 20–30 lines or handles multiple tasks, split it into smaller helper functions.
Avoid magic numbers: Replace unexplained hardcoded numbers with named constants (e.g., use `MAX_LOGIN_ATTEMPTS = 3` instead of a bare `3` inside an `if` statement).
Comment the *why*, not the *what*: Do not write comments that simply repeat what the code already says (e.g., `// add 1 to count`). Use comments to explain tricky business logic or *why* a specific workaround was needed.
Format consistently: Stick to consistent indentation, spacing, and naming conventions (like `camelCase` or `snake_case`) throughout your entire file so your code looks unified.
