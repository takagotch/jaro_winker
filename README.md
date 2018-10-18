### jaro_winkler
---
https://github.com/tonytonyjan/jaro_winkler

```ruby
require 'jaro_winkler'
JaroWinkler.distance "MARTHA", "MARHTA"
JaroWinkler.distance "MARTHA", "martha", ignore_case: true
JaroWinkler.distance "MARTHA", "MARTHA", weight: 0.2
JaroWinkler.jaro_distance "MARHTA", "MARHTA"


```


```
gem install jaro_winkler
bundle exec rake benchmark


```


```

```

