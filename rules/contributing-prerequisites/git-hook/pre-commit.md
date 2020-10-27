# Git `pre-commit` Hook

Add a `git` `pre-commit` hook that runs `make`.

In your version of the project repository.

1. Create the file `.git/hooks/pre-commit` with this content:

    ```sh
    #!/bin/sh

    make
    ```

1. Make `.git/hooks/pre-commit` executable with this command:

    `chmod u=rwx .git/hooks/pre-commit`
