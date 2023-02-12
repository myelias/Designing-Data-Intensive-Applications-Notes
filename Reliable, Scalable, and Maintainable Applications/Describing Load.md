## Load can be described using a load parameter. A load parameter can be something like requests per second to a web server, the ratio of reads to writes in a database, the number of simultaneously active users in a chat room, the hit rate on a cache, etc...
<br/>

# Let us consider Twitter. Two of Twitter's main operations are:
<br/>


## ***Post tweet*** - A user can publish a new message to their followers (4.6k requests/sec on average, over 12k requests/sec at peak).    
## ***Home timeline*** - A user can view tweets posted by the people they follow(300k requests/sec)

## Twitter's scaling challenge is not primarily due to tweet volume, but due to fan-out- each user follows many people, and each user is followed by many people.

# There are 2 ways of implementing these 2 operations:
