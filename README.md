# action-kcov

A GitHub action for kcov

## Example usage

```yml
    - uses: actions/checkout@v2
    - name: get kcov version
        uses: crubalcaba/action-kcov@latest
        with:
            cli-args: "--version"
```
