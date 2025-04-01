# cinemapedia

A new Flutter project.

## Specific Topics in the First Section
This section will lay the groundwork for everything we'll begin building here and in a couple of additional sections.

The idea is to start creating reusable, structured, and expandable code from the start, making it easier to add new features in the future.

Specifically, we'll cover:

 - Datasources
    - Implementations
    - Abstractions
 - Repositories
    - Implementations
    - Abstractions
 - Models
 - Entities
 - Riverpod
    - Provider
    - StateNotifierProvider
    - Notifiers
 - Mappers

The entire goal of this section is to establish the orderly foundations of our architecture so we can strengthen them and see them in practice.

## Specific Topics in the Second Section

This section aims to perform 4 queries on TheMovieDB to obtain:

 - Popular movies
 - Movies in theaters
 - Top-rated movies
 - Movies coming soon

To achieve this, we'll continue working with the same principles and gradually build a robust application.

We'll also learn a little about infinite horizontal scrolling, slivers, and more.

## Specific Topics in the Third Section

This section is dedicated to the design of the movie screen individually, we will learn to pass parameters, loaders, chips, and additionally we will have to bring in the actors.

This means that we have to rework a new entity, datasources, repositories and so on to keep responsibilities separate.

## Specific Topics in Four Section

This section aims to learn how to perform searches and work with SearchDelegate, specifically we will cover:

 - SearchDelegate
 - Datasources
 - Repositories
 - Searching against TheMovieDB
 - Debouncer
 - Streams
 - Builders
 - DRY
 - Providers

In this section, we will build a complete and robust search engine so that our users can search for their movies there and preserve previous searches to improve its performance.

## Dev
 1. Copy the .env.template and rename it to .env
 2. Change the environment variables (The MovieDB)