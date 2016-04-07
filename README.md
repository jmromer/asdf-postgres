# asdf-postgres

Postgresql plugin for [asdf](https://github.com/asdf-vm/asdf) version manager

## Install

```
asdf plugin-add postgresql https://github.com/smashedtoatoms/asdf-postgres.git
```

## Gotchas
This requires that you have xcode installed on a mac.  It hasn't been tested on linux, so if you use this and find there are requirements, please let me know.  If it does anything weird, open a ticket or submit a pull request.

## Use

Check [asdf](https://github.com/asdf-vm/asdf) readme for instructions on how to install & manage versions of Postgres.

When installing Postgres using `asdf install`, you can pass custom configure options with the following env vars:

* `POSTGRES_CONFIGURE_OPTIONS` - use only your configure options
* `POSTGRES_EXTRA_CONFIGURE_OPTIONS` - append these configure options along with ones that this plugin already uses
