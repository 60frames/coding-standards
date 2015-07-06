# coding-standards

This README will eventually outline coding standards and preferred best
practices which cannot be enforced through automated tools.

## .eslintrc usage example
```
    .
    ├── src
    │   ├── .eslintrc /* extends .eslintrc-browser || .eslintrc-react */
    │   └── test
    │       └── .eslintrc /* extends .eslintrc-test */
    └── server
        ├── .eslintrc /* extends .eslintrc-node */
        └── test
            └── .eslintrc /* extends .eslintrc-test */
```
