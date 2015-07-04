# coding-standards

This README will eventually outline coding standards and preferred best
practices which cannot be enforced through automated tools.

## .eslintrc usage example
```
    .
    ├── src
    │   ├── .eslintrc /* extends .eslintrc-client || .eslintrc-react */
    │   └── test
    │       └── .eslintrc /* extends .eslintrc-test */
    └── server
        ├── .eslintrc /* extends .eslintrc-server */
        └── test
            └── .eslintrc /* extends .eslintrc-test */
```
