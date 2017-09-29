# pup-base

The base pup. All kennels must specify `pup-base` as the first pup in
`kennel.yml`.

## Variables

This kennel supports the following variables:
- `pup_base_vars_hostname` - the hostname for this machine.
- `pup_base_vars_sheepdoge_enable_cron` - whether we want to create a cron job
  to run `sheepdoge run --cron`.
- `pup_base_vars_sheepdoge_cron_interval_minutes` - how often to run `sheepdoge
  run --cron`, if enabled
- `pup_base_vars_sheepdoge_cron_interval_hours` - how often to run `sheepdoge
  run --cron`, if enabled

## Dependencies

`pup-base` has no dependencies. However, it must be included as the first role
in any `kennel.yml`.
