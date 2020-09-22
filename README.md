# Verify Package Version (cargo)

Verifies that the package version matches the current tag.

## Inputs

### `file`

**Required** Path to the package descriptor. Default `./Cargo.toml`.

## Outputs

### `version`

The version from the descriptor.

## Example usage

    uses: tcurdt/action-verify-version-cargo@master
