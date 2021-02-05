# Function Best Practices
1. Give your functions precise verb / action-based names (always start with a verb!).
2. Use `camelCase`
3. Properly indent function code
4. Functions should focus on a single task: returning a value or causing a side effect. *Break your function into additional smaller functions if you find it doing two or more things.*
    - e.g. return a value, log a message should be two different helper functions
5. Data needed by Functions should be passed in as parameters/arguments (i.e. local scope) instead of being accessed directly