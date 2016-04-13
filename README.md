# README

## How to recreate:

```
$ rails new dry-reloading --skip-bundle --skip-active-record --skip-sprockets --skip-javascript --skip-test-unit --skip-turbolinks
```

### This works...

```irb
Types::Quantity[1]
reload!
Types::Quantity[1]
```
