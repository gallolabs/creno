# medico
A tool to find a medical disponibility !

## Specs
- An API
- 2 resources :
  - The scrapers, custom and builtins
  - The "watchers"

 Scrapers based on Gallolabs Web Surfing.

 Watchers : Linked to a scraper, inject variables (input), get a list of availabilities (ex Array<{datetime, isReplacer}>), filters (days, max date, replacer, etc), compute news, store & notify.
