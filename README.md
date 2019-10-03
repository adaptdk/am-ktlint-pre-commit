# am-ktlint-pre-commit
For setting up pre-commit for ktlint formatting. 

## Installation

```bash
$ brew list ktlint | brew upgrade ktlint || brew install ktlint && curl -s -L "https://raw.githubusercontent.com/adaptdk/am-ktlint-pre-commit/master/pre-commit" > .git/hooks/pre-commit && chmod 755 .git/hooks/pre-commit
```
