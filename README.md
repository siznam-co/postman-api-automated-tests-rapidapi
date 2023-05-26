# postman-api-automated-tests-rapidapi
Movie room apis
Workflow, Folder Structure and api tests.
rapidapi.com
Movie Application APIs automation.

Search
Add folder description…
Search Basic (FREE)
Add folder description…
GET
Search Basic (FREE) without country params
{{search_basic}}?service=netflix&type=movie&genre=18&page=1&output_language=en&language=en
Add request description…
Request Headers
X-RapidAPI-Key
{{X-RapidAPI-Key}}

X-RapidAPI-Host
{{X-RapidAPI-Host}}

Query Params
country
us

service
netflix

type
movie

genre
18

page
1

output_language
en

language
en

GET
Search Basic (FREE) with wrong country params
{{search_basic}}?country=pk&service=netflix&type=movie&genre=18&page=1&output_language=en&language=en
Add request description…
Request Headers
X-RapidAPI-Key
{{X-RapidAPI-Key}}

X-RapidAPI-Host
{{X-RapidAPI-Host}}

Query Params
country
pk

service
netflix

type
movie

genre
18

page
1

output_language
en

language
en

GET
Search Basic (FREE) without service params
{{search_basic}}?country=us&type=movie&genre=18&page=1&output_language=en&language=en
Add request description…
Request Headers
X-RapidAPI-Key
{{X-RapidAPI-Key}}

X-RapidAPI-Host
{{X-RapidAPI-Host}}

Query Params
country
us

service
netflix

type
movie

genre
18

page
1

output_language
en

language
en

GET
Search Basic (FREE) with wrong service params
{{search_basic}}?country=us&service=netf&type=movie&genre=18&page=1&output_language=en&language=en
Add request description…
Request Headers
X-RapidAPI-Key
{{X-RapidAPI-Key}}

X-RapidAPI-Host
{{X-RapidAPI-Host}}

Query Params
country
us

service
netf

type
movie

genre
18

page
1

output_language
en

language
en

GET
Search Basic (FREE) without type params
{{search_basic}}?country=us&service=netflix&genre=18&page=1&output_language=en&language=en
Add request description…
Request Headers
X-RapidAPI-Key
{{X-RapidAPI-Key}}

X-RapidAPI-Host
{{X-RapidAPI-Host}}

Query Params
country
us

service
netflix

type
movie

genre
18

page
1

output_language
en

language
en

GET
Search Basic (FREE) with wrong type params
{{search_basic}}?country=us&service=netflix&type=mov&genre=18&page=1&output_language=en&language=en
Add request description…
Request Headers
X-RapidAPI-Key
{{X-RapidAPI-Key}}

X-RapidAPI-Host
{{X-RapidAPI-Host}}

Query Params
country
us

service
netflix

type
mov

genre
18

page
1

output_language
en

language
en

GET
Search Basic (FREE) without genre params
{{search_basic}}?country=us&service=netflix&type=movie&page=1&output_language=en&language=en
Add request description…
Request Headers
X-RapidAPI-Key
{{X-RapidAPI-Key}}

X-RapidAPI-Host
{{X-RapidAPI-Host}}

Query Params
country
us

service
netflix

type
movie

genre
18

Optional

page
1

output_language
en

language
en

GET
Search Basic (FREE) with wrong genre params
{{search_basic}}?country=us&service=netflix&type=movie&genre=-18&page=1&output_language=en&language=en
Add request description…
Request Headers
X-RapidAPI-Key
{{X-RapidAPI-Key}}

X-RapidAPI-Host
{{X-RapidAPI-Host}}

Query Params
country
us

service
netflix

type
movie

genre
-18

page
1

output_language
en

language
en

GET
Search Basic (FREE) without page params
{{search_basic}}?country=us&service=netflix&type=movie&genre=18&output_language=en&language=en
Add request description…
Request Headers
X-RapidAPI-Key
{{X-RapidAPI-Key}}

X-RapidAPI-Host
{{X-RapidAPI-Host}}

Query Params
country
us

service
netflix

type
movie

genre
18

page
1

Optional

output_language
en

language
en

GET
Search Basic (FREE) with wrong page params
{{search_basic}}?country=us&service=netflix&type=movie&genre=18&page=-10&output_language=en&language=en
Add request description…
Request Headers
X-RapidAPI-Key
{{X-RapidAPI-Key}}

X-RapidAPI-Host
{{X-RapidAPI-Host}}

Query Params
country
us

service
netflix

type
movie

genre
18

page
-10

Optional

output_language
en

language
en

GET
Search Basic (FREE) without output_language params
{{search_basic}}?country=us&service=netflix&type=movie&genre=18&page=1&language=en
Add request description…
Request Headers
X-RapidAPI-Key
{{X-RapidAPI-Key}}

X-RapidAPI-Host
{{X-RapidAPI-Host}}

Query Params
country
us

service
netflix

type
movie

genre
18

page
1

output_language
en

Optional

language
en

GET
Search Basic (FREE) with wrong output_language params
{{search_basic}}?country=us&service=netflix&type=movie&genre=18&page=1&output_language=language&language=en
Add request description…
Request Headers
X-RapidAPI-Key
{{X-RapidAPI-Key}}

X-RapidAPI-Host
{{X-RapidAPI-Host}}

Query Params
country
us

service
netflix

type
movie

genre
18

page
1

output_language
language

Optional

language
en

GET
Search Basic (FREE) without language params
{{search_basic}}?country=us&service=netflix&type=movie&genre=18&page=1&output_language=en
Add request description…
Request Headers
X-RapidAPI-Key
{{X-RapidAPI-Key}}

X-RapidAPI-Host
{{X-RapidAPI-Host}}

Query Params
country
us

service
netflix

type
movie

genre
18

page
1

output_language
en

language
en

Optional

GET
Search Basic (FREE) with wrong language params
{{search_basic}}?country=us&service=netflix&type=movie&genre=18&page=1&output_language=en&language=wLang
Add request description…
Request Headers
X-RapidAPI-Key
{{X-RapidAPI-Key}}

X-RapidAPI-Host
{{X-RapidAPI-Host}}

Query Params
country
us

service
netflix

type
movie

genre
18

page
1

output_language
en

language
wLang

Optional

GET
Search Basic (FREE) without X-RapidAPI-Key Headers
{{search_basic}}?country=us&service=netflix&type=movie&genre=18&page=1&output_language=en&language=en
Add request description…
Request Headers
X-RapidAPI-Host
{{X-RapidAPI-Host}}

Query Params
country
us

service
netflix

type
movie

genre
18

page
1

output_language
en

language
en

GET
Search Basic (FREE) with wrong X-RapidAPI-Key Headers
{{search_basic}}?country=us&service=netflix&type=movie&genre=18&page=1&output_language=en&language=en
Add request description…
Request Headers
X-RapidAPI-Key
8a2c6ddf34msh8ebb9066ad9470ep132001

X-RapidAPI-Host
{{X-RapidAPI-Host}}

Query Params
country
us

service
netflix

type
movie

genre
18

page
1

output_language
en

language
en

GET
Search Basic (FREE) without X-RapidAPI-Host Headers
{{search_basic}}?country=us&service=netflix&type=movie&genre=18&page=1&output_language=en&language=en
Add request description…
Request Headers
X-RapidAPI-Key
{{X-RapidAPI-Key}}

Query Params
country
us

service
netflix

type
movie

genre
18

page
1

output_language
en

language
en

GET
Search Basic (FREE) with wrong X-RapidAPI-Host Headers
{{search_basic}}?country=us&service=netflix&type=movie&genre=18&page=1&output_language=en&language=en
Add request description…
Request Headers
X-RapidAPI-Key
{{X-RapidAPI-Key}}

X-RapidAPI-Host
streaming-availability

Query Params
country
us

service
netflix

type
movie

genre
18

page
1

output_language
en

language
en

Optional

GET
Search Basic (FREE) without Headers
{{search_basic}}?country=us&service=netflix&type=movie&genre=18&page=1&output_language=en&language=en
Add request description…
Query Params
country
us

service
netflix

type
movie

genre
18

page
1

output_language
en

language
en

GET
Search Basic (FREE) without Params
{{search_basic}}
Add request description…
Query Params
country
us

service
netflix

type
movie

genre
18

page
1

output_language
en

language
en

GET
Search Basic (FREE) without Params&Headers
{{search_basic}}
Add request description…
Query Params
country
us

service
netflix

type
movie

genre
18

page
1

output_language
en

language
en

GET
Search Basic (FREE)
{{search_basic}}?country=us&service=netflix&type=movie&genre=18&page=1&output_language=en&language=en
Add request description…
Request Headers
X-RapidAPI-Key
{{X-RapidAPI-Key}}

X-RapidAPI-Host
{{X-RapidAPI-Host}}

Query Params
country
us

service
netflix

type
movie

genre
18

page
1

output_language
en

language
en

GET
Seach Ultra
https://streaming-availability.p.rapidapi.com/search/ultra?country= us&services= netflix,hulu&type= movie&order_by= imdb_vote_count&year_min= 2000&year_max= 2020&page= 1&genres= 18,80&genres_relation= or&desc= true&language= en&min_imdb_rating= 70&max_imdb_rating= 90&min_imdb_vote_count= 10000&max_imdb_vote_count= 1000000&output_language= en
Add request description…
Request Headers
X-RapidAPI-Key
8a2c6ddf34msh8ebb9066ad9470ep132001jsn31ecbda6e8d5

X-RapidAPI-Host
streaming-availability.p.rapidapi.com

Query Params
country
us

services
netflix,hulu

type
movie

order_by
imdb_vote_count

year_min
2000

year_max
2020

page
1

genres
18,80

genres_relation
or

desc
true

language
en

min_imdb_rating
70

max_imdb_rating
90

min_imdb_vote_count
10000

max_imdb_vote_count
1000000

output_language
en

GET
Search Pro
https://streaming-availability.p.rapidapi.com/search/pro?country= us&services= netflix&type= movie&order_by=original_title&year_min= 2000&year_max= 2020&page= 1&genres= 18&genres_relation= or&desc= true&language= en&output_language= en
Add request description…
Request Headers
X-RapidAPI-Key
8a2c6ddf34msh8ebb9066ad9470ep132001jsn31ecbda6e8d5

X-RapidAPI-Host
streaming-availability.p.rapidapi.com

Query Params
country
us

services
netflix

type
movie

order_by
original_title

year_min
2000

year_max
2020

page
1

genres
18

genres_relation
or

desc
true

language
en

output_language
en

Get
Add folder description…
Get Basic (FREE)
Add folder description…
GET
Get Basic (FREE) without country params
{{get_basic}}?tmdb_id=movie/120&output_language=en
Add request description…
Request Headers
X-RapidAPI-Key
{{X-RapidAPI-Key}}

X-RapidAPI-Host
{{X-RapidAPI-Host}}

Query Params
country
us

tmdb_id
movie/120

output_language
en

GET
Get Basic (FREE) with wrong country params
{{get_basic}}?country=pk&tmdb_id=movie/120&output_language=en
Add request description…
Request Headers
X-RapidAPI-Key
{{X-RapidAPI-Key}}

X-RapidAPI-Host
{{X-RapidAPI-Host}}

Query Params
country
pk

tmdb_id
movie/120

output_language
en

GET
Get Basic (FREE) without tmdb_id params
{{get_basic}}?country=us&output_language=en
Add request description…
Request Headers
X-RapidAPI-Key
{{X-RapidAPI-Key}}

X-RapidAPI-Host
{{X-RapidAPI-Host}}

Query Params
country
us

tmdb_id
movie/120

output_language
en

GET
Get Basic (FREE) with wrong tmdb_id params
{{get_basic}}?country=us&tmdb_id=movie&output_language=en
Add request description…
Request Headers
X-RapidAPI-Key
{{X-RapidAPI-Key}}

X-RapidAPI-Host
{{X-RapidAPI-Host}}

Query Params
country
us

tmdb_id
movie

output_language
en

GET
Get Basic (FREE) without output_language params
{{get_basic}}?country=us&tmdb_id=movie/120
Add request description…
Request Headers
X-RapidAPI-Key
{{X-RapidAPI-Key}}

X-RapidAPI-Host
{{X-RapidAPI-Host}}

Query Params
country
us

tmdb_id
movie/120

output_language
en

GET
Get Basic (FREE) with wrong output_language params
{{get_basic}}?country=us&tmdb_id=movie/120&output_language=eng
Add request description…
Request Headers
X-RapidAPI-Key
{{X-RapidAPI-Key}}

X-RapidAPI-Host
{{X-RapidAPI-Host}}

Query Params
country
us

tmdb_id
movie/120

output_language
eng

Optional

GET
Get Basic (FREE) without X-RapidAPI-key header
{{get_basic}}?country=us&tmdb_id=movie/120&output_language=en
Add request description…
Request Headers
X-RapidAPI-Host
{{X-RapidAPI-Host}}

Query Params
country
us

tmdb_id
movie/120

output_language
en

Optional

GET
Get Basic (FREE) with wrong X-RapidAPI-key
{{get_basic}}?country=us &tmdb_id=movie/120&output_language=en
Add request description…
Request Headers
X-RapidAPI-Key
8a2c6ddf34msh8ebb9066ad94

X-RapidAPI-Host
streaming-availability.p.rapidapi.com

Query Params
country
us

tmdb_id
movie/120

output_language
en

GET
Get Basic (FREE) without X-RapidAPI-Host header
{{get_basic}}?country=us &tmdb_id=movie/120&output_language=en
Add request description…
Request Headers
X-RapidAPI-Key
{{X-RapidAPI-Key}}

Query Params
country
us

tmdb_id
movie/120

output_language
en

GET
Get Basic (FREE) with wrong X-RapidAPI-Host
{{get_basic}}?country=us &tmdb_id=movie/120&output_language=en
Add request description…
Request Headers
X-RapidAPI-Key
{{X-RapidAPI-Key}}

X-RapidAPI-Host
streaming-availability.p

Query Params
country
us

tmdb_id
movie/120

output_language
en

GET
Get Basic (FREE)
{{get_basic}}?country=us &tmdb_id=movie/120&output_language=en
Add request description…
Request Headers
X-RapidAPI-Key
{{X-RapidAPI-Key}}

X-RapidAPI-Host
{{X-RapidAPI-Host}}

Query Params
country
us

tmdb_id
movie/120

output_language
en

GET
Get Ultra
https://streaming-availability.p.rapidapi.com/get/ultra?output_language= en&tmdb_id= tv/7225
Add request description…
Request Headers
X-RapidAPI-Key
8a2c6ddf34msh8ebb9066ad9470ep132001jsn31ecbda6e8d5

X-RapidAPI-Host
streaming-availability.p.rapidapi.com

Query Params
output_language
en

tmdb_id
tv/7225

Base Utilities
Add folder description…
Genres (FREE)
Add folder description…
GET
Genres (FREE) without X-RapidAPI-Key
{{genres}}
Add request description…
Request Headers
X-RapidAPI-Host
{{X-RapidAPI-Host}}

GET
Genres (FREE) with wrong X-RapidAPI-Key
{{genres}}
Add request description…
Request Headers
X-RapidAPI-Key
8a2c6ddf34msh8ebb9066ad9470ep132001js

X-RapidAPI-Host
{{X-RapidAPI-Host}}

GET
Genres (FREE) without X-RapidAPI-Host
{{genres}}
Add request description…
Request Headers
X-RapidAPI-Key
{{X-RapidAPI-Key}}

GET
Genres (FREE) with wrong X-RapidAPI-Host
{{genres}}
Add request description…
Request Headers
X-RapidAPI-Key
{{X-RapidAPI-Key}}

X-RapidAPI-Host
streaming-availability

GET
Genres (FREE)
{{genres}}
Add request description…
Request Headers
X-RapidAPI-Key
{{X-RapidAPI-Key}}

X-RapidAPI-Host
{{X-RapidAPI-Host}}

Countries (FREE)
Add folder description…
GET
Countries (FREE) without X-RapidAPI-key
{{countries}}
Add request description…
Request Headers
X-RapidAPI-Host
{{X-RapidAPI-Host}}

GET
Countries (FREE) with wrong X-RapidAPI-key
{{countries}}
Add request description…
Request Headers
X-RapidAPI-Key
8a2c6ddf34msh8ebb9066ad9470ep13

X-RapidAPI-Host
{{X-RapidAPI-Host}}

GET
Countries (FREE) without X-RapidAPI-Host
{{countries}}
Add request description…
Request Headers
X-RapidAPI-Key
{{X-RapidAPI-Key}}

GET
Countries (FREE) with wrong X-RapidAPI-Host
{{countries}}
Add request description…
Request Headers
X-RapidAPI-Key
{{X-RapidAPI-Key}}

X-RapidAPI-Host
streaming-availability

GET
Countries (FREE)
{{countries}}
Add request description…
Request Headers
X-RapidAPI-Key
{{X-RapidAPI-Key}}

X-RapidAPI-Host
{{X-RapidAPI-Host}}

Changes and Leaving
Add folder description…
GET
Leaving
https://streaming-availability.p.rapidapi.com/leaving?service=hulu&country=us&type=movie&output_language=en
Add request description…
Request Headers
X-RapidAPI-Key
8a2c6ddf34msh8ebb9066ad9470ep132001jsn31ecbda6e8d5

X-RapidAPI-Host
streaming-availability.p.rapidapi.com

Query Params
service
hulu

country
us

type
movie

output_language
en

GET
Changes (Ultra)
https://streaming-availability.p.rapidapi.com/changes?service=netflix&country=us&change_type=new&type=movie&output_language=en
Add request description…
Request Headers
X-RapidAPI-Key
8a2c6ddf34msh8ebb9066ad9470ep132001jsn31ecbda6e8d5

X-RapidAPI-Host
streaming-availability.p.rapidapi.com

Query Params
service
netflix

country
us

change_type
new

type
movie

output_language
en
