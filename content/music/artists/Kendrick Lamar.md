---
publish: true
---
<!-- QueryToSerialize: TABLE WITHOUT ID file.link as "album", album_score as "album score", release_year as "release year", genre as "genre" from "music/albums" where album_score != 0 and contains(artist, "Kendrick Lamar") sort album_score desc limit 100 -->
<!-- SerializedQuery: TABLE WITHOUT ID file.link as "album", album_score as "album score", release_year as "release year", genre as "genre" from "music/albums" where album_score != 0 and contains(artist, "Kendrick Lamar") sort album_score desc limit 100 -->

| album                                                            | album score | release year | genre |
| ---------------------------------------------------------------- | ----------- | ------------ | ----- |
| [[To Pimp A Butterfly]]     | 9.3         | 2015         | Rap   |
| [[good kid m.A.A.d city]] | 9           | 2012         | Rap   |
<!-- SerializedQuery END -->

