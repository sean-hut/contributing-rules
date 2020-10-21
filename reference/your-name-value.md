# What To Enter For `<your-name>`

1. Look up the name in your git configuration file.

    This will be in one of your git configuration files in order of highest to lowest precident:
    - .git/config
        - This one is project specific in your project repository.
    - ~/.gitconfig
    - ~/.config/git/config
    - /etc/gitconfig

    For example:

    ```
    [user]
        name = "John Smith"
    ```

2. Do your own conversion and put the result in for `<your-name>`.

    The conversion is:
    - all lowercase
    - replace each space with a `-`

    So for example `John Smith` becomes `john-smith`.
