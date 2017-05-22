# Mystery Science Theater 3000 episode guide dataset

## 5/22/2017 Major revisions include:

+ Add IMDB ids under "imdb"
+ Removed extra movie production details from "movie_details"(a lot of conflicting sources/missing info)
+ Fix/change spelling/date discrepancies

## 5/1/2017 Major revisions include:

+ Addition of Season 11 episodes
+ Add movie_details from [Wikipedia][wikipedia]
+ Change date format
+ Fix/change spelling/date discrepancies


*From original MST3K JSON created by [https://github.com/malantonio/mst3k-episodes][https://github.com/malantonio/mst3k-episodes]. (Note: Below example has newly added "movie_details" and edited "air_date" format):*

I couldn't find a list like this anywhere, so why not? Movie titles are pulled
from complete series torrent; shorts from [Satellite News episode guide][sneq].
This list doesn't include the [1996 movie][mst3ktm].

## example

```json
{
  "id": "S06E21",
  "season": 6,
  "episode": 21,
  "movie": "The Beast Of Yucca Flats",
  "imdb": "tt0054673",
  "movie_details": "1961, B&W, USA",
  "shorts": ["Money Talks!", "Progress Island, USA"],
  "air_date": "01-21-1995"
}
```

[sneq]: http://www.mst3kinfo.com/?page_id=20112
[mst3ktm]: http://www.imdb.com/title/tt0117128
[wikipedia]: https://en.wikipedia.org/wiki/List_of_Mystery_Science_Theater_3000_episodes
[https://github.com/malantonio/mst3k-episodes]: https://github.com/malantonio/mst3k-episodes