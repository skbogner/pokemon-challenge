# Coding Challenge
You are provided a dataset of Pokemons - why not?
Your task is to build a backend to serve the dataset through an api,
and a frontend to browse, sort or compare Pokemons somehow.

# Backend
**You can implement this beforehand if you want to.**
You are to build a simple backend that reads in the dataset and publishes
through an api. You can either just load the datafile directly or you can
put it in a database.
The backend will not be the focus of this challenge, but it still counts some.

## Requirements
The only requirement here is that you use JS. You can use express, koa or any
other framework. You can provide a REST, GraphQL or any other type of API you
like.

# Frontend
**Don't build this before showing up**
You are to build a frontend that accesses the dataset through the backend you built.
It has to at the very least provide the following features:

- List pokemons (with a free-text filter on name of pokemon)
- Compare two pokemons (somehow select two pokemons and see their stats compared side
by side)

Other than that it is up to you how you want to built it and what features you want to
add. If you need ideas, here are a few:

- Sort pokemons by either stat. Ascending and descending.
- Compare any number of selected pokemons (highligthing the best in each stat).
- Filter pokemons on other stat than name. (ex. only Grass type)

But if you can make up your own features that would be awesome!

## Requirements
Again use JS. Use a framework, React would be best, then Vue, then some other framework.

- Don't worry too much about styling as long as it's not a complete mess.
Rather worry about your code, the way you structure it
and actually implementing some of the features.

- But don't focus on feature completeness. Besides the two *required* features, focus on providing
what you consider closer to production-ready code over more features.

- But don't test everything. There is no time for that. If you can choose one feature and provide
tests for it, that is great!

# Example data
The data is provided as a csv file with the following format:
\#,Name,Type 1,Type 2,Total,HP,Attack,Defense,Sp. Atk,Sp. Def,Speed,Generation,Legendary
1,Bulbasaur,Grass,Poison,318,45,49,49,65,65,45,1,False