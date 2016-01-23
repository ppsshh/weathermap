## weathermap

Builds GitHub-like weathermap using slim-template.

Sample usage:

`== slim :weathermap, locals: {stats: @my_stats, date_start: Date.today - 365, date_end: Date.today + 1}`

Sample `stats` hash:

```
{
  "2016-01-15" => {:add=>18, :del=>3, :cc=>1},
  "2016-01-18" => {:add=>87, :del=>27, :cc=>2},
  "2016-01-23" => {:add=>89, :del=>83, :cc=>5}
}
```
