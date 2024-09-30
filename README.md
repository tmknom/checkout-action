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

## Versioning policy

This action follows a unique versioning policy.
It will never perform major version upgrades.
Raising the major version would negate the purpose of this action.

### Patch version upgrade

When a patch or minor version of [actions/checkout][checkout] is released,
this action applies the patch version upgrade.

### Minor version upgrade

When a major version of [actions/checkout][checkout] is released,
this action applies a minor version upgrade.

### Major version upgrade

Never.

## Release notes

See [GitHub Releases][releases].

## License

Apache 2 Licensed. See [LICENSE](LICENSE) for full details.

[checkout]: https://github.com/actions/checkout
[releases]: https://github.com/tmknom/checkout-action/releases
