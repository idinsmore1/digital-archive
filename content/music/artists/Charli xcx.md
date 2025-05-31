---
publish: true
---

```dataview
TABLE WITHOUT ID file.link as "Album", album_score as "Album Score", release_year as "Release Year", genre as "Genre"
from "music/albums"
where album_score != 0
and contains(artist, "Charli xcx")
sort album_score desc
limit 100
```
