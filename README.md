# Recipe aggregator

There are lots of great recipe sites out there. Often when I ask for a recipe, a friend
will rave about a particular recipe site or author, and provide a link. That site or
author may be amazing at one particular thing (e.g. I hear Smitten Kitchen has great
baking recipes), but not others.

Without knowing about all of the different recipe sites or knowing who to ask, it's hard
to find good recipes. Google search results are terrible.


## Idea

A recipe aggregator site acts much like a news or other link aggregator: enable users to
easily submit links and vote on links that are valuable to them. In this case, the link
aggregation will happen at the "Dish" level. Many dishes have countless variants, so it
will be challenging to pick a level of abstraction to stop at, for example: Are
"cheeseburgers" a variant of "hamburgers", or their own dish? It will have to be a
community process that balances user and maintainer needs.


### How?

I feel that this database should be managed within a GitHub repository (or many) by a
community of cooks and authors. Perhaps GitHub Discussions, which already supports
voting, can be the data entry mechanism, and GitHub Actions can automate converting that
data into interoperable, re-usable formats (JSON?) in GitHub repositories.

A website can be generated which has access to this data and focuses on making the data
findable and accessible.


#### Like _Conda Forge?_

I feel like I keep coming back to the _Conda Forge_ model for everything these days, but
I think that's because I'm thinking a lot more about community-building lately. Conda
Forge has been a massive success in community-building, so I don't feel too bad about
learning from it :)
