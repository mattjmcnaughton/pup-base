# pup-base

The base pup. All kennels must specify `pup-base` as the first pup in
`kennel.yml`.

`pup-base` currently does not too much, but I want to preserve it, in case it
could be useful later. It seems like it would be much harder to add down the
road.

## Variables

This kennel supports the following variables:
- `pup_base_vars_hostname` - the hostname for this machine.

## Dependencies

`pup-base` has no dependencies. However, it must be included as the first role
in any `kennel.yml`.
