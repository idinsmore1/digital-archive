---
publish: true
---
<!-- QueryToSerialize: TABLE WITHOUT ID file.link as "album", album_score as "album score", release_year as "release year", genre as "genre" from "music/albums" where album_score != 0 and contains(artist, "Magdalena Bay") sort album_score desc limit 100 -->
<!-- SerializedQuery: TABLE WITHOUT ID file.link as "album", album_score as "album score", release_year as "release year", genre as "genre" from "music/albums" where album_score != 0 and contains(artist, "Magdalena Bay") sort album_score desc limit 100 -->

| album | album score | release year | genre |
| ----- | ----------- | ------------ | ----- |
<!-- SerializedQuery END -->

