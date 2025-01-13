# medico
A tool to find a medical disponibility !

Will replace https://github.com/gallofeliz/doctolib-availabilities

## Specs
- An API
- Resources :
  - Users
  - The scrapers, custom and builtins
  - The "watchers"

 Scrapers based on Gallolabs Web Surfing.

 Watchers : Linked to a scraper, inject variables (input), get a list of availabilities (ex Array<{datetime, isReplacer}>), filters (days, max date, replacer, etc), compute news, store & notify.

All scoped to an user
