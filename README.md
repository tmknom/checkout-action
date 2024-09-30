# checkout-action

A wrapper for [actions/checkout][checkout].

## Description

This action serves as a wrapper for [actions/checkout][checkout].
It allows you to checkout a Git repository at a specific version, similar to [actions/checkout][checkout].
The repository is checked out under `$GITHUB_WORKSPACE`, enabling your workflow to access it.

## Usage

```yaml
  steps:
    - name: Checkout
      uses: tmknom/checkout-action@v1
```

## Inputs and outputs

Inputs and outputs are exactly the same as the original [actions/checkout][checkout], including default values.

## Permissions

| Scope    | Access |
| :------- | :----- |
| contents | read   |

## FAQ

N/A

## Release notes

See [GitHub Releases][releases].

## License

Apache 2 Licensed. See [LICENSE](LICENSE) for full details.

[checkout]: https://github.com/actions/checkout
[releases]: https://github.com/tmknom/checkout-action/releases
