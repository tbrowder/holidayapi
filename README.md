[![Actions Status](https://github.com/tbrowder/HolidayAPI/workflows/test/badge.svg)](https://github.com/tbrowder/HolidayAPI/actions)

NAME
====

HolidayAPI - A Raku module to get and use data from <https://holidayapi.com>

SYNOPSIS
========

```raku
$ holiday-api
Usage: holiday-api <mode> [options]

Modes:
  get           - get the api data sets
  create        - produce the Holidays.rakumod.YYYY modules
  test          - get the free data sets from last year
  show-holidays - dumps the default holidays to STDOUT as a TOML file

Options:
  yyyy       - get or produce modules for year 2yyy [default:  previous year]
  dir=X      - output data to directory X           [default: './data']
  holidays=Y - define a TOML file ('Y') with the user's desired holiday list
  force      - overwrite an existing file
  quiet      - no informative messages
  debug      - for developer use

Note only the unique portion of a node or option need be entered.
```

DESCRIPTION
===========

This repo is a work-in-progress and I will add public code here only if there is interest. Please file an issue if you are.

Note even though the Holiday API has not changed, the JSON output format has changed since 2019 (for the better) and I am updating my using code appropriately.

AUTHOR
======

Tom Browder <tom.browder@cpan.org>

COPYRIGHT AND LICENSE
=====================

Copyright &#x00A9; 2020 Tom Browder

This library is free software; you can redistribute it or modify it under the Artistic License 2.0.

